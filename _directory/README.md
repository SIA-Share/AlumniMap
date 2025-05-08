<!-- README.md with language toggle -->

<style>
  .lang-en, .lang-zh { display: none; }
  .lang-toggle button { margin-left: 10px; cursor: pointer; }
</style>

<div class="lang-toggle" align="right">
  <strong>Language:</strong>
  <button onclick="showLang('en')">English</button>
  <button onclick="showLang('zh')">中文</button>
</div>

<div class="lang-content">
  <div class="lang-en">

# How to add and manage your entry

The project is hosted at GitHub, which allows for everyone to add and manage their map entries by themselves! This is pretty cool.

Learn about 3 ways how to manage your entry:

## 1. Send a pull request

**This is the best option:** fork the repo, add or update your entry and send a pull request. Once merged, it will be live on the map! 💯

👉 Did you know you don’t need to work with Git to add your entry? GitHub provides all the tools on its website and you can start using them immediately, see [Howto: add your entry via GitHub website](https://github.com/SIA-Share/AlumniMap/blob/master/_directory/howto-add-entry-via-github.md).

## 2. Open an issue

Second best option: if you’re not familiar with forking and pull requests, just open a [GitHub issue](https://github.com/SIA-Share/AlumniMap/issues) with your data inside. We’ll take care and add your data to the map.

## 3. Contact us

Worst option, but no worries, we’d love to help! If you don’t have a GitHub account at all or you do not feel comfortable to open an issue containing your data, just send it to us. **Email:** _friendsof [at] redaxo.org_

Btw: what data? 👇

## Data structure

Have a look at the example file [`.data.example.yml`](https://github.com/SIA-Share/AlumniMap/blob/master/_directory/.data.example.yml). Aside from dummy data it contains a lot of **helpful comments** on how to structure your data!

For your entry, add a new folder inside of `_directory/data`. It is best to name the folder after your name so that you can find it later and get a cool URL for it! (just like [Jan](https://friendsofredaxo.github.io/community/#dergel) has one). Add a `data.yml` which contains your data according to the example file. Also add an image to the folder, if you don’t want to refer to an external image (like gravatar.com or your GitHub profile picture).  

If you're not sure, take a look at existing user folders to see how to do it. And no worries, the data is always safe — you can't break anything!

## What data should I provide?

The map requires your name or nickname and your geo position. Everything else is optional. Of course we'd all love to read more about you and maybe see your picture! But it’s completely up to you whether to provide it or not!

❤️

  </div>

  <div class="lang-zh">

# 如何添加和管理您的条目

该项目托管在 GitHub 上，允许每个人自行添加和管理自己的地图条目，非常方便。

您可以通过以下三种方式管理您的条目：

## 1. 提交 pull request

**最推荐方式：** fork 仓库，添加或更新您的条目并提交 pull request，合并后即可显示在地图上！ 💯

👉 你知道吗，不需要安装 Git 工具也可以添加条目？GitHub 提供了在线操作界面，立即上手，详见：[如何通过 GitHub 网站添加条目](https://github.com/SIA-Share/AlumniMap/blob/master/_directory/howto-add-entry-via-github.md)。

## 2. 新建 issue

第二选择：如果您不熟悉 fork 和 pull request，可以直接创建一个 [GitHub issue](https://github.com/SIA-Share/AlumniMap/issues)，将您的信息填写在其中，我们会帮您添加到地图中。

## 3. 联系我们

最不推荐但也可行的方式，如果您没有 GitHub 账号，或者不方便在线提交信息，可以直接发邮件给我们。**邮箱：** _friendsof [at] redaxo.org_

顺便说一下：需要提供哪些信息？👇

## 数据结构

请查看示例文件 [`.data.example.yml`](https://github.com/SIA-Share/AlumniMap/blob/master/_directory/.data.example.yml)。除了示例数据，还包含许多**有用的注释**帮助您组织数据结构。

添加条目时，请在 `_directory/data` 目录下新建一个专属文件夹，建议使用您的名字命名，以便之后查找，同时也可获得一个专属的 URL 地址（就像 [Jan](https://friendsofredaxo.github.io/community/#dergel) 的那样）。

在文件夹内添加一个 `data.yml` 文件，按示例文件格式填写信息。如不想使用外部头像链接（如 gravatar 或 GitHub 头像），也可以将图片直接添加到该文件夹中。

不确定怎么做？可以查看其他用户的文件夹作为参考。放心，数据是安全的，操作不会出错！

## 我需要提供哪些信息？

地图最基本需要您的姓名或昵称和地理位置，其余信息完全可选。我们当然很希望了解更多关于您的故事，也欢迎上传头像！但是否填写完全由您决定。

❤️

  </div>
</div>

<script>
  function showLang(lang) {
    document.querySelector('.lang-en').style.display = (lang === 'en') ? 'block' : 'none';
    document.querySelector('.lang-zh').style.display = (lang === 'zh') ? 'block' : 'none';
  }
  // Show English by default
  showLang('en');
</script>
