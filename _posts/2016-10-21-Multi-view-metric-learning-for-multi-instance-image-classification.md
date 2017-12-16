---
layout: post
title: "Multi-view metric learning for multi-instance image classification"
date: 2016-10-21 04:46:53
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Object_Detection Image_Classification Optimization Classification Detection Relation Recognition
author: Dewei Li, Yingjie Tian
mathjax: true
---

* content
{:toc}

##### Abstract
It is critical and meaningful to make image classification since it can help human in image retrieval and recognition, object detection, etc. In this paper, three-sides efforts are made to accomplish the task. First, visual features with bag-of-words representation, not single vector, are extracted to characterize the image. To improve the performance, the idea of multi-view learning is implemented and three kinds of features are provided, each one corresponds to a single view. The information from three views is complementary to each other, which can be unified together. Then a new distance function is designed for bags by computing the weighted sum of the distances between instances. The technique of metric learning is explored to construct a data-dependent distance metric to measure the relationships between instances, meanwhile between bags and images, more accurately. Last, a novel approach, called MVML, is proposed, which optimizes the joint probability that every image is similar with its nearest image. MVML learns multiple distance metrics, each one models a single view, to unifies the information from multiple views. The method can be solved by alternate optimization iteratively. Gradient ascent and positive semi-definite projection are utilized in the iterations. Distance comparisons verified that the new bag distance function is prior to previous functions. In model evaluation, numerical experiments show that MVML with multiple views performs better than single view condition, which demonstrates that our model can assemble the complementary information efficiently and measure the distance between images more precisely. Experiments on influence of parameters and instance number validate the consistency of the method.

##### Abstract (translated by Google)
对图像进行分类是非常重要和有意义的，因为它可以帮助人们进行图像检索和识别，目标检测等。本文做了三方面的工作来完成任务。首先，提取具有词袋表示的视觉特征，而不是单个矢量，以表征图像。为了提高性能，实现了多视角学习的思想，提供了三种特征，每种特征对应一个视图。三个视角的信息是互补的，可以统一在一起。然后通过计算实例之间距离的加权和来设计一个新的距离函数。探讨了度量学习技术，构建了一个数据相关距离度量，以更准确地度量实例之间的关系，同时还可以更准确地测量包和图像之间的关系。最后，提出了一种新的方法MVML，该方法优化了每幅图像与其最近图像相似的联合概率。 MVML学习多个距离度量标准，每个距离度量标准为单个视图建模，以统一来自多个视图的信息。该方法可以通过迭代地交替优化来解决。在迭代中使用梯度上升和正半定投影。距离比较证实，新的行李距离功能在先前的功能之前。在模型评估中，数值实验表明，多视点MVML比单视点条件具有更好的表现，说明该模型能够有效地组合补充信息，更精确地测量图像间的距离。参数和实例号影响的实验验证了方法的一致性。

##### URL
[https://arxiv.org/abs/1610.06671](https://arxiv.org/abs/1610.06671)

##### PDF
[https://arxiv.org/pdf/1610.06671](https://arxiv.org/pdf/1610.06671)

