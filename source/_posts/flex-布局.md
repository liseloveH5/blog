---
title: flex 布局
date: 2017-10-26 15:31:20
tags:
- css
---
```css
#dad {
    display: flex;
    justify-content: center;  //水平居中
    align-items: center;      //垂直居中
}
```

#### 父容器：
* justify-content（水平方向）
flex-start：起始端对齐 
flex-end：末尾段对齐  
center：居中对齐   
space-around：子容器沿主轴均匀分布，位于首尾两端的子容器到父容器的距离是子容器间距的一半。   
space-between：子容器沿主轴均匀分布，位于首尾两端的子容器与父容器相切。

* align-items（垂直方向）
flex-start：起始端对齐 
flex-end：末尾段对齐  
center：居中对齐   
baseline：基线对齐，默认是指首行文字对齐
stretch：子容器沿交叉轴方向的尺寸拉伸至与父容器一致。

* flex-wrap（控制换行）

* align-content（多行沿交叉轴对齐）
flex-start：起始端对齐 
flex-end：末尾段对齐  
center：居中对齐   
space-around：子容器沿主轴均匀分布，位于首尾两端的子容器到父容器的距离是子容器间距的一半。   
space-between：子容器沿主轴均匀分布，位于首尾两端的子容器与父容器相切。

#### 子容器
* flex
子容器会按照 flex 定义的尺寸比例自动伸缩，如果取值为 none 则不伸缩。

* align-self
flex-start：起始端对齐 
flex-end：末尾段对齐  
center：居中对齐   
baseline：基线对齐，默认是指首行文字对齐
stretch：子容器沿交叉轴方向的尺寸拉伸至与父容器一致。

* order （设置排列顺序）
默认值为 0，可以为负值，数值越小排列越靠前
