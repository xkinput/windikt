<div align="center">

<img width="160" src="windikt/icon/windikt.webp" alt="logo">

# windikt · 问道

—— 小小星空的键道码表更新程序

[![release](https://img.shields.io/github/release/xkinput/windikt)](https://github.com/xkinput/windikt/releases)
![license](https://img.shields.io/github/license/xkinput/windikt.svg?logo=github)
![platform](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?logo=windows11&logoColor=white)

「*子踏白云来问道，我垂华发自生辉。*」

</div>

## 功能简介

本程序的主要功能是拉取 <a href=https://keytao.rea.ink><img width="12" src="https://keytao.rea.ink/_next/image?url=%2Flogo.png&w=48&q=75" alt="keytao"> KeyTao 键道词库管理系统</a>的词库，并更新 Windows 版 <a href=https://github.com/xkinput/xxxk><img width="12" src="https://github.githubassets.com/favicons/favicon-dark.png" alt="xxxk"> 小小星空</a>的键道码表的相应内容。

|  分类  | 从 KeyTao 拉取的内容 | 小小星空更新的文件
|  ----  | ----                 | ----
| 单字   | Single               | xkjd6_arg.txt
| 词组   | Phrase               | xkjd6_dict_ci.txt
| 简码   | Supplement & CSS     | xkjd6_dict_jm.txt

## 使用方法

1. 下载程序，建议把 windikt.exe 放到小小星空用户资料目录（可通过命令直通车 `ooml3` 快速打开）下的 tools 目录中。
2. 运行程序。
3. :gear: 设置：填写小小星空的用户资料目录，以及你的 [KeyTao API Key](https://keytao.rea.ink/developer)，然后保存设置。
4. :cloud: 更新。

## 发行渠道

* 方式一：<a href="https://github.com/xkinput/windikt/releases"><img width="12" src="https://github.githubassets.com/favicons/favicon-dark.png" alt="github-logo"> Github Releases</a>
* 方式二：<a href="https://xxxk.ysepan.com"><img width="12" src="https://xxxk.ysepan.com/favicon.ico" alt="ysepan-logo"> 永硕e盘</a>
* 方式三：<a href="http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=VhmkWzdAvvsNwA-2XmDZ_X0jdxiA1xbT&authKey=b9sF6E8RhStcW3PBHiVC6rB29CnjPmgG5YjLpBWdABEbXBzRd1g4eJKWNB7ci1ob&noverify=0&group_code=865189947"><img width="12" src="https://static-res.qq.com/static-res/imqq/qq-logo.png" alt="qq-logo"> 键道QQ群</a>

## 开发指南

本程序使用 Windows 桌面软件快速开发工具 [aardio](https://aardio.com) 开发，并经过其 AI 编程助手优化。仓库中的 windikt 文件夹即为工程目录，下载后可直接用 aardio 打开其中的 default.aprj 查看和修改工程。

## 其他说明

* 本程序功能可用性高度依赖 KeyTao API。
* 因使用本程序导致的任何损失，由使用者自行承担。
* 命名由来：windikt 中的 win 表示程序支持 Windows 系统，dikt 是 dict（词库）和 KeyTao（键道）的结合，表明程序的主要功能。同时，windikt 是其中文名「问道」的谐音。