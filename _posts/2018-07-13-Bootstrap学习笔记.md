---
yout:     post
title:      "Bootstrap3学习笔记"
subtitle:   "根据bootstrap3文档做的笔记"
date:       2018-07-13 12:00:00
author:     "张璐"
tags:
    - hotKey
---

1.在同一行的文字有不同样式的时候：

```
<p>我的 <span>路</span> </p>
```

2.ember中的判断语法：(查一下文档)

```
{{#if (eq <参数> '<判断条件>') }}

  {{else}}

{{/if}}
```
3.bootstrap 学习笔记

#### 栅格布局

- 在某一行的分界点清池浮动使下一列换行：
```
<div class="clearfix"></div>
```
- 使某一列向右偏移，实际上是给元素增加了左侧或右侧边距
```
<div class="col-md-2 col-md-offset-2"></div>    //向右偏移2个列的宽度、
```
- 列嵌套：
```
<div class="row">
    <div class="col-md-6">第一列</div>
    <div class="col-md-6">第二列
        <div class="col-md-8">第二列中嵌套的第一列</div>
        <div class="col=md-4">第二列中嵌套的第二列</div>
    </div>
</div>
```
- 列排序
```
<div class="col-md-3 col-md-push-3">向右移动3列的宽度</div> 
//如果此列右面本来有列，会覆盖这一列
<div class="col-md-3 col-md-pull-3">向左移动3列的宽度</div>
//如果此列左面本来有列，此列会覆盖之前列
```

#### 文本排版

- class设置为.h1~.h6，相当于<h1>~<h6>。除此之外，.small可作为副标题

```
<div class="contain">
    <div class="h1">wode<span class="small">路</span></div>
</div>

```
- .lead 可以让段落突出显示
```
<p class="lead">...</p>
```
- 对齐
- 改变大小写
- 斜体
- 着重加粗
- 标记颜色
- 删除文本
- 插入文本
- 带下划线文本
- 改变大小写
- 缩略语
- 地址
- 引用
- 有序列表
- 无需列表
- 无样式列表
- 内联列表
- 描述
- 


#### 代码排版

- 内联代码
- 用户输入
- 代码块
- 变量
- 程序输出




#### 表格排版

- .table 基本的表格样式
- 将table包裹在.table-reponsive中，表格会有响应式
- .table-striped 条纹状表格
- .table-bordered 带边框的表格
- .table-condensed 紧缩表格（每行高度）
- .table-hover 鼠标悬停样式
- 设置单元格不同状态（颜色）：共有5种状态

















