蓝图平台app【Q-——333307——】蓝图平台app【 辋芷《888yx●vip》 】
蓝图平台app【Q-——333307——】蓝图平台app【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

还在羡慕别人拥有独立博客？其实你只需要一个GitHub账号，就能免费搭建一个属于自己的技术博客站点。本文手把手教你完成Hexo部署，全程零成本，小白也能轻松上手。

 为什么选择GitHub Pages + Hexo？

- 完全免费：托管在GitHub服务器，无需购买云主机
- 访问速度快：依托GitHub全球CDN加速，国内访问也稳定
- Markdown写作：专注内容创作，屏蔽样式干扰
- SEO友好：静态页面天生适合搜索引擎收录，Google、百度均能快速抓取

 环境准备（3分钟）

在开始前，请确保电脑已安装以下工具：

1. Git：下载地址 [git-scm.com](https://git-scm.com)，Windows用户直接下一步安装
2. Node.js：推荐LTS版本，下载地址 [nodejs.org](https://nodejs.org)

安装完成后，打开终端（Mac用户用Terminal，Windows用户用PowerShell），输入以下命令验证：

```bash
node -v    输出 v18.x.x 即成功
git --version   输出 git version 2.x.x 即成功
```

 三步搭建博客（核心步骤）

 第一步：安装Hexo并初始化项目

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

 第二步：关联GitHub仓库

1. 在GitHub新建仓库，命名为 `你的用户名.github.io`
2. 修改根目录 `_config.yml` 文件，找到 `deploy` 段，配置为：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

 第三步：一键部署

```bash
npm install hexo-deployer-git --save
hexo clean && hexo g && hexo d
```

浏览器访问 `https://你的用户名.github.io`，你的博客已经上线！

 进阶技巧：如何让百度更快收录

由于GitHub Pages默认屏蔽百度爬虫，建议开启 `sitemap` 插件：

```bash
npm install hexo-generator-sitemap --save
```

同时，在 `_config.yml` 中添加：

```yaml
sitemap:
  path: sitemap.xml
```

最后，将 `https://你的用户名.github.io/sitemap.xml` 提交到[百度站长平台](https://ziyuan.baidu.com)，一般3-7天即可收录。

 遇到问题怎么办？

常见报错：
- `port 4000已被占用`：运行 `hexo server -p 4001`
- `deploy失败`：检查仓库名是否与你GitHub用户名一致

欢迎在评论区留言你的问题，或私信获取完整配置文件。如果本文对你有帮助，点个赞支持下吧！你的支持是我持续输出干货的最大动力。关注我，下期分享《Hexo主题美化：让博客颜值提升300%的NexT配置指南》。

相关推荐：

https://github.com/sheppardrandall419/okbjfs/blob/main/2026%E6%9D%83%E5%A8%81%E7%A7%91%E6%99%AE%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95_%E5%A4%8D%E8%AE%B6%E4%BF%9A%E6%AD%A4%E5%A0%AAUITCF.md

<img src="https://i.postimg.cc/c4bQRyjk/lantu-00008.png" />

相关推荐：

https://github.com/sheppardrandall419/okbjfs/commit/3f635c5080d1f86199da581a6b1e6834b98bfbac

<img src="https://i.postimg.cc/rsg9XDf0/lantu-00001.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/blob/main/2026%E6%9D%83%E5%A8%81%E7%A7%91%E6%99%AE%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E6%A1%88%E5%90%A8%E5%B1%8F%E5%B7%A7%E6%AC%A2DYGII.md

<img src="https://i.postimg.cc/T2Zb1qDM/lantu-00015.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/commit/a068948b450bb9f50be93b5930448a919f7e550a

<img src="https://i.postimg.cc/sfKP2ZJh/lantu-00007.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
