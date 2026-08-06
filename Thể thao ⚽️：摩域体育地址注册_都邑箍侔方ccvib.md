摩域体育地址注册【Q-——333307——】摩域体育地址注册【 辋芷《888yx●vip》 】
摩域体育地址注册【Q-——333307——】摩域体育地址注册【 辋芷《888yx●vip》 】

 从0到1搭建个人技术博客：GitHub Pages + Hugo 完整指南

> 还在为写技术文章没地方发愁？用GitHub Pages免费搭建个人博客，零成本、可定制、支持自定义域名，还能顺便提升你的开源影响力。本教程手把手带你30分钟上线。

 为什么选择GitHub Pages建博客

对于开发者来说，GitHub Pages是搭建个人技术博客的首选方案。它免费、稳定、支持HTTPS，最重要的是与GitHub生态无缝集成——写完Markdown直接push，自动触发部署，省去服务器运维的烦恼。配合Hugo或Hexo等静态站点生成器，还能获得极快的访问速度。

搜索引擎对静态站点尤其友好，页面加载快、结构清晰，天然利于百度收录。而且GitHub Pages支持自定义域名，你可以绑定自己的专属网址，建立个人品牌。

 第一步：创建GitHub仓库

登录GitHub，点击“New repository”，命名格式必须是`username.github.io`（username换成你的用户名）。选择Public可见性，勾选“Add a README file”初始化仓库。

 第二步：安装Hugo并初始化站点

Hugo是Go语言编写的静态站点生成器，安装简单、构建极快。Mac用户执行`brew install hugo`，Windows用户用`choco install hugo`。确认安装后，在本地执行：

```bash
hugo new site my-blog
cd my-blog
```

 第三步：选择并配置主题

Hugo社区有超300款主题，推荐PaperMod（简洁美观）或LoveIt（功能丰富）。以PaperMod为例：

```bash
git init
git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
```

在`config.toml`中添加`theme = "PaperMod"`，然后新建第一篇

```bash
hugo new posts/my-first-post.md
```

 第四步：部署到GitHub Pages

在本地生成静态文件：

```bash
hugo -D
```

将public目录内容推送到仓库：

```bash
git add .
git commit -m "deploy blog"
git branch -M main
git remote add origin https://github.com/username/username.github.io.git
git push -u origin main
```

仓库会在Actions中自动构建，几分钟后访问`username.github.io`即可看到你的博客。

 互动引导：免费领取SEO关键词布局清单

博客搭建完成后，如何让百度更快收录？欢迎在评论区留言“关键词”，我整理了“技术博客SEO优化关键词布局表”免费分享给你。关注我，下期将详解如何通过内链和外链提升文章排名。

---

小提示：使用GitHub Pages建站完全免费，但百度收录需要主动提交站点地图。在博客根目录添加`sitemap.xml`，然后通过百度搜索资源平台提交，可以加速收录进程。有问题随时在评论区交流，我看到都会回复的。

相关推荐：

https://github.com/lopezmatthew2/pfcyfz/blob/main/ch%E1%BB%8Di%20g%C3%A0%20%F0%9F%90%94%20%EF%BC%9A%E6%91%A9%E5%9F%9F%E4%BD%93%E8%82%B2%E5%B9%B3%E5%8F%B0%E5%AE%A2%E6%9C%8D_%E5%A8%9C%E4%BB%9D%E7%93%A4%E8%AE%B6%E6%B9%9Bmiktj.md

<img src="https://i.postimg.cc/wMLK7NjM/moyutiyu3-00002.png" />

相关推荐：

https://github.com/lopezmatthew2/pfcyfz/commit/1ae609c79b637f219f72ca3a4e127b6f21ed6ad7

<img src="https://i.postimg.cc/T1g8pb32/moyutiyu3-00001.png" />
相关推荐：

https://github.com/haydendouglas1/jorysh/blob/main/C%E1%BB%91c%20Games%20%F0%9F%A5%8A%EF%BC%9A%E6%91%A9%E5%9F%9F%E4%BD%93%E8%82%B2%E5%B9%B3%E5%8F%B0%E4%B8%8B%E8%BD%BD_%E8%A2%92%E8%97%A4%E8%B9%A6%E7%AB%A0%E6%81%BFonnnm.md

<img src="https://i.postimg.cc/GhPwRvN1/moyutiyu3-00014.png" />
相关推荐：

https://github.com/haydendouglas1/jorysh/commit/e03a919156c4942d2df6642cf17679cff8b1b905

<img src="https://i.postimg.cc/wMLK7NjM/moyutiyu3-00002.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
