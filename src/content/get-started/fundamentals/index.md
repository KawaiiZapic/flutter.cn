---
title: 了解基础知识
short-title: 基础知识
description: >
  你已经对Flutter框架有了基本的了解；
  现在让我们开始学习有关Flutter的基础知识。
toc: false
---



<div class="side-by-side">
<div>

## Find your way with Flutter!
## 开始你的Flutter之旅！

If you are new to Flutter, and have already worked
through [your first Flutter codelab][],
this section of the website is for you!  
如果你是第一次使用 Flutter，而且已经完成了你的第一个 [Flutter codelab][]，这个章节就是为你准备的！

The goal here is to guide you through some next
steps of learning Flutter. It's not about teaching
you how to _program_, it's about teaching you
how Flutter works.  
本章节的目标是引导你完成一些学习 Flutter 的进阶步骤。这并非一个教你如何_编程_的教程，本章的主要目的是告诉你 Flutter 如何工作。


</div>
<div class="centered-rows">
  {% render docs/app-figure.md, image:"fwe/dash-search.png", alt:"Dash with magnifying glass", img-style: "max-height: 320px;"%}
</div>
</div>

</div>
<div class="centered-rows">
  {% render docs/app-figure.md, image:"fwe/dash-search.png", alt:"拿着放大镜的 Dash", img-style: "max-height: 320px;"%}
</div>
</div>

:::note
These fundamentals docs are still a work
in progress and we welcome your feedback!
Please consider filling out the survey
listed at the bottom of this page and on the
new subject pages in this section.  
这些基础文档仍然在编写中，我们期待您的反馈！
欢迎你完成在本页面和其他页面底部列出的调查表。
:::

We suggest that you work through the
following subjects in the listed order.  
我们建议你按以下顺序完成各章节：

 1. [Intro to Dart][] _(Optional)_
    As you might know, Flutter uses the [Dart language][].
    If you have experience with other object-oriented
    languages, like Java, C++, or Swift,
    Dart should feel familiar to you.
    As of this writing,
    [Dart is one of the fastest growing languages][dart-lang],
    in part, thanks to Flutter.  
    [初识Dart][Intro to Dart] _(可选)_  
    你可能已经知道 Flutter 使用 [Dart 语言][Dart language].
    如果你有其他面向对象（Object-oriented）的语言使用经验，例如
    Java、C++ 或者 Swift，你可能会觉得 Dart 与他们很相似。
    在本章节编写时,
    [Dart 是增长最快的语言之一][dart-lang],
    这很大部分归功于 Flutter.
 2. [Widget fundamentals][]
    Learn about one of the primary building blocks
    of a Flutter application, widgets.  
    [组件基础][Widget fundamentals]  
    了解组成一个 Flutter 应用的基础积木之一，组件。
 3. [Layout][]
    Flutter is different from other UI frameworks
    in that you create the layout programmatically.
    This allows you to compose widgets,
    Flutter's basic building blocks,
    to realize your own layout vision.
    It also facilitates designing a UI to
    optimize any screen where your app might be used.  
    [布局][Layout]  
    Flutter 与其他 UI 框架不同，它使用编程的方式去构建布局。
    这使你能够编写 Flutter 的基本元素 ———— 组件，以实现你想要的布局。
    这样做还能帮助你设计一套能适应所有将要运行此应用的屏幕的UI。
 4. [State management][]
    Learn how to share state between widgets and notify other parts of your app
    when the state changes.
    See how to implement MVVM in Flutter to manage state effectively
    for small to medium-sized apps.  
    [状态管理][State management]  
    了解如何在组件之间共享状态，并在状态发生变化时通知应用的其他部分。
    学习如何在 Flutter 中实现 MVVM 架构，以在中小型应用中高效管理状态。
 5. [Handling user input][]
    Learn about Flutter's widgets that support
    interactivity, like buttons and text.
    Also, learn how to add interactivity to
    a widget that doesn't already support it.
    [处理用户输入][Handling user input]  
    了解 Flutter 中支持交互的组件，例如按钮和文本。同时，学习如何为一个
    不支持交互的组件处理用户交互。
 6. [Networking and data][]
    Networking is a very large topic,
    so this section focuses on basic networking
    functionality, such as how to retrieve
    or submit data using HTTP,
    how to convert to and from JSON,
    how to use authentication, 
    how to implement asynchronicity, and more.  
    [网络通信与数据][Networking and data]
    网络通信是一个非常复杂的内容，故本章节只注重于基础的网络通信功能，
    例如如何通过 HTTP 接收或发送数据，
    如何将数据与JSON互相转换，如何使用鉴权，如何实现异步通信等等。  
 7. [Local data and caching][]
    Learn about different techniques for caching
    local data.
    [本地数据与缓存][Local data and caching]
    了解本地数据与缓存的不同技术。
    

[Dart language]: {{site.dart-site}}
[dart-lang]: https://twitter.com/MiSvTh/status/1732002450641400276?cxt
[Intro to Dart]: /get-started/fundamentals/dart
[Layout]: /get-started/fundamentals/layout
[State management]: /get-started/fundamentals/state-management
[Handling user input]: /get-started/fundamentals/user-input
[Networking and data]: /get-started/fundamentals/networking
[Local data and caching]: /get-started/fundamentals/local-caching
[Widget fundamentals]: /get-started/fundamentals/widgets
[your first Flutter codelab]: {{site.codelabs}}/codelabs/flutter-codelab-first

## Feedback
## 反馈
As this section of the website is evolving,
we [welcome your feedback][]!
网站的这部分正在不断改进，我们[欢迎你的反馈][welcome your feedback]！


[welcome your feedback]: https://google.qualtrics.com/jfe/form/SV_6A9KxXR7XmMrNsy?page="index"
