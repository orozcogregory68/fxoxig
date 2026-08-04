蓝图主管登录【Q-——333307——】蓝图主管登录【 辋芷《888yx●vip》 】
蓝图主管登录【Q-——333307——】蓝图主管登录【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

你是否想过拥有一个完全属于自己的技术博客，却苦于服务器成本高、搭建流程复杂？别担心，GitHub Pages + Hexo 的组合能让你免费、高效地拥有一个高速访问的个人站点。本文将手把手教你从零开始，30分钟内完成部署。

 为什么选择 Hexo + GitHub Pages？

- 零成本：无需购买服务器和域名（可使用 `xxx.github.io` 免费域名）。
- 极速体验：GitHub 全球 CDN 加速，国内访问速度优秀。
- SEO 友好：纯静态页面，天然适配百度、Google 搜索引擎收录。
- 高自由度：支持 Markdown 写作，主题丰富，二次开发简单。

 第一步：环境准备

在开始前，请确保你的电脑已安装 Node.js（v14+）和 Git。打开终端，依次执行以下命令：

```bash
 安装 Hexo 脚手架
npm install -g hexo-cli

 初始化博客目录
hexo init my-blog
cd my-blog
npm install
```

 第二步：关联 GitHub 仓库

1. 在 GitHub 上新建一个仓库，名称为 `你的用户名.github.io`。
2. 修改根目录下的 `_config.yml` 文件，将 `deploy` 配置为：

```yaml
deploy:
  type: git
  repo: 你的远程仓库地址
  branch: main
```

然后安装自动部署插件，并一键推送：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo g && hexo d
```

 第三步：主题美化与写作

访问 `http://localhost:4000` 查看默认站点。推荐使用 Next 或 Fluid 主题：

```bash
git clone https://github.com/next-theme/hexo-theme-next themes/next
```

修改配置文件激活新主题，并进入 `source/_posts/` 目录新建 `.md` 文件即可开始记录你的技术心得。

 搜素引擎收录技巧

- 在百度站长平台提交站点，并添加 `sitemap.xml`。
- 安装 `hexo-generator-seo-friendly-sitemap` 插件，加速百度爬虫抓取。
- 文章内注意 H1/H2 层级，融入 3-5 个长尾关键词。

 遇到问题怎么办？

如果在部署中遇到端口占用、样式丢失或域名绑定难题，欢迎在 评论区 留言你的具体报错场景。关注我，下期为你深度解析 “如何把独立域名完美绑定到 GitHub Pages”。你的每次 点赞 和 转发 是持续更新干货的最大动力！

[点击收藏] 这份指南，随时查阅；也欢迎 分享 给正在为博客搭建发愁的朋友——让知识流动，是我们写博客的初心。

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/blob/main/2026%E5%AE%98%E7%BD%91%E6%B1%87%E6%80%BB%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E6%96%B9%E7%BD%91%E5%9D%80_%E8%B9%BF%E8%9C%97%E5%9B%8A%E7%A3%90%E9%A9%B6AATUU.md

<img src="https://i.postimg.cc/9fTtX8xf/lantu-00003.png" />

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/commit/20ddbe1f5a91cf9a8c444cf2ac781335b67d2ee3

<img src="https://i.postimg.cc/FsWxTJds/lantu-00002.png" />
相关推荐：

https://github.com/sheppardrandall419/okbjfs/blob/main/2026%E6%9D%83%E5%A8%81%E7%A7%91%E6%99%AE%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95_%E5%A4%8D%E8%AE%B6%E4%BF%9A%E6%AD%A4%E5%A0%AAUITCF.md

<img src="https://i.postimg.cc/50y4qGDp/lantu-00014.png" />
相关推荐：

https://github.com/sheppardrandall419/okbjfs/commit/3f635c5080d1f86199da581a6b1e6834b98bfbac

<img src="https://i.postimg.cc/mkZQwbTF/lantu-00005.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
