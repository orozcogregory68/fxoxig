蓝图官方开户【Q-——333307——】蓝图官方开户【 辋芷《888yx●vip》 】
蓝图官方开户【Q-——333307——】蓝图官方开户【 辋芷《888yx●vip》 】

 从零到一：用Github Actions搭建个人博客自动部署流水线

最近在重构个人技术博客时，踩了不少CI/CD的坑。今天把这套基于Github Actions的自动部署方案分享出来，尤其适合使用Hexo或Hugo的静态站点。全文操作可复现，照着做就行。

 为什么需要自动化部署？
手动执行`hexo g`再`git push`，每次更新文章都要重复登录服务器，效率低且容易出错。通过Github Actions，只需推代码到仓库，云端自动完成构建并推送至服务器（如Nginx或OSS），真正实现“push即发布”。

 核心工作流配置
在项目根目录创建`.github/workflows/deploy.yml`：

```yaml
name: Deploy Blog
on:
  push:
    branches: [ main ]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: actions/setup-node@v3
        with:
          node-version: '18'
      - run: npm install
      - run: npm run build
      - uses: easingthemes/ssh-deploy@v2.1.5
        env:
          SSH_PRIVATE_KEY: ${{ secrets.SSH_KEY }}
          REMOTE_HOST: ${{ secrets.HOST }}
          REMOTE_USER: ${{ secrets.USER }}
          SOURCE: public/
          TARGET: /var/www/blog
```

 关键配置说明
1. Secrets管理：在Repo的Settings→Secrets中添加SSH私钥、服务器IP等敏感信息，避免明文泄露。
2. 分支触发：指定`main`分支（或你的默认分支），推送即触发流水线。
3. 构建缓存优化：可添加`cache`依赖，将`node_modules`缓存，缩短下次构建时间约40%。

 进阶技巧：定时触发与多环境
通过`schedule`语法加`cron`表达式（如`schedule: - cron: '0 3   '`），可设定每日自动更新。若需多环境（测试/生产），可复用同一workflow并传入不同环境变量。

 避坑指南
- 路径问题：确认`SOURCE`指向构建产物目录，Hexo默认为`public/`，Hugo为`public/`，VuePress为`docs/.vuepress/dist`。
- SSH密钥格式：私钥需为`-----BEGIN OPENSSH PRIVATE KEY-----`格式，若为RSA需转换。
- 首次连接：在`ssh-deploy`步骤前添加`ssh-keyscan`录入指纹，避免主机验证失败。

 效果与收益
改造后，博客更新从3分钟缩短至10秒。GitHub免费版提供2000分钟/月的构建时长，个人项目绰绰有余。配合Google Analytics与Sitemap插件，文章更快被搜索引擎收录。

---

快去试试吧！ 如果遇到报错，把错误日志发在评论区，我帮你排查。也欢迎分享你的自动化部署案例。

相关推荐：

https://github.com/brownbarbara40/yzuprm/blob/main/2026%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%A8%B1%E4%B9%90%E7%BD%91%E5%9D%80_%E5%92%8F%E5%82%BA%E7%BA%B1%E5%9E%82%E4%BF%A3KRELU.md

<img src="https://i.postimg.cc/zXVhX2BP/lantu-00013.png" />

相关推荐：

https://github.com/brownbarbara40/yzuprm/commit/70afb6d7a496294e60376604533d2ced9476cb16

<img src="https://i.postimg.cc/kGjWYk5W/lantu-00006.png" />
相关推荐：

https://github.com/nielsenholly4115/bdgoxe/blob/main/2026%E5%AE%98%E6%96%B9%E7%83%AD%E6%A2%97%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95_%E5%A6%93%E5%8F%AF%E9%A1%BF%E6%B3%BB%E5%BD%B1EYZTA.md

<img src="https://i.postimg.cc/9fTtX8xf/lantu-00003.png" />
相关推荐：

https://github.com/nielsenholly4115/bdgoxe/commit/a731b907b2803b0d1bf136085e0018cc90c2c256

<img src="https://i.postimg.cc/FsWxTJds/lantu-00002.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
