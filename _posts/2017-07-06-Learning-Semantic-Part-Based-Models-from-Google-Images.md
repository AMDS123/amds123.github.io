---
layout: post
title: "Learning Semantic Part-Based Models from Google Images"
date: 2017-07-06 17:14:14
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Davide Modolo, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a technique to train semantic part-based models of object classes from Google Images. Our models encompass the appearance of parts and their spatial arrangement on the object, specific to each viewpoint. We learn these rich models by collecting training instances for both parts and objects, and automatically connecting the two levels. Our framework works incrementally, by learning from easy examples first, and then gradually adapting to harder ones. A key benefit of this approach is that it requires no manual part location annotations. We evaluate our models on the challenging PASCAL-Part dataset [1] and show how their performance increases at every step of the learning, with the final models more than doubling the performance of directly training from images retrieved by querying for part names (from 12.9 to 27.2 AP). Moreover, we show that our part models can help object detection performance by enriching the R-CNN detector with parts.

##### Abstract (translated by Google)
我们提出了一种技术来训练来自Google Images的对象类的基于语义部分的模型。我们的模型包括部件的外观和它们在物体上的空间排列，特定于每个视点。我们通过为零件和对象收集训练实例并自动连接两个级别来学习这些丰富的模型。我们的框架是渐进式的，首先从简单的例子中学习，然后逐渐适应困难的例子。这种方法的一个关键好处是它不需要手动的零件位置注释。我们在具有挑战性的PASCAL-Part数据集[1]上评估我们的模型，并展示它们在学习的每个步骤中的性能如何提高，最终模型比通过查询部分名称检索的图像的直接训练性能提高了一倍到27.2 AP）。此外，我们表明，我们的部分模型可以通过丰富R-CNN探测器与零件来帮助物体探测性能。

##### URL
[https://arxiv.org/abs/1609.03140](https://arxiv.org/abs/1609.03140)

##### PDF
[https://arxiv.org/pdf/1609.03140](https://arxiv.org/pdf/1609.03140)

