---
layout: post
title: "The Conditional Lucas & Kanade Algorithm"
date: 2016-03-29 00:34:07
categories: arXiv_CV
tags: arXiv_CV Relation
author: Chen-Hsuan Lin, Rui Zhu, Simon Lucey
mathjax: true
---

* content
{:toc}

##### Abstract
The Lucas & Kanade (LK) algorithm is the method of choice for efficient dense image and object alignment. The approach is efficient as it attempts to model the connection between appearance and geometric displacement through a linear relationship that assumes independence across pixel coordinates. A drawback of the approach, however, is its generative nature. Specifically, its performance is tightly coupled with how well the linear model can synthesize appearance from geometric displacement, even though the alignment task itself is associated with the inverse problem. In this paper, we present a new approach, referred to as the Conditional LK algorithm, which: (i) directly learns linear models that predict geometric displacement as a function of appearance, and (ii) employs a novel strategy for ensuring that the generative pixel independence assumption can still be taken advantage of. We demonstrate that our approach exhibits superior performance to classical generative forms of the LK algorithm. Furthermore, we demonstrate its comparable performance to state-of-the-art methods such as the Supervised Descent Method with substantially less training examples, as well as the unique ability to "swap" geometric warp functions without having to retrain from scratch. Finally, from a theoretical perspective, our approach hints at possible redundancies that exist in current state-of-the-art methods for alignment that could be leveraged in vision systems of the future.

##### Abstract (translated by Google)
Lucas和Kanade（LK）算法是高效密集图像和对象对齐的首选方法。该方法是有效的，因为它试图通过在像素坐标上独立的线性关系来模拟外观和几何位移之间的关系。然而，这种方法的一个缺点是它的生成性。具体而言，即使对准任务本身与逆问题相关联，其性能与线性模型如何从几何位移合成外观紧密耦合。在本文中，我们提出了一种新的方法，被称为条件LK算法，它：（一）直接学习线性模型，预测几何位移作为外观的函数，和（二）采用新的战略，确保生成像素独立假设仍然可以被利用。我们证明了我们的方法展现了LK算法的经典生成形式的优越性能。此外，我们展示了与监督式下降法等最先进的方法相媲美的性能，其训练实例少得多，以及独特的“交换”几何变形功能而无需从头开始重新训练。最后，从理论角度来看，我们的方法暗示了当前最先进的校准方法中可能存在的冗余，这些方法可以在未来的视觉系统中使用。

##### URL
[https://arxiv.org/abs/1603.08597](https://arxiv.org/abs/1603.08597)

##### PDF
[https://arxiv.org/pdf/1603.08597](https://arxiv.org/pdf/1603.08597)

