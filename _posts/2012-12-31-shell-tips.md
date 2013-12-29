---
layout: post
title: "shell tips"
date: 2012-12-31 21:05
comments: true
categories: ["shell"]
tags: ["shell"]
---


+ for 的几种写法

{% highlight sh linenos %}
# C style
for ((i=1;i<=10;i++));
	do echo i;
done
# Use `seq`
for i in $(seq 10);
	do echo i;
done

# File
for i in /home/*.sh; do

# num
for i in {1..10}; do
{% endhighlight %}


+ 截取字符串

{% highlight sh linenos %}
v=hello
a=${v#v=}
echo a	# hello
{% endhighlight %}
	

+ tee 的用法 [1][1]

{% highlight sh linenos %}
# 会提示没有权限，因为 `>` 也是一个命令，`sudo`只能给一个命令权限
sudo echo 1 > /root/some/thing
# 改用tee
echo 1 | sudo tee /root/some/thing
{% endhighlight %}


---
[1]: http://blog.c1gstudio.com/archives/1255
