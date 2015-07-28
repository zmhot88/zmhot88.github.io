---
layout: post
title:  "搭建github pages博客"
date:   2015-07-28 13:59:53
author: ross
---

想做一个私人博客，整理一下所学的内容，搞了半天，才算终于可以用起来了。

1. 生成jekyll项目

	jekyll new mercenary

2. 预览

	jekyll server

3. 上传github page


	git init .

	git remote add https://github.io/yourname/yourname.github.io

	git branch --set-upstream master origin/master

	git push


4. 可以打开yourename.github.io了，内容应该是默认生成的。

5. 下一步写blog。

说明：有的步骤被我省了，这是我第二次玩github pages。有些环境是已经完成了，包括安装等内容，具体还是参考官网。