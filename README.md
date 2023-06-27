# IPDC 组织网站

智能感知与决策研究中心，IPDC的组织网站，使用Hugo框架，使用wowchemy主题。为便于组内成员使用，特写以下简单的使用说明。

对网站内容进行编辑之后，提交`git commit`并`push`到remote的仓库中，GitHub Action会自动重新生成网页。因此专注内容即可。

## 个人资料编辑

1. 若个人资料不存在，则复制`example`文件夹到目录`content/authors/`下，重命名为自己的名字，如`刘子锋`。
2. 变更该目录下的`avatar.jpg`文件即可更换头像
3. 编辑`index.md`中的内容即可改变个人页面中的内容，具体效果看改文件中的注释即可。

## 新闻编辑

1. 新建一篇新闻，复制`content/post/example`文件夹到目录`content/post/`下，重命名为自己的新闻标题，如`2021-09-01-新闻标题`。
2. 编辑该目录下的`index.md`写新闻即可。

## 文章/出版物编辑

1. 新建一篇文章，复制`content/publication/example`文件夹到目录`content/publication/`下，重命名为自己的文章标题，如`2021-09-01-文章标题`。
2. 编辑该目录下的`index.md`将文章写入即可。

## 本地编译及渲染

hugo是基于go的，因此，若想要在本地编译及渲染，需要先安装go环境。安装方法请自行百度。

其次，需要在本地安装hugo，windows下的安装方法很简单，打开powershell，输入命令：

```powershell

winget install Hugo.Hugo.Extended
```

即可，详见<https://gohugo.io/installation/windows/>。安装完之后最好重启下电脑，不然环境变量可能不生效。

配置好环境后，将本仓库clone到本地，在目录下运行命令：

```powershell
hugo
```

即可对网页进行渲染。运行命令：

```powershell
hugo server
```

即可在本地1313端口生成预览。

---
***以下为原主题使用文档***

# [Hugo Research Group Theme](https://github.com/wowchemy/starter-hugo-research-group)

[![Screenshot](./preview.png)](https://wowchemy.com/hugo-themes/)

The **Research Group Template** empowers your research group to easily create a beautiful website with a stunning homepage, news, academic publications, events, team profiles, and a contact form.

️**Trusted by 250,000+ researchers, educators, and students.** Highly customizable via the integrated **no-code, widget-based Wowchemy page builder**, making every site truly personalized ⭐⭐⭐⭐⭐

[![Get Started](https://img.shields.io/badge/-Get%20started-ff4655?style=for-the-badge)](https://wowchemy.com/hugo-themes/)
[![Discord](https://img.shields.io/discord/722225264733716590?style=for-the-badge)](https://discord.com/channels/722225264733716590/742892432458252370/742895548159492138)  
[![Twitter Follow](https://img.shields.io/twitter/follow/wowchemy?label=Follow%20on%20Twitter)](https://twitter.com/wowchemy)

Easily write technical content with plain text Markdown, LaTeX math, diagrams, RMarkdown, or Jupyter, and import publications from BibTeX.

[Check out the latest demo](https://research-group.netlify.app/) of what you'll get in less than 60 seconds, or [view the showcase](https://wowchemy.com/creators/).

The integrated [**Wowchemy**](https://wowchemy.com) website builder and CMS makes it easy to create a beautiful website for free. Edit your site in the CMS (or your favorite editor), generate it with [Hugo](https://github.com/gohugoio/hugo), and deploy with GitHub or Netlify. Customize anything on your site with widgets, light/dark themes, and language packs.

- 👉 [**Get Started**](https://wowchemy.com/hugo-themes/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy research community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- ⬇️ **Automatically import citations from BibTeX** with the [Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli)
- 🐦 Share your new site with the community: [@wowchemy](https://twitter.com/wowchemy) [@GeorgeCushen](https://twitter.com/GeorgeCushen) [#MadeWithWowchemy](https://twitter.com/search?q=%23MadeWithWowchemy&src=typed_query)
- 🗳 [Take the survey and help us improve #OpenSource](https://forms.gle/NioD9VhUg7PNmdCAA)
- 🚀 [Contribute improvements](https://github.com/wowchemy/wowchemy-hugo-themes/blob/main/CONTRIBUTING.md) or [suggest improvements](https://github.com/wowchemy/wowchemy-hugo-themes/issues)
- ⬆️ **Updating?** View the [Update Guide](https://wowchemy.com/docs/hugo-tutorials/update/) and [Release Notes](https://github.com/wowchemy/wowchemy-hugo-themes/releases)

## We ask you, humbly, to support this open source movement

Today we ask you to defend the open source independence of the Wowchemy website builder and themes 🐧

We're an open source movement that depends on your support to stay online and thriving, but 99.9% of our creators don't give; they simply look the other way.

### [❤️ Click here to become a GitHub Sponsor, unlocking awesome perks such as _exclusive academic templates and widgets_](https://github.com/sponsors/gcushen)

## Demo credits

Please replace the demo images with your own.

- [Female scientist](https://unsplash.com/photos/uVnRa6mOLOM)
- [2 Coders](https://unsplash.com/photos/kwzWjTnDPLk)
- [Cafe](https://unsplash.com/photos/RnDGGnMEOao)
- Blog posts
  - https://unsplash.com/photos/AndE50aaHn4
  - https://unsplash.com/photos/OYzbqk2y26c
- Avatars
  - https://unsplash.com/photos/5yENNRbbat4
  - https://unsplash.com/photos/WNoLnJo7tS8
