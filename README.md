<img src="https://swift.org/assets/images/swift.svg" alt="Swift logo" height="70" >

# iOS
知识体系，学以致用

## Welcome to ShaoQing's Knowledge system of iOS

- [舆图](#舆图)
- [Learn Project](#learn-project)
- [学习知识点步骤](#学习知识点步骤)
- [Runtime](#runtime)
- [Runtime应用](#runtime应用)
- [利用关联对象（AssociatedObject）给分类添加属性](#利用关联对象（AssociatedObject）给分类添加属性)

## 舆图

* [iOS 开发舆图](https://xiaozhuanlan.com/topic/7365849012?from=timeline&isappinstalled=0)
* [iOS开发——BAT面试题合集](https://www.jianshu.com/p/75e4b9fdcf41)

## Learn Project

* **[Youtube客户端](https://github.com/aslanyanhaik/youtube-iOS)**

## 学习知识点步骤
1. 根据具体应用找到知识点
2. 独立知识点整理成树形结构的知识
3. 独立知识点直接找关联，找时序性

## Runtime

### Runtime应用

#### 利用关联对象（AssociatedObject）给分类添加属性

> 准备知识对象、属性、方法在Runtime是怎么存在的？
背景
在iOS开发中如果我们想给一个对象动态添加属性或者给category添加属性的时候，
都是通过runtime的关联对象去实现，那我们添加的属性到底是如何存取的呢？
是直接添加到了对象自身的内存中了去吗？带着这些疑问让我们看一runtime的源码，解开关联对象的神秘面纱。



#### 遍历类的所有成员变量（修改textfield的占位文字颜色、字典转模型、自动归档解档）
#### 交换方法实现（交换系统的方法）
#### 利用消息转发机制解决方法找不到的异常问题
#### KVC 字典转模型

### Runtime原理
#### 什么是Runtime?
> 准备知识，面向对象 http://www.xuetangx.com/courses/course-v1:NEU+2018051501+sp/about
#### 对象在Runtime是怎么存在的？
#### 属性在Runtime是怎么存在的？
#### 方法在Runtime是怎么存在的？



TODO: 怎么跳转
TODO: 怎么构建文章结构 标题、副标题？？？参考https://github.com/apple/swift
