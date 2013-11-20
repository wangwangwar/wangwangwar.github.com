---
layout: post
title: "python tips"
date: 2013-01-02 21:28
comments: true
categories: ["python"]
---

+ 创建字典的一些方法

		{'name': 'mel', 'age': 45}
	
		D = {}
		D['name'] = 'mel'
		D['age'] = 45
		
		dict.fromkeys(['name', 'age'])

		dict(name='mel', age=45)
	
		dict([('name', 'mel'), ('age', 45)])
	
		dict(zip(['name', 'age'], ['mel', 45]))

+ zip for creating a dict

		keys = ['super', 'star', 'suicide']
		vals = [1, 3, 5]
		D = {}
		for (k, v) in zip(keys, vals): D[k] = v

+ 列表解析（list comprehensions） 1

		lines = [line.rstrip() for line in open('file') if line[0] == 'p']

+ 列表解析 2

		[x + y for x in 'abc' for y in 'lmn']

+ PSL 之 collections.defaultdict [[d]][1]

	我们知道标准的 dict 类型，当访问不存在的 key 时会抛出 KeyError 异常。
	这可以用 try ... catch 来解决，但是有个更简洁的方法，即使用 
	collections.defaultdict。官方文档定义为：

		dict subclass that calls a factory function to supply missing
		values
		
	即这是 dict 类的子类，可以调用一个工厂函数来支持“返回”缺失值。
	
	例如：

		D = collections.defaultdict(lambda : 0)
		D['a'] = 2
		D['a'] # 返回 2
		D['not exist'] # 返回 0

[1]: http://docs.python.org/2/library/collections.html#collections.defaultdict
