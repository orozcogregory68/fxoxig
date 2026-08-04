蓝图地址app【Q-——333307——】蓝图地址app【 辋芷《888yx●vip》 】
蓝图地址app【Q-——333307——】蓝图地址app【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Jekyll 完整教程

还在羡慕别人拥有独立博客？其实，借助 GitHub Pages 和 Jekyll，你也能在半小时内搭建一个免费、稳定、支持自定义域名的个人网站。本文为你提供一份保姆级教程，从环境配置到部署上线，一步不落。

 为什么选择 GitHub Pages？

- 完全免费：无需购买服务器，GitHub 为你提供静态托管。
- 版本管理：所有内容基于 Git，历史记录清晰可溯。
- SEO友好：静态页面加载速度快，天生利于搜索引擎收录。
- 一键部署：推代码即更新，自动化程度高。

 环境准备：你需要什么？

在开始前，请确保你已完成：
1. 注册一个 GitHub 账号。
2. 本地安装 Git 工具。
3. 安装 Ruby 和 Jekyll（Windows 用户建议通过 RubyInstaller 安装）。

 第一步：创建代码仓库

1. 登录 GitHub，点击右上角 “+” 选择 New repository。
2. 仓库名格式必须为：`你的用户名.github.io`。
3. 勾选 “Public” 后点击创建。

 第二步：初始化 Jekyll 项目

打开终端，克隆刚创建的仓库到本地：

```bash
git clone https://github.com/你的用户名/你的用户名.github.io.git
cd 你的用户名.github.io
```

安装 Jekyll 并启动本地服务：

```bash
gem install jekyll bundler
jekyll new . --force
bundle exec jekyll serve
```

浏览器访问 `http://localhost:4000`，即可预览默认博客。

 第三步：配置站点信息

编辑根目录下的 `_config.yml` 文件，修改关键参数：

- `title`：站点- `description`：站点描述（建议包含关键词，利于 SEO）
- `baseurl`：通常留空
- `url`：设置为 `https://你的用户名.github.io`

修改后记得重启 Jekyll 服务。

 第四步：发布到 GitHub

```bash
git add .
git commit -m "初始化博客"
git push origin main
```

等待约 1-2 分钟，访问 `https://你的用户名.github.io`，你的博客就正式上线了！

 进阶优化与互动引导

- 绑定自定义域名：在仓库 Settings 中找到 Pages 设置，添加你的域名并配置 CNAME 记录。
- 使用评论系统：集成 Gitalk 或 utterances，让读者能够互动留言。
- SEO 优化：安装 `jekyll-seo-tag` 插件，并为每篇文章编写合适的 title 和 description。

如果你在搭建过程中遇到任何问题，欢迎在评论区留言提问，我会第一时间为你解答。如果本文对你有帮助，别忘了点赞和转发，让更多朋友学会搭建属于自己的独立博客！

现在就开始行动吧，动手创建你的第一个 GitHub Pages 博客！

相关推荐：

https://github.com/brownbarbara40/yzuprm/blob/main/2026%E6%9D%83%E5%A8%81%E8%A7%A3%E6%9E%90%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%B9%B3%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E7%9E%8E%E4%BD%B3%E7%84%89%E8%B0%AA%E8%BD%BDAAUBI.md

<img src="https://i.postimg.cc/FsWxTJds/lantu-00002.png" />

相关推荐：

https://github.com/brownbarbara40/yzuprm/commit/1b3ce48aed46faed647e3ab3cf56f30a239f5137

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />
相关推荐：

https://github.com/bakerangela2326/pvryuo/blob/main/2026%E5%AE%98%E7%BD%91%E6%89%8B%E5%86%8C%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%B9%B3%E5%8F%B0%E5%AE%A2%E6%9C%8D_%E9%98%89%E5%8A%AB%E8%BD%BD%E5%87%89%E6%BD%AEEYFFF.md

<img src="https://i.postimg.cc/6QsnPV9w/lantu-00010.png" />
相关推荐：

https://github.com/bakerangela2326/pvryuo/commit/a9e644486149cee1a046553abbf4b6e8b6f1dde2

<img src="https://i.postimg.cc/FsWxTJds/lantu-00002.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
