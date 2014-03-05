---
layout: post
title: "what is a web framework"
tagline: 
description: ""
category: ""
tags: []
---
{% include JB/setup %}

1. Although the server is so complicate, it just send plain HTML
(CSS,JS) to the client. No magic.

2. The HTTP protocol is based on a *request-response* model.

3. The communication is *always* initiated by the client. The server
has no way of initiating a connection to you and send your browser
unsolicited data.

4. HTTP methods and response codes.

5. POST requests send to a specific URL, which is specified in the
form's HTML.

6. Big two problem: routing and templates

	1. How do we map a requested URL to the code that is meant to
handle it?
	2. How do we create the requested HTML dynamically, injecting
calculated values or information retrieved from a database?
