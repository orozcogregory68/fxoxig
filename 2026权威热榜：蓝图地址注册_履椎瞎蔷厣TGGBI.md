蓝图地址注册【Q-——333307——】蓝图地址注册【 辋芷《888yx●vip》 】
蓝图地址注册【Q-——333307——】蓝图地址注册【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

> 无需服务器，零成本，30分钟上线你的专属技术博客。

你是否厌倦了在第三方平台写作，却担心数据安全和排版限制？作为开发者，拥有一个完全自主的博客主页，既是技术名片，也是知识沉淀的最佳方式。GitHub Pages 免费提供静态托管，配合 Hexo 框架，轻松生成高性能站点。本文基于2025年最新环境，手把手教你完成部署。

 一、为什么选择 Hexo + GitHub Pages？

1. 完全免费：GitHub Pages 提供无限流量和带宽
2. 极速响应：静态页面加载速度远超动态博客
3. 版本控制：所有文章通过 Git 管理，历史可追溯

在动手前，请确保已安装 Git 和 Node.js（需大于 14.0 版本）。使用 `node -v` 和 `git --version` 验证环境。

 二、五分钟创建本地博客

打开终端，执行以下命令：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo server
```

浏览器访问 `http://localhost:4000`，看到默认页面即成功。此时本地博客已运行，但部署到 GitHub 还需三步配置。

 三、对接 GitHub 仓库

1. 新建仓库：在 GitHub 创建名为 `你的用户名.github.io` 的仓库
2. 安装部署插件：
   ```bash
   npm install hexo-deployer-git --save
   ```
3. 修改配置：编辑 `_config.yml` 文件，在末尾添加：
   ```yaml
   deploy:
     type: git
     repo: https://github.com/用户名/用户名.github.io.git
     branch: main
   ```

> 注意：2024年起 GitHub 默认分支已改为 `main`，旧教程多为 `master`，注意区分。

 四、一键部署与访问

执行 `hexo clean && hexo deploy`，等待命令执行完毕。访问 `https://用户名.github.io`，你的个人主页已正式上线！

进阶技巧：绑定自定义域名只需在仓库设置中添加 CNAME 记录，并在 `source` 目录放置同名文件。

---

你成功部署后第一篇文章准备写什么？ 欢迎在评论区分享你的博客地址，让更多人看到你的技术思考。如果本教程对你有帮助，请点赞收藏，你的支持是我持续输出的最大动力。

相关推荐：

https://github.com/bakerangela2326/pvryuo/blob/main/%E5%85%B1%E8%B5%B4%E6%96%87%E5%BF%83%E4%B9%8B%E7%BA%A6%EF%BC%9A%E8%93%9D%E5%9B%BE%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7_%E7%82%AE%E5%A9%AA%E5%88%82%E5%81%88%E6%B4%9EJQREE.md

<img src="https://i.postimg.cc/kGjWYk5W/lantu-00006.png" />

相关推荐：

https://github.com/bakerangela2326/pvryuo/commit/fb738e2616daf4f360f081a5a38e5f960942dd16

<img src="https://i.postimg.cc/rsg9XDf0/lantu-00001.png" />
相关推荐：

https://github.com/nielsenholly4115/bdgoxe/blob/main/2026%E5%AE%98%E6%96%B9%E7%88%86%E7%82%B9%EF%BC%9A%E8%93%9D%E5%9B%BE%E4%B8%BB%E7%AE%A1%E4%B8%BB%E7%AE%A1_%E5%AE%A4%E6%85%95%E4%B9%85%E6%BD%AD%E9%80%80OPWDX.md

<img src="https://i.postimg.cc/6QsnPV9w/lantu-00010.png" />
相关推荐：

https://github.com/nielsenholly4115/bdgoxe/commit/df66466371c5a9ba4616c071ee518547c28545a7

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
