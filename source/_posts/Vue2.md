---
title: 初探 vue2
tags: [vue]
categories: vue
date: 2018-03-04 16:18:38
---

<div class="tip">
```javascript
var vm = new Vue({
  el:'#app',       // 用來掛載 Vue 實體元素
  data:{},         // 綁定資料
  props:{},        // 接收子元件外部資料
  methods:{},      // 定義方法 ＝ function a(el){}
  watch:{},        // 監聽 vue 資料變動
  computed:{},     // 計算屬性
  template:"...",  // 模板
  components:{}    // 定義子元件
  container:{}     // 用 components 接資料，可測試 ui 畫面
})
```
</div>
<h3 id="lifecycle" class="mb-0"><a href="#lifecycle"><i class="fas fa-share-square">#</i></a>生命週期</h3>
<hr class="mt-0 mb-1">
<article>
<p data-height="700" data-theme-id="27337" data-slug-hash="PQVeYv" data-default-tab="js" data-user="bnmghjtyu" data-embed-version="2" data-pen-title="v-LifeCycle 生命週期" class="codepen">See the Pen <a href="https://codepen.io/bnmghjtyu/pen/PQVeYv/">v-LifeCycle 生命週期</a> by RichardLiao 🇹🇼 (<a href="https://codepen.io/bnmghjtyu">@bnmghjtyu</a>) on <a href="https://codepen.io">CodePen</a>.</p>
<script async src="https://static.codepen.io/assets/embed/ei.js"></script>
</article>
