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
