---
layout: post
title: "An Orientation Factor for Object-Oriented SLAM"
date: 2018-09-19 01:45:45
categories: arXiv_RO
tags: arXiv_RO Knowledge SLAM
author: Natalie Jablonsky, Michael Milford, Niko S&#xfc;nderhauf
mathjax: true
---

* content
{:toc}

##### Abstract
Current approaches to object-oriented SLAM lack the ability to incorporate prior knowledge of the scene geometry, such as the expected global orientation of objects. We overcome this limitation by proposing a geometric factor that constrains the global orientation of objects in the map, depending on the objects' semantics. This new geometric factor is a first example of how semantics can inform and improve geometry in object-oriented SLAM. We implement the geometric factor for the recently proposed QuadricSLAM that represents landmarks as dual quadrics. The factor probabilistically models the quadrics' major axes to be either perpendicular to or aligned with the direction of gravity, depending on their semantic class. Our experiments on simulated and real-world datasets show that using the proposed factors to incorporate prior knowledge improves both the trajectory and landmark quality.

##### Abstract (translated by Google)
当前面向对象SLAM的方法缺乏结合场景几何的先验知识的能力，例如对象的预期全局方向。我们通过提出一个几何因子来克服这个限制，该几何因子根据对象的语义约束地图中对象的全局方向。这个新的几何因子是语义如何在面向对象的SLAM中通知和改进几何的第一个例子。我们实现了最近提出的QuadricSLAM的几何因子，它将地标表示为双重二次曲面。该因子概率地模拟了二次曲线的主轴与重力方向垂直或对齐，这取决于它们的语义类别。我们对模拟和真实世界数据集的实验表明，使用所提出的因素来结合先验知识可以改善轨迹和地标质量。

##### URL
[http://arxiv.org/abs/1809.06977](http://arxiv.org/abs/1809.06977)

##### PDF
[http://arxiv.org/pdf/1809.06977](http://arxiv.org/pdf/1809.06977)

