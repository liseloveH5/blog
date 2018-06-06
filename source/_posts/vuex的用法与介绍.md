---
title: VUEX用法和介绍
date: 2017-10-25 15:06:02
categories: 代码
tags:
    - vue
    - 框架
---
* state 存储的状态， 或者称为存储的变量值
```bash
    console.log(this.$store.state)
```
  
* getter 是根据state派生出来的变量。   类比vue中computed里申明的变量。
```bash 
   console.log(this.$store.getters.done)
```
   
* mutation就是同步更改状态的方法，mutations是操作state的唯一方法，即只有mutations方法能够改变state状态值
```bash
   this.$store.commit('addList', this.content )
```

<!-- more -->

* action主要就是处理异步改变状态的方法
```bash
   this.$store.dispatch('addList', this.content )
```
   
### 所以一共可以分为两组来理解 ：  
1. state,getter  (均为状态， 前者原状态， 后者派生计算后的状态)
2. mutgation,action(均为改变状态的方法或者叫事件，前者同步，后者异步)
