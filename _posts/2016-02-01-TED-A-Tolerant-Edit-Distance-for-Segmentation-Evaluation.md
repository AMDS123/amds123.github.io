---
layout: post
title: "TED: A Tolerant Edit Distance for Segmentation Evaluation"
date: 2016-02-01 14:26:10
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Jan Funke, Francesc Moreno-Noguer, Albert Cardona, Matthew Cook
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a novel error measure to compare a segmentation against ground truth. This measure, which we call Tolerant Edit Distance (TED), is motivated by two observations: (1) Some errors, like small boundary shifts, are tolerable in practice. Which errors are tolerable is application dependent and should be a parameter of the measure. (2) Non-tolerable errors have to be corrected manually. The time needed to do so should be reflected by the error measure. Using integer linear programming, the TED finds the minimal weighted sum of split and merge errors exceeding a given tolerance criterion, and thus provides a time-to-fix estimate. In contrast to commonly used measures like Rand index or variation of information, the TED (1) does not count small, but tolerable, differences, (2) provides intuitive numbers, (3) gives a time-to-fix estimate, and (4) can localize and classify the type of errors. By supporting both isotropic and anisotropic volumes and having a flexible tolerance criterion, the TED can be adapted to different requirements. On example segmentations for 3D neuron segmentation, we demonstrate that the TED is capable of counting topological errors, while ignoring small boundary shifts.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的错误测量来比较分割与地面实况。这个我们称之为“容忍编辑距离”（TED）的测量是出于两个观察的启发：（1）一些错误，如小的边界移位，在实践中是可以容忍的。哪些错误是可以容忍的，取决于应用程序，应该是度量的参数。 （2）不可容忍的错误必须手动纠正。这样做的时间应该反映在错误的措施。使用整数线性规划，TED发现分割和合并误差的最小加权和超过了给定的容差标准，因此提供了固定时间估计。与兰德指数或信息变化等常用指标相比，TED（1）不算小，但可容忍的差异，（2）提供了直观的数字，（3）给出了时间固定的估计， 4）可以对错误的类型进行本地化和分类。通过支持各向同性和各向异性体积，并具有灵活的公差标准，TED可以适应不同的要求。在3D神经元分割的示例分割中，我们证明了TED能够计算拓扑错误，而忽略小的边界移位。

##### URL
[https://arxiv.org/abs/1503.02291](https://arxiv.org/abs/1503.02291)

##### PDF
[https://arxiv.org/pdf/1503.02291](https://arxiv.org/pdf/1503.02291)

