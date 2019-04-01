title: Epoxy：构建复杂页面的框架（二）
date: 2018-01-04 17:41:08
categories:
- lwp
tags:
- Android
- Epoxy

---

本文是 Epoxy 系列的第二篇，主要介绍 Epoxy Model 的使用方法。

<!--more-->

Epoxy 使用 `EpoxyModel` 对象来决定显示哪些视图以及如何将数据绑定到它们，这与流行的 ViewModel 模式相似。模型还允许您控制视图的其他方面，如网格间隔大小，id 和保存的状态。

## 创建 Model

Epoxy 有多种方法创建 Model，最终在构建后都会生成以 `_` 为后缀的类，也就是是我们在 Controller 中实际使用的类。

* [Annotate custom views](#annotate_custom_views)
* [Use Android databinding](#use_android_databinding)
* [Use the view holder pattern](#use_view_holder)

## Model 的 ID



## <span id="annotate_custom_views">通过自定义控件创建 Model</span>


## <span id="use_android_databinding">通过 DataBinding 创建 Model</span>


## <span id="use_view_holder">通过 ViewHolder 控件创建 Model</span>


## 参考资料

* [Epoxy Models - Epoxy Wiki](https://github.com/airbnb/epoxy/wiki/Epoxy-Models)

