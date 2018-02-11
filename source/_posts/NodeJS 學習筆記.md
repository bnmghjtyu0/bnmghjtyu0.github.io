---
title: NodeJS學習筆記
tags: []
categories: node
date: 2018-02-04 16:18:38
---

<div class="tip">
<ol style="padding-left:20px;">
<li><a href="#Node01">資料傳遞：require 與 module</a></li>
</ol>
</div>

<ul id="Node01">
<li>
<h4>資料傳遞：require 與 module</h4>
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
</li>
</ul>


