---
title: 安装Chrome 102+版本并隔离与已安装的Chrome 82版本
date: 2026-07-17 15:44:55
updated: 2026-07-17 15:44:55
tags: ["chrome"]
categories: ["chrome"]
keywords: "chrome"
description: "Install google chrome 102+ version and isolate with chrome 82 version"
top_img: /img/top.jpg
comments: true
cover: /img/top.jpg
toc: true
toc_number: true
toc_style_simple: true
copyright: true
copyright_author: MaoMao
copyright_author_href: https://github.com/maomao-paradox/
copyright_url: https://maomao-paradox.github.io/
copyright_info: "hello world"
mathjax: false
katex: false
aplayer: false
highlight_shrink: false
aside: false
abcjs: false
noticeOutdate: false
---

## 安装Chrome 102+版本并隔离与已安装的Chrome 82版本

---

### 步骤1：下载Chrome 102+浏览器和7zip安装包

### 步骤2：安装和解压

首先安装7zip，安装之后，找到下载的chrome安装包文件使用7zip进行解压（可能要连续解压两层）

解压后的位置尽量隐蔽，不要被轻易删除

![解压](/img/install-chrome-1.jpg)

### 步骤3：创建用户数据文件夹

在“Chrome-bin”文件夹中新建一个空文件夹，命名为“user-data”，复制user-data文件夹的全路径

![user-data](/img/install-chrome-2.jpg)

### 步骤4：创建快捷方式

找到“Chrome-bin”文件夹中的“chrome.exe”文件，右键点击该文件，选择“创建快捷方式”，右键点击快捷方式，选择“属性”，在“目标”一栏的内容后面添加以下路径：

--user-data-dir=”D:\Chrome102\APP\Chrome-bin\user-data”（上面复制的user-data文件夹的全路径）

![快捷方式](/img/install-chrome-3.jpg)

### 步骤5：确认浏览器版本号

双击桌面的快捷方式打开浏览器，在设置中确认浏览器版本号是否为102+版本

![版本号](/img/install-chrome-4.jpg)

确认无误后，访问院内信息系统，创建桌面快捷方式

![信息系统快捷方式](/img/install-chrome-5.jpg)

![删除快捷方式](/img/install-chrome-6.jpg)

### 步骤6：删除旧快捷方式并保留新快捷方式

如果【步骤4】创建的chrome快捷方式在桌面，就删除掉，桌面只保留刚创建的信息系统的快捷方式即可。

![删除快捷方式](/img/install-chrome-7.jpg)

---

通过以上步骤，就可以在Windows 7电脑上安装Chrome 102版本，并且与已安装的Chrome 82版本隔离。每个版本的Chrome使用各自独立的用户数据文件夹，互不干扰，可分别进行使用和管理。
