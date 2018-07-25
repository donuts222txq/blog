---
title: hexo+github搭建个人博客教程
date: 2018-07-24 11:35:13
tags:
---
# hexo
### 特点：快速、简洁且高效的博客框架
### 环境：基于node（v8.11.3）
1.环境及检测：
	win+r输入cmd回车 
	cmd窗口输入node -v回车
	如果提示node不是内部或外部命令
	则需要安装node
	②安装node环境
	https://nodejs.org/zh-cn/ v8.11.3
	双击下载得到的mis文件，全程next
2.安装git（版本控制器）
https://git-scm.com/download/win
QQ群文件也有
3.安装hexo
cmd命令：
```
npm install hexo-cli -g
```
npm：基于node的包管理器，类似于iOS的APP store
    通过npm可以下载安装需要的插件或者框架
install：安装、导入
-g：表示全局安装（在任何目录都可以使用）
4.初始化一个博客项目
①hexo init 项目名
②切换到项目目录
	cd 项目名
③安装项目依赖包
npm install 
