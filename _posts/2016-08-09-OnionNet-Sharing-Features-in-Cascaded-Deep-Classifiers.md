---
layout: post
title: "OnionNet: Sharing Features in Cascaded Deep Classifiers"
date: 2016-08-09 08:59:47
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Object_Detection Detection
author: Martin Simonovsky, Nikos Komodakis
mathjax: true
---

* content
{:toc}

##### Abstract
The focus of our work is speeding up evaluation of deep neural networks in retrieval scenarios, where conventional architectures may spend too much time on negative examples. We propose to replace a monolithic network with our novel cascade of feature-sharing deep classifiers, called OnionNet, where subsequent stages may add both new layers as well as new feature channels to the previous ones. Importantly, intermediate feature maps are shared among classifiers, preventing them from the necessity of being recomputed. To accomplish this, the model is trained end-to-end in a principled way under a joint loss. We validate our approach in theory and on a synthetic benchmark. As a result demonstrated in three applications (patch matching, object detection, and image retrieval), our cascade can operate significantly faster than both monolithic networks and traditional cascades without sharing at the cost of marginal decrease in precision.

##### Abstract (translated by Google)
我们工作的重点是加速对检索场景中的深度神经网络的评估，传统的架构可能花费太多的时间在负面的例子上。我们建议用我们的新型级联特征共享深度分类器（称为OnionNet）来取代单片网络，在这种分级深度分类器中，随后的阶段可以同时添加新层和新特征通道。重要的是，中间特征映射在分类器之间共享，防止它们被重新计算的必要性。为了实现这个目标，模型在共同损失的情况下被端对端地原则化训练。我们在理论上和综合基准上验证了我们的方法。结果表明，在三个应用（补丁匹配，目标检测和图像检索）中，我们的级联可以比单片网络和传统级联运行速度快得多，而不会以牺牲精度边际降低为代价。

##### URL
[https://arxiv.org/abs/1608.02728](https://arxiv.org/abs/1608.02728)

##### PDF
[https://arxiv.org/pdf/1608.02728](https://arxiv.org/pdf/1608.02728)

