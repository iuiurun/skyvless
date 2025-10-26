---
title: 我的博客记录
published: 2025-10-20T06:40:00
description: "更新一些常用的"
image: ""
tags: ["标签"]
category: 博客
draft: false
---
# 域名

spaceship购买
https://www.spaceship.com/zh/domain-transfer-submit/

# 解析

华为云国际版https://www.huaweicloud.com/intl/zh-cn/
无需实名认证，不需要手机号码。邮箱即可！

# 更新文章

src\content\posts
新建文件夹（10）——新建index.md
图片在文件夹下

## 文章内容

```
---
title: 标题
published: 2025-10-20
description: "描述"
image: "./cover.jpeg"
tags: ["标签"]
category: 分类
draft: false
---
```

# 同步文章

电脑是GitHub Desktop
https://desktop.github.com/download/
简单、方便

# 本地预览的话

clone 仓库文件夹

在终端打开
命令

```
pnpm install
```

```
pnpm dev
```

浏览器打开：http://localhost:4321/

# Fuwari的基本信息修改

title：你的博客主标题

subtitle：你的博客副标题。可选，在首页会显示为“主标题 - 副标题”

lang：博客显示语言。注释已经列出了一些常用的值，如：en, zh_CN, zh_TW, ja, ko

themeColor：hue值则是你的博客主题色，可以在你的博客右上角的画板图标确定喜欢的颜色再填写

banner：src：即banner图片，支持http/https URL

favicon：src：即网站图标，支持http/https URL

links：即友情链接，这些链接在导航栏上

avatar：即你的头像

name：即你的名字

bio：即个性签名，会显示在头像和名字下面

NavBarConfig 为导航栏设置的超链接。ProfileConfig 为你的用户的超链接
icon：你需要前往icones.js去搜索你想要的图标，比如QQ，则填写 fa6-brands:qq ，如图。Fuwari默认支持这几种类型：fa6-brands, fa6-regular, fa6-solid, material-symbols。可以在 astro.config.mjs 中搜索关键字进行配置
https://icones.js.org/

# 编辑器

老老实实用Visual Studio Code  加上Paste Image插件

![](2025-10-20-05-18-50.png)

1. 打开插件设置界面
   在 VS Code 左侧点击扩展（或快捷键 Ctrl+Shift+X），找到已安装的 Paste Image 插件。
   点击插件名字，进入详情页后，点击右上角的设置齿轮，选择扩展设置。
2. 通过设置界面配置
   搜索并修改如下两个设置：
   ① Paste Image: Path
   搜索“Paste Image: Path”。
   在输入框里填写：
   代码
   ``${currentFileDir}``
   这表示图片会保存在当前 markdown 文件的同级目录。

② Paste Image: Insert Pattern
搜索“Paste Image: Insert Pattern”。
在输入框里填写：
代码
``![](${imageFilePath})``
这样插入的就是标准的 Markdown 相对路径格式。

粘贴图片（Ctrl+Alt+V），会发现图片就在 md 同级目录,并且插入的就是相对路径的 Markdown 语法。

一般写文章是在本地仓库 pnpm dev 浏览器实时预览

在用Visual Studio Code写

# 部署

我是部署在vercel

https://vercel.com/

2025/10/26

部署更换为netlify

## 解析优选：

解析优选 用的是WeTest.Vip
*.vercel.182682.xyz

2025/10/26

更换https://www.byoip.top/优选

*.netlify.byoip.top
![](2025-10-26-08-20-59.png)

## 解析查询：

https://uutool.cn/nslookup/

![img](2025-10-26-08-19-56.png)

# 评论

Github的giscus

添加方法：https://thw.lol/posts/fuwari-giscus/

# 友链

是我参照https://blog.kimbleex.top/posts/2025-10-09-fuwari-friends/

然后用GTP 模仿https://pcb.im/friends/

修改而来的。
![](2025-10-26-08-21-39.png)

# 其他

以后在更新吧~
