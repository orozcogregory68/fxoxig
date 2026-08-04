蓝图开户地址【Q-——333307——】蓝图开户地址【 辋芷《888yx●vip》 】
蓝图开户地址【Q-——333307——】蓝图开户地址【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

还在羡慕大佬们炫酷的个人博客？其实你也能轻松拥有。今天这份教程，手把手教你用 GitHub Pages 和 Hexo 免费搭建一个高颜值、加载快的技术博客，无需服务器，无需域名成本，全程可视化操作。记得先收藏，一步一步跟着做。

 为什么选择 GitHub Pages + Hexo？

- 完全免费：托管和域名费用全省了。
- 极速访问：依托 GitHub 全球 CDN，国内访问速度也可接受。
- 高度定制：海量主题与插件，代码高亮、SEO 优化一应俱全。
- 写作友好：支持 Markdown 语法，专注内容创作。

 前置准备：你需要这三个账号/工具

1. GitHub 账号：用来创建仓库并托管网站。
2. Git 客户端：用于代码同步（推荐下载官方 Git for Windows/Mac）。
3. Node.js 环境：Hexo 依赖运行，建议安装 LTS 长期支持版。

 五步搭建：从零到上线

 Step 1：创建 GitHub 仓库

登录 GitHub，点击右上角 “+” → New repository。仓库名格式必须为 `你的用户名.github.io`（例如 `sunshine0920.github.io`），勾选 Public，点击创建。

 Step 2：本地安装 Hexo 脚手架

打开终端，依次执行以下命令（Windows 请用 Git Bash）：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

 Step 3：关联 GitHub 并部署

修改根目录下的 `_config.yml` 文件，将 deploy 部分改为：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

然后安装自动部署插件，并更新到远端：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate && hexo deploy
```

 Step 4：选择一款高颜值主题

访问 Hexo 主题官网或 GitHub 搜索 “Hexo 主题”，推荐热门主题 NexT、Fluid、Butterfly。以 NexT 为例：

```bash
git clone https://github.com/theme-next/hexo-theme-next themes/next
```

在 `_config.yml` 中修改 `theme: next`，然后重新部署。

 Step 5：发布第一篇博客

在 `source/_posts/` 下新建 Markdown 文件，写入内容后再次执行 `hexo g -d` 即可上线。

 常见问题速递

Q：本地预览效果和线上不一样？  
A：务必执行 `hexo clean` 清缓存后再部署。

Q：如何绑定自己的域名？  
A：在仓库 Settings → Pages 中填写自定义域名，并在 DNS 管理处添加 CNAME 解析。

Q：国内访问慢怎么办？  
A：可尝试将 GitHub Pages 接入 CDN 加速，或在 Hexo 中启用 Gzip 压缩。

---

搭建过程中如果遇到报错，欢迎在评论区留言，我会第一时间帮你排查。也欢迎分享你的博客链接，让大家互相学习！

觉得有用就点赞 + 转发，让更多小伙伴告别繁琐建站。关注我，后续将带来更多 SEO 优化、主题魔改 的进阶干货！

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/blob/main/2026%E5%AE%98%E6%96%B9%E7%83%AD%E6%A2%97%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E7%BD%91%E4%BB%A3%E7%90%86_%E6%99%AE%E5%A6%93%E8%B0%88%E8%B0%80%E6%8E%8CBIAUI.md

<img src="https://i.postimg.cc/rsg9XDf0/lantu-00001.png" />

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/commit/c0f4bf3ba3fbb4e0695aae02b70aa01e1854390e

<img src="https://i.postimg.cc/sfKP2ZJh/lantu-00007.png" />
相关推荐：

https://github.com/leebradley6/ubrqlg/blob/main/2026%E7%A7%91%E6%8A%80%E6%89%8B%E5%86%8C%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E7%BD%91app_%E6%83%AD%E6%81%BF%E9%A1%B5%E8%B0%AE%E5%91%98CWKLS.md

<img src="https://i.postimg.cc/50y4qGDp/lantu-00014.png" />
相关推荐：

https://github.com/leebradley6/ubrqlg/commit/0743aca78cbc6ac5469327a16d82101837cbd088

<img src="https://i.postimg.cc/mkZQwbTF/lantu-00005.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
