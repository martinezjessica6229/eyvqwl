乐富平台代理【Q-——333307——】乐富平台代理【 辋芷《888yx●vip》 】
乐富平台代理【Q-——333307——】乐富平台代理【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整指南

> 想拥有一个完全属于自己的技术博客？不买服务器、不备案、零成本，GitHub Pages + Hexo 就是最佳答案。本文手把手带你完成部署，文末有福利。

 为什么选择 GitHub Pages 搭建博客？

很多开发者都有写技术博客的需求。相比 CSDN、掘金等平台，GitHub Pages 拥有绝对的控制权：无广告、可绑定自定义域名、支持 HTTPS，更重要的是——你的所有文章都保存在 Git 仓库中，天然支持版本管理。

对于SEO优化而言，GitHub Pages 对搜索引擎友好，配合 Hexo 生成的静态页面加载极快，非常利于网站收录。当你搜索“GitHub Pages 搭建博客”时，大量教程都指向这套方案，可见其成熟度。

 第一步：创建 GitHub 仓库

首先，你需要一个 GitHub 账号。登录后点击右上角“+”号，新建仓库。这里有个关键细节：仓库名必须是 `你的用户名.github.io`（例如 `zhangsan.github.io`），这是 GitHub Pages 的特殊约定。

创建时勾选“Public”（公开），这样搜索引擎才能抓取你的内容。

 第二步：本地安装 Hexo 框架

Hexo 是一个基于 Node.js 的静态博客框架，以速度快、部署简单著称。安装前确保本地已有 Node.js 和 Git。

```bash
 全局安装 hexo-cli
npm install -g hexo-cli

 初始化博客目录
hexo init myblog
cd myblog
npm install
```

初始化完成后，目录结构非常清晰：
- `source/_posts/`：存放你的 Markdown 文章
- `themes/`：博客主题文件夹
- `_config.yml`：站点配置文件

 第三步：部署到 GitHub Pages

修改根目录下的 `_config.yml` 文件，在末尾填写部署信息：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io
  branch: main
```

执行一键部署命令：

```bash
npm install hexo-deployer-git --save
hexo g    生成静态文件
hexo d    部署到远程仓库
```

现在访问 `https://你的用户名.github.io`，你的博客就已经上线了！

 第四步：文章的日常写作

发布新文章非常简单：

```bash
hexo new "我的第一篇技术分享"
```

该命令会在 `source/_posts/` 下生成一个 Markdown 文件。使用你喜欢的编辑器（Typora、VS Code 均可）直接写内容，保存后重新执行 `hexo d` 即可发布。

写作小建议：Markdown 语法本身就是一种关键词布局工具——标题层级（H1/H2）和加粗文字（关键字）都能增强文章的可读性和SEO效果。

 互动引导与进阶优化

博客上线只是开始，持续输出才是关键。下面几个方向能帮你提升博客质量：

1. 绑定独立域名（在仓库 Settings → Pages 中配置）
2. 选择 SEO 优化的主题，如 Next、Fluid
3. 提交网站地图至 Google Search Console，加快收录速度

你已经为自己创造了一个干净、自主的创作空间。接下来，你想在博客中加入哪些功能？ 是评论系统、搜索功能，还是流量统计？

欢迎在评论区留下你的想法，或者加入我们的 GitHub 技术社群（关注公众号“全栈开发日记”，回复关键词 `hexo` 获取详细视频教程+主题资源包）。

写作不是目的，成长才是。动手试试吧，你的第一个技术博客马上就能和大家见面了！

相关推荐：

https://github.com/leebradley6/ubrqlg/blob/main/2026%E7%A7%91%E6%8A%80%E5%A4%8D%E7%9B%98%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%9C%B0%E5%9D%80_%E9%98%91%E8%B4%AD%E5%90%95%E6%8D%85%E7%93%9CVIIRE.md

<img src="https://i.postimg.cc/sf6RVMFw/lefu-00017.png" />

相关推荐：

https://github.com/leebradley6/ubrqlg/commit/350a0f70d2fe35534b9de76165019e4a1b514bc8

<img src="https://i.postimg.cc/YSKHJZ5P/lefu-00006.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/blob/main/%E5%A8%B1%E4%B9%90%E4%BA%A7%E4%B8%9A%E5%8A%A8%E6%80%81%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1_%E7%A4%81%E5%A5%84%E7%9A%84%E9%97%AA%E6%B9%9BXRAUI.md

<img src="https://i.postimg.cc/XNH0VrMC/lefu-00016.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/commit/82662a914dc35e89aeaf93b4f474e72d4c1df0c5

<img src="https://i.postimg.cc/XqJSfb5x/lefu-00014.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
