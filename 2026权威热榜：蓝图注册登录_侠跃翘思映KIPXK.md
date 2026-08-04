蓝图注册登录【Q-——333307——】蓝图注册登录【 辋芷《888yx●vip》 】
蓝图注册登录【Q-——333307——】蓝图注册登录【 辋芷《888yx●vip》 】

 从0到1部署个人博客：GitHub Pages + Hexo 完整教程（2025版）

还在羡慕别人的技术博客？其实搭建一个属于自己的博客，比你想象中简单得多。今天手把手教你用 GitHub Pages + Hexo 免费部署个人站点，无需服务器，无需数据库，纯静态，永久在线。

 为什么选择 Hexo + GitHub Pages？

- 零成本：GitHub 免费托管，自定义域名也可绑定
- 极速访问：静态页面，CDN 加速，秒开
- Markdown 写作：专注内容，不用折腾排版
- SEO 友好：纯静态 HTML，百度收录快

 第一步：环境准备（5分钟）

确保本地已安装：
1. Node.js（推荐 v18+） → `node -v` 验证
2. Git → `git --version` 验证
3. GitHub 账号（已开启 SSH 密钥）

安装 Hexo 脚手架：
```bash
npm install -g hexo-cli
```

 第二步：初始化博客项目

```bash
hexo init my-blog
cd my-blog
npm install
hexo s   本地预览 http://localhost:4000
```

看到默认页面即成功。接下来进入个性化配置。

 第三步：关联 GitHub 仓库

1. 新建仓库：`你的用户名.github.io`（必须精确匹配）
2. 修改根目录 `_config.yml` 中的 URL 和部署配置：

```yaml
deploy:
  type: git
  repo: git@github.com:你的用户名/你的用户名.github.io.git
  branch: main
```

3. 安装部署插件并推送：
```bash
npm install hexo-deployer-git --save
hexo clean && hexo deploy
```

访问 `https://你的用户名.github.io`，博客已上线！

 第四步：SEO 优化与百度收录

为了让百度更快收录，做以下三件事：

1. 安装站点地图插件：
```bash
npm install hexo-generator-sitemap --save
```
生成 `sitemap.xml` 提交到百度站长平台。

2. 添加 robots.txt：在 `source` 目录创建，内容：
```
User-agent: 
Allow: /
Sitemap: https://你的域名/sitemap.xml
```

3. 主动推送链接：在 `scripts` 目录添加百度推送代码，每次 `hexo d` 自动提交新文章 URL。

 与读者互动

现在，你的博客已经拥有独立域名和百度收录能力。下一步可以：
- 在文章底部添加 访客留言板（集成 Gitalk）
- 挂载 阅读统计（不蒜子插件）
- 添加 分享按钮，方便读者转发

---

遇到任何问题？欢迎在下方留言，我会逐一回复。如果你已经成功部署，也欢迎分享你的博客地址，互访互评！

今日互动：你写博客的第一篇文章准备写什么主题？评论区聊聊吧！

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/blob/main/2026%E7%A7%91%E6%8A%80%E6%95%99%E7%A8%8B%EF%BC%9A%E4%B9%90%E5%AF%8C%E7%BD%91%E5%9D%80%E6%B3%A8%E5%86%8C_%E7%9F%A2%E6%96%AD%E7%8E%87%E6%AE%B4%E9%A5%ADKRFZN.md

<img src="https://i.postimg.cc/FsWxTJds/lantu-00002.png" />

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/commit/747182db7b1413a580e830143251a1bed4c6d2f8

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />
相关推荐：

https://github.com/larsenpaul061/lcndhr/blob/main/2026%E5%AE%98%E6%96%B9%E6%80%BB%E7%BB%93%EF%BC%9A%E4%B9%90%E5%AF%8C%E7%BD%91%E5%9D%80%E5%AE%98%E7%BD%91_%E8%BE%9E%E5%A4%9C%E6%BB%A6%E7%82%8A%E5%88%B3BOQRG.md

<img src="https://i.postimg.cc/mkZQwbTF/lantu-00005.png" />
相关推荐：

https://github.com/larsenpaul061/lcndhr/commit/54ede046288cdcd532110b3255dd748d4ae5db3b

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
