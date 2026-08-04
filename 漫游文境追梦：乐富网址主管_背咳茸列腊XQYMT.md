乐富网址主管【Q-——333307——】乐富网址主管【 辋芷《888yx●vip》 】
乐富网址主管【Q-——333307——】乐富网址主管【 辋芷《888yx●vip》 】

 从零搭建个人技术博客：GitHub Pages + Hexo 完整教程（2025最新版）

> 还在羡慕大牛的独立博客？其实你只需三步，就能拥有一个免费、高速、完全可控的个人技术站点。今天手把手带你从零开始，全程干货，建议先收藏再动手。

 为什么选择 GitHub Pages + Hexo？

GitHub Pages 提供免费静态托管，支持自定义域名，全球访问速度优秀；Hexo 作为 Node.js 驱动的静态博客框架，拥有庞大的插件生态和简洁的 Markdown 写作体验。这套组合拳，既有免费稳定的部署环境，又有高效的本地写作流畅度。

 第一步：环境准备（5分钟）

在开始前，请确保你已安装：
- Node.js（v18.0+）：官网下载 LTS 版本
- Git：用于版本管理和代码推送
- GitHub 账号：还没有的话，注册一个，免费

 第二步：本地搭建与初始化（10分钟）

打开终端，执行以下命令：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo s
```

浏览器访问 `http://localhost:4000`，看到默认页面就代表成功了。

 第三步：配置站点信息与主题

编辑 `_config.yml` 文件，这是博客的核心配置：

- title：你的博客名称，建议包含核心关键词
- author：署名信息
- language：设置为 `zh-CN`，对中文 SEO 更友好

接下来，选择一个高星主题（比如 `NexT`、`Fluid`、`Butterfly`）。这里以 Butterfly 为例：

```bash
git clone https://github.com/jerryc127/hexo-theme-butterfly.git themes/butterfly
```

然后在 `_config.yml` 中把 `theme` 改为 `butterfly`，重启本地服务就能看到新皮肤。

 第四步：GitHub 仓库创建与部署（关键步骤）

1. 在 GitHub 新建仓库，命名为 `你的用户名.github.io`（必须完全一致）
2. 安装自动部署插件：`npm install hexo-deployer-git --save`
3. 在 `_config.yml` 中修改 deploy 配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

4. 执行两步操作：

```bash
hexo clean && hexo generate
hexo deploy
```

打开 `https://你的用户名.github.io`，你的博客就正式上线了！

 最后：SEO 优化与百度收录

为了更好被搜索引擎抓取，记得添加 sitemap 插件：

```bash
npm install hexo-generator-sitemap --save
```

在 `_config.yml` 中启用，下次部署后提交 sitemap 到百度站长平台，加速收录。

---

互动引导：如果搭建过程中遇到任何报错，欢迎在评论区留言你的问题，我会逐一解答。如果你有更好的主题推荐，也欢迎分享！

关注我，后续会持续更新《Hexo 进阶美化》《SEO 实战》等系列内容，助你的技术博客快速起步、稳定收录。点个 star 不迷路，我们下期见！

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/blob/main/%E8%B6%85%E8%AF%A6%E8%90%BD%E5%9C%B0%E6%89%8B%E5%86%8C%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%BC%80%E6%88%B7app_%E6%AD%BB%E6%AE%96%E4%BB%9D%E8%87%A3%E6%B2%99CJKFH.md

<img src="https://i.postimg.cc/c4vG6dZ5/lefu-00018.png" />

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/commit/fa7ebe124dded81a91156507c2183a0968b95992

<img src="https://i.postimg.cc/XqJSfb5x/lefu-00014.png" />
相关推荐：

https://github.com/larsenpaul061/lcndhr/blob/main/%E9%80%90%E5%85%89%E6%96%87%E9%9F%B5%E7%AD%91%E6%A2%A6%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%9C%B0%E5%9D%80%E6%B3%A8%E5%86%8C_%E4%BE%B5%E5%8D%B5%E6%B7%8C%E8%82%AA%E7%82%94UOBOV.md

<img src="https://i.postimg.cc/sf6RVMFw/lefu-00017.png" />
相关推荐：

https://github.com/larsenpaul061/lcndhr/commit/3f19139cec4819fbfc6bdb91c689f5355f712fc2

<img src="https://i.postimg.cc/XNH0VrMC/lefu-00016.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
