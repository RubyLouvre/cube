---
layout: default
title: button.css
---

## Button

按钮是网站，尤其是重表单页面最常用的元素， Cube 整理了很精致的按钮形式，先引入样式：

{% include cubeUsage.html %}

### 普通按钮

对浮动元素加上 btn 即可：

```html
<button class="btn">Step In</button>
<a class="btn" href="javascript:void(0);">Step In</a>
```

将输出：

<button class="btn">Step In</button>
<a class="btn" href="javascript:void(0);">Step In</a>


### 带 iconfont 的按钮

```html
<button class="btn"><i class="iconfont">&#444;</i>Step In</button>
<a class="btn" href="javascript:void(0);"><i class="iconfont">&#444;</i>Step In</a>
```

将输出：

<button class="btn"><i class="iconfont">&#444;</i>Step In</button>
<a class="btn" href="javascript:void(0);"><i class="iconfont">&#444;</i>Step In</a>

### 按钮组合

```html
<div class="btn-group">
  <button class="btn">Step1</button>
  <button class="btn">Step2</button>
  <button class="btn">Step3</button>
  <button class="btn">Step4</button>
</div>

<div class="btn-group">
  <a class="btn" href="javascript:void(0);">Step1</a>
  <a class="btn" href="javascript:void(0);">Step2</a>
  <a class="btn" href="javascript:void(0);">Step3</a>
  <a class="btn" href="javascript:void(0);">Step4</a>
</div>
```

将输出：

<div class="btn-group">
  <button class="btn">Step1</button>
  <button class="btn">Step2</button>
  <button class="btn">Step3</button>
  <button class="btn">Step4</button>
</div>

<div class="btn-group">
  <a class="btn" href="javascript:void(0);">Step1</a>
  <a class="btn" href="javascript:void(0);">Step2</a>
  <a class="btn" href="javascript:void(0);">Step3</a>
  <a class="btn" href="javascript:void(0);">Step4</a>
</div>

### 各色按钮

```html
<button class="btn btn-red">Step In</button>
<a class="btn btn-red" href="javascript:void(0);">Step In</a>

<button class="btn btn-orange">Step In</button>
<a class="btn btn-orange" href="javascript:void(0);">Step In</a>

<button class="btn btn-blue">Step In</button>
<a class="btn btn-blue" href="javascript:void(0);">Step In</a>
```

将输出：

<button class="btn btn-red">Step In</button>
<a class="btn btn-red" href="javascript:void(0);">Step In</a>

<button class="btn btn-orange">Step In</button>
<a class="btn btn-orange" href="javascript:void(0);">Step In</a>

<button class="btn btn-blue">Step In</button>
<a class="btn btn-blue" href="javascript:void(0);">Step In</a>



### 禁用按钮

```html
<button class="btn btn-blue">Step In</button>
<a class="btn btn-blue" href="javascript:void(0);">Step In</a>
```

将输出：

<button class="btn btn-disabled">Step In</button>
<a class="btn btn-disabled" href="javascript:void(0);">Step In</a>
<div class="ellipsis">我是个蒸不烂煮不熟捶不扁炒不爆响珰珰一粒铜豌豆，恁子弟每谁教你钻入他锄不断斫不下解不开顿不脱慢腾腾千层锦套头。</div>

### 按钮大小

```html
<button class="btn btn-size45"><i class="iconfont">&#444;</i>Step In</button>
<button class="btn btn-xlarge"><i class="iconfont">&#444;</i>Step In</button>

<button class="btn btn-size40"><i class="iconfont">&#444;</i>Step In</button>
<button class="btn btn-large"><i class="iconfont">&#444;</i>Step In</button>

<button class="btn btn-size30"><i class="iconfont">&#444;</i>Step In</button>
<button class="btn btn-medium"><i class="iconfont">&#444;</i>Step In</button>

<button class="btn btn-size28"><i class="iconfont">&#444;</i>Step In</button>
<button class="btn btn-small"><i class="iconfont">&#444;</i>Step In</button>
```
将输出：

<button class="btn btn-size45"><i class="iconfont">&#444;</i>Step In</button>
<button class="btn btn-xlarge"><i class="iconfont">&#444;</i>Step In</button>

<button class="btn btn-size40"><i class="iconfont">&#444;</i>Step In</button>
<button class="btn btn-large"><i class="iconfont">&#444;</i>Step In</button>

<button class="btn btn-size30"><i class="iconfont">&#444;</i>Step In</button>
<button class="btn btn-medium"><i class="iconfont">&#444;</i>Step In</button>

<button class="btn btn-size28"><i class="iconfont">&#444;</i>Step In</button>
<button class="btn btn-small"><i class="iconfont">&#444;</i>Step In</button>
