---
layout: post
title: "linux tips"
tagline: 
description: 
categories: [tools]
tags: [linux, tips, sed]
---
{% include JB/setup %}

### 以16进制方式查看文件

	xxd <file>

也可以用vim查看

	vim -b <file>

转换为16进制

	:%!xxd

最后再转换回来

	:%!xxd -r
### 用 sed 删除文件中特定行

删除第三行：
	
	sed -i '3d' file

删除以 junk 开头的行：

	sed -i '/^junk/d' file

删除包含 junk 的行

	sed -i '/junk/d' file

### sed 替换
找出所有的".py"文件, 然后替换其中某些词:

	find . -iname "*.py" | xargs sed -i 's/something/otherthing/g'

### kill

kill 默认发出 15 SIGTERM 信号，这是可以被进程忽略的，
如果需要强制终止进程，指定发送9 SIGKILL。
	
	kill -9 <pid>
