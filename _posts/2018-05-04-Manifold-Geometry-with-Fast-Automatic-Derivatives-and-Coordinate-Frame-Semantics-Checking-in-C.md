---
layout: post
title: "Manifold Geometry with Fast Automatic Derivatives and Coordinate Frame Semantics Checking in C++"
date: 2018-05-04 14:55:57
categories: arXiv_RO
tags: arXiv_RO Face
author: Leonid Koppel, Steven L. Waslander
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision and robotics problems often require representation and estimation of poses on the SE(3) manifold. Developers of algorithms that must run in real time face several time-consuming programming tasks, including deriving and computing analytic derivatives and avoiding mathematical errors when handling poses in multiple coordinate frames. To support rapid and error-free development, we present wave_geometry, a C++ manifold geometry library with two key contributions: expression template-based automatic differentiation and compile-time enforcement of coordinate frame semantics. We contrast the library with existing open source packages and show that it can evaluate Jacobians in forward and reverse mode with little to no runtime overhead compared to hand-coded derivatives. The library is available at https://github.com/wavelab/wave_geometry .

##### Abstract (translated by Google)
计算机视觉和机器人问题通常需要SE（3）流形上姿态的表示和估计。必须实时运行的算法开发人员需要面对几个耗时的编程任务，包括派生和计算分析导数，以及在处理多个坐标系中的姿态时避免数学错误。为了支持快速和无差错的开发，我们提出了wave_geometry，一个C ++流形几何库，它有两个关键贡献：基于表达式模板的自动差异和坐标帧语义的编译时执行。我们将该库与现有的开源软件包进行对比，并表明它可以在正向和反向模式下评估雅可比行为，与手动编码衍生产品相比，几乎没有运行时开销。该库可在https://github.com/wavelab/wave_geometry上找到。

##### URL
[http://arxiv.org/abs/1805.01810](http://arxiv.org/abs/1805.01810)

##### PDF
[http://arxiv.org/pdf/1805.01810](http://arxiv.org/pdf/1805.01810)

