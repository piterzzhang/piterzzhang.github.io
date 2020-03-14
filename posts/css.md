---
title: "Css"
date: 2020-03-14T21:08:27+08:00
draft: false
---
# css知识总结
## 一、浏览器渲染原理
1、参考谷歌开发团队写的文章
2、浏览器渲染过程：
根据Html构建html树==>根据css构建css树==>将两棵树合并渲染成一颗渲染树==>layout布局==>paint绘制==>compose合成
## 二、css动画的两种做法
1、transition
作用：补充中间帧
语法：transition: 属性名 时长 过滤方式 延迟
可用逗号分隔两个不同属性，可以用all代表所有属性
过渡方式有： linear/ease/ease-in/ease-out/ease-in-out/cubic-bezier/step-start/step-end/steps
2、animation
语法：animation:时长/过渡方式/延迟/次数/方向/填充模式/是否暂停
时长：1s或者1000ms
过渡方式：跟transition取值一样，如linear
次数：3或者2.4或者infinite
方向：reverse/alternate/alternate-reverse
填充模式：none/forwords/backwards/both
是否暂停：paused/running
以上所有属性都有其对应的单独属性!


