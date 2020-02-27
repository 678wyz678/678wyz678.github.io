---
layout: post
title: 'Note'
date: 2020-02-27
author: Jo
cover: 'http://on2171g4d.bkt.clouddn.com/jekyll-theme-h2o-postcover.jpg'
categories: 随笔
tags: vueJS
---

### 订阅-发布模式和观察者模式

## 前言
发布订阅者模式与观察者模式是很相似的，之前的好多网站、博客上也把它们画上等号，其实不太一样。


## 订阅-发布模式
￼![subscribe_code2](https://github.com/678wyz678/678wyz678.github.io/blob/master/assets/img/2020-02-27/subscribe_code1.jpg)


![subscribe_code2](https://github.com/678wyz678/678wyz678.github.io/blob/master/assets/img/2020-02-27/subscribe_code2.jpg)



## 订阅-发布模式和观察者模式的区别
* 在观察者模式中，观察者是知道Subject的，Subject一直保持对观察者进行记录。然而，在发布订阅模式中，发布者和订阅者不知道对方的存在。它们只有通过调度中心进行通信。
* 在发布订阅模式中，组件是松散耦合的，正好和观察者模式相反。
* 观察者模式大多数时候是同步的，比如当事件触发，Subject就会去调用观察者的方法。而发布-订阅模式大多数时候是异步的（使用消息队列）


￼![observer_image](https://github.com/678wyz678/678wyz678.github.io/blob/master/assets/img/2020-02-27/observer.jpg)
观察者模式图

￼![publish_subscribe](https://github.com/678wyz678/678wyz678.github.io/blob/master/assets/img/2020-02-27/publish_subscribe.jpg)
发布-订阅模式
发布者和订阅者没有直接关系，是通过数据中心反应的
￼
## 最后说一句，这两个模式尽管很相似但是却工作机制不一样，这是我今天所学到的东西，希望每天都可以学到更多。加油！