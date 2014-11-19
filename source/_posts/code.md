---
layout: post
title: Code
date: 2014-01-08 10:58:17
tags:
- dolor
description: Code Test. 测试代码显示。
---

Normal code block:

``` js
var http = require('http');
http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello World\n');
}).listen(1337, '127.0.0.1');
console.log('Server running at http://127.0.0.1:1337/');
```

Code block:

{% codeblock Javascript Array Syntax lang:js http://j.mp/pPUUmW MDN Documentation %}
var arr1 = new Array(arrayLength);
var arr2 = new Array(element0, element1, ..., elementN);
{% endcodeblock %}

<!-- more -->

jsFiddle:

{% jsfiddle ccWP7 %}