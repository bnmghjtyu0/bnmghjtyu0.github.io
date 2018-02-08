---
title: 資料傳遞：require 與 module
tags: []
categories: node
date: 2018-02-04 16:18:38
---

取得資料 ./app.js
<pre>
var require = require('./data');
</pre>

輸出資料 ./data.js
<pre>
var name = '吉利蛋';
module.exports = {
	name:name,
    level: 20,
    sex: girl
}
</pre>