---
layout: post
title: "python tips"
date: 2013-01-02 21:28
comments: true
categories: ["python"]
---

##### 创建字典的一些方法

{% highlight python linenos %}
{'name': 'mel', 'age': 45}
D = {}
D['name'] = 'mel'
D['age'] = 45

dict.fromkeys(['name', 'age'])

dict(name='mel', age=45)

dict([('name', 'mel'), ('age', 45)])

dict(zip(['name', 'age'], ['mel', 45]))
{% endhighlight %}


##### zip for creating a dict

{% highlight python linenos %}
keys = ['super', 'star', 'suicide']
vals = [1, 3, 5]
D = {}
for (k, v) in zip(keys, vals): D[k] = v
{% endhighlight %}


##### 列表解析（list comprehensions） 1

{% highlight python linenos %}
lines = [line.rstrip() for line in open('file') if line[0] == 'p']
{% endhighlight %}


##### 列表解析 2

{% highlight python linenos %}
[x + y for x in 'abc' for y in 'lmn']
{% endhighlight %}


##### PSL 之 collections.defaultdict [[d]][1]

我们知道标准的 dict 类型，当访问不存在的 key 时会抛出 KeyError 异常。
这可以用 try ... catch 来解决，但是有个更简洁的方法，即使用 
collections.defaultdict。官方文档定义为：
>   dict subclass that calls a factory function to supply missing
	values

即这是 dict 类的子类，可以调用一个工厂函数来支持“返回”缺失值。

例如：
{% highlight python linenos %}
D = collections.defaultdict(lambda : 0)
D['a'] = 2
D['a'] # 返回 2
D['not exist'] # 返回 0
{% endhighlight %}


##### 调用函数时使用星号 \*, \** [[star]][2]

\* 的作用其实就是把序列 args 中的每个元素，当作位置参数传进去。如果 args 等于 (1,2,3) ，那么这个代码就等价于 
{% highlight python linenos %}
test(*args)
test(1, 2, 3)
{% endhighlight %}

\*\* 的作用则是把字典 kwargs 变成关键字参数传递。如果 kwargs 等于 {'a':1,'b':2,'c':3} ，那这个代码就等价于
{% highlight python linenos %}
test(*kwargs)
test(a=1,b=2,c=3)
{% endhighlight %}


##### enumerate常用法

{% highlight python linenos %}
with open(filename) as f: 
    for line,row in enumerate(csv.DictReader(f)): 
        if line >= 6: 
            # process the CSV 
{% endhighlight %}


##### slice
[总结][3]


##### map and filter in python3

在python2中，map和filter返回的是list，而在python3中，返回的是
generator，如果map的func参数中有打印语句什么的，将不会打印。
将generator转换为list，让lazy变成greedy，就会打印出来。

{% highlight python linenos %}
def show(item):
    print(item)

# nothing
map(show, range(10))

# print 0 to 9
list(map(show, range(10)))
{% endhighlight %}


[1]: http://docs.python.org/2/library/collections.html#collections.defaultdict
[2]: http://hi.baidu.com/jiyeqian/item/a1ec88c42021ad7189ad9eda
[3]: http://shmilyaw-hotmail-com.iteye.com/blog/1782733
