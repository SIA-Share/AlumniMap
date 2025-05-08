<!--
 * @Author: likecanyon 
 * @Date: 2025-05-08 09:53:13
 * @LastEditors: likecanyon 1174578375@qq.com
 * @LastEditTime: 2025-05-08 12:54:30
 * @FilePath: \AlumniMap\_directory\README_cn.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->

<!-- README.md with language toggle -->
👉[English Version](https://github.com/SIA-Share/AlumniMap/blob/master/_directory/README.md) 

## 需提供哪些数据？

地图最基本需要你的
- **姓名或昵称** **必选项**
- **入学信息，如21级硕士，16级博士等**，**必选项**
- **地理位置（坐标）**， [这个链接可以帮助你找到你的坐标](https://www.latlong.net/)，**必选项**
- 现工作或学习单位名称 **可选项**。
- 邮箱 **可选项**
- 个人主页 **可选项**
- 我们很希望了解你更多，看到你的头像，但是是否提供全由你自己决定。❤️

## 数据结构

查看示例文件 [`.data.example.yml`](https://github.com/SIA-Share/AlumniMap/blob/master/_directory/.data.example.yml)。除了示例数据，还有许多 **有用注释** 教你如何结构数据。

添加条目时，请在 `_directory/data` 目录下新建一个专属文件夹，最好以自己的名字命名（拼音拼写），方便后期查找，还可以获得一个专属 URL，如 [SIA,Nanta](https://sia-share.github.io/AlumniMap/#siananta)。

在文件夹里添加一个 `data.yml`，根据示例文件填写你的数据。如果你不想使用外部图片链接（如 gravatar.com 或 GitHub 头像），还可以把图片直接放入该文件夹。

```
---
# name (required)
# may be your real name or your nick; not your company name.
# teams: feel free to add multiple entries for each of your members!
name: John Doe # 这里写姓名和入学信息 如， 张三，16级博士

# geo location (required)
# provide your favored level of detail by number of digits (like 50.107811 vs 50.11)
# you may use services like openstreetmap.org to find out your geo location
latitude: 50.11 #这里填写您的纬度
longitude: 8.67 #这里填写您的经度

# bio
# describe yourself, your involvement in the project and the community or whatever is relevant for you.
# should be 300 chars at maximum. no markup or line breaks!
bio: "Hey, I’m John, englishman living in Frankfurt am Main working for YAKAMOTO. I was involved into several REDAXO addons like structure 4.0, the wordpress importer and twitteredaxo. Find me at slack and in the forum." # 这里是您的简介，可选项，可以写您的现工作或学习单位

# image or gravatar
# provide image file from current folder (like 'johndoe.jpg') or gravatar url (generated via https://3v4l.org/OXG7H)
# should be square and about 200-300 px size!
image: johndoe.jpg

# links
# one or more links to your website, your github profile, twitter, facebook et al.
# 4 links, tops! 下面这些行可以添加您的个人主页链接，邮箱等
links:
- https://johndoe.me
- https://github.com/johndoe
- https://twitter.com/johndoe
---

```
如果你还是不确定，可以先看看已有用户的文件夹是怎么做的， 如 [SIA,Nanta的问价夹](https://github.com/SIA-Share/AlumniMap/tree/main/_directory/data/SIANanta)。无须担心，数据系统是安全的，没有什么操作是错误的！

# 如何添加和管理您的条目

该项目住于 GitHub 上，允许每个人自行添加和管理自己的地图条目，非常方便。

你可以通过下列 3 种方式管理条目：

## 1. 提交 pull request

**最推荐方式：** fork 仓库，添加或更新你的条目，提交 pull request，合并后就会显示在地图上了！ 💯

👉 你知道吗，不用 Git 也能添加条目？GitHub 网站提供了全部工具，直接上网操作就可以了，请参考 [通过 GitHub 网站添加条目的方法](https://github.com/SIA-Share/AlumniMap/blob/master/_directory/howto-add-entry-via-github.md)。

## 2. 新建 issue

第二个方案：如果你不熟悉 fork 和 pull request，可以直接新建一个 [GitHub issue](https://github.com/SIA-Share/AlumniMap/issues)，将你的资料(data.yml的内容)写在里面。我们会帮你添加到地图上。

## 3. 联系我们

最不推荐的方式，但是没关系，我们依然很乐意帮助你！如果你没有 GitHub 账号，或者不想在网上揭露资料，那就直接把资料发给我们吧。**邮箱：** 1174578375@qq.com






