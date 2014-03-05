---
layout: post
title: "MongoDB Tips"
tagline: 
description: ""
category: ""
tags: []
---
{% include JB/setup %}

1. About data model design [1][http://docs.mongodb.org/manual/core/data-model-design/]

There are two data model: embedded data models and normalized data
models. We compare them in performance, space, model relationship,
atomicity.

	* Performance: Embedded data models (E) is faster than Normalized
	  data models (N) because no matter reading, updating, the former 
	  just need 1 ops. N need 2 or more.
	
	* Space: E need more disk/memory space than N.
	
	* Model relationship: E applies 1-to-1 or 1-to-many relationships.
	  while N applies many-to-many relationships.

	* Atomicity: Because updating one document is atomic, E need just 1
	  op to update its data, so E ensure its atomicity. While N need more
	  than 1 op to update data in separate documents, we can't ensure
	  more 2 ops' atomicity.
