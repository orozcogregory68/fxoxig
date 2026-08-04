蓝图主管注册【Q-——333307——】蓝图主管注册【 辋芷《888yx●vip》 】
蓝图主管注册【Q-——333307——】蓝图主管注册【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025新版）

你是否厌倦了在CSDN、掘金上写文章却担心平台算法变动？是否想要一个完全属于自己、永久免费且支持自定义域名的技术博客？今天这篇教程，手把手教你用 GitHub Pages + Hexo 搭建一个轻量级、高颜值的个人站点。

 为什么选择Hexo + GitHub Pages？

- 完全免费：托管在GitHub，无服务器成本。
- 极速加载：生成纯静态页面，CDN加速秒开。
- SEO友好：无需数据库，百度收录快。
- 版本管理：所有文章用Git管理，永不怕丢失。

 三步快速启动你的博客

 第一步：环境准备
安装 [Node.js](https://nodejs.org/) (建议LTS版本) 和 Git。打开终端验证：`node -v` 和 `git --version`。

 第二步：本地初始化Hexo
```bash
npm install hexo-cli -g
hexo init myblog && cd myblog
npm install
hexo s
```
浏览器访问 `http://localhost:4000`，看到默认博客即成功。

 第三步：部署到GitHub
1. 在GitHub新建仓库：`你的用户名.github.io`。
2. 修改根目录 `_config.yml` 中的deploy配置：
```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
```
3. 执行部署：
```bash
npm install hexo-deployer-git --save
hexo d
```

 进阶优化：让百度更快收录

- 主动提交链接：在百度搜索资源平台提交站点地图 `sitemap.xml`（安装 `hexo-generator-sitemap` 插件）。
- 内链建设：在文章中自然链接到博客其他相关文章，提升爬虫抓取深度。
- 关键词布局：标题包含核心词（如"GitHub Pages搭建教程"），正文中自然地重复2-3次。

 遇到问题怎么办？
- 端口被占用：使用 `hexo s -p 5000` 更换端口。
- 部署失败：检查仓库名是否完全等于 `用户名.github.io`。
- 样式丢失：清除浏览器缓存或执行 `hexo clean && hexo g && hexo d`。

看到这里，你已经能独立搭建一个博客了！ 如果这篇文章对你有帮助，点赞 支持一下，让更多朋友看到。有任何问题，欢迎在评论区留言，我会逐一回复解答。

后续想了解 如何自定义主题 或 百度SEO优化 的朋友，记得 关注，下期分享更多干货！你的第一个技术博客，今天就动手搭建吧！

相关推荐：

https://github.com/leebradley6/ubrqlg/blob/main/2026%E5%AE%98%E7%BD%91%E6%8C%87%E5%8D%97%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%B9%B3%E5%8F%B0%E4%B8%BB%E7%AE%A1_%E7%88%AC%E8%B4%A8%E6%A6%B7%E6%82%94%E9%B2%9CVOBQE.md

<img src="https://i.postimg.cc/mkZQwbTF/lantu-00005.png" />

相关推荐：

https://github.com/leebradley6/ubrqlg/commit/eef53512194c7545e4892c5c8ca2d518ee33b5b8

<img src="https://i.postimg.cc/mkZQwbTF/lantu-00005.png" />
相关推荐：

https://github.com/larsenpaul061/lcndhr/blob/main/2026%E5%AE%98%E7%BD%91%E8%AE%BF%E8%B0%88%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%B9%B3%E5%8F%B0%E5%AE%A2%E6%9C%8D_%E6%85%B7%E7%9B%85%E9%85%B6%E5%AB%A1%E6%82%A3BVJRM.md

<img src="https://i.postimg.cc/6QsnPV9w/lantu-00010.png" />
相关推荐：

https://github.com/larsenpaul061/lcndhr/commit/7363d6afbae6ace18736e5390df5892e23729a83

<img src="https://i.postimg.cc/ZnqdNVLn/lantu-00012.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
