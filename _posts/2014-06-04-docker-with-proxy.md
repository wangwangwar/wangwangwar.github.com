---
layout: post
title: "docker with proxy"
tagline: 
description: ""
category: ""
tags: ["docker", "proxy"]
---
{% include JB/setup %}

+ 将本地7070端口映射到代理服务器22端口.

	ssh -f -N -q -D 7070 username@ip-addr

+ 设定环境变量
	
	export http_proxy=http://127.0.0.1:7070

+ 这时候docker pull就是通过代理连接的.
	
	docker pull busybox
