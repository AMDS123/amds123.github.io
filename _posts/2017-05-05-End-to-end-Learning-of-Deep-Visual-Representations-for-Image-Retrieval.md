---
layout: post
title: "End-to-end Learning of Deep Visual Representations for Image Retrieval"
date: 2017-05-05 15:34:09
categories: arXiv_CV
tags: arXiv_CV Image_Caption Image_Retrieval Deep_Learning
author: Albert Gordo, Jon Almazan, Jerome Revaud, Diane Larlus
mathjax: true
---

* content
{:toc}

##### Abstract
While deep learning has become a key ingredient in the top performing methods for many computer vision tasks, it has failed so far to bring similar improvements to instance-level image retrieval. In this article, we argue that reasons for the underwhelming results of deep methods on image retrieval are threefold: i) noisy training data, ii) inappropriate deep architecture, and iii) suboptimal training procedure. We address all three issues. First, we leverage a large-scale but noisy landmark dataset and develop an automatic cleaning method that produces a suitable training set for deep retrieval. Second, we build on the recent R-MAC descriptor, show that it can be interpreted as a deep and differentiable architecture, and present improvements to enhance it. Last, we train this network with a siamese architecture that combines three streams with a triplet loss. At the end of the training process, the proposed architecture produces a global image representation in a single forward pass that is well suited for image retrieval. Extensive experiments show that our approach significantly outperforms previous retrieval approaches, including state-of-the-art methods based on costly local descriptor indexing and spatial verification. On Oxford 5k, Paris 6k and Holidays, we respectively report 94.7, 96.6, and 94.8 mean average precision. Our representations can also be heavily compressed using product quantization with little loss in accuracy. For additional material, please see www.xrce.xerox.com/Deep-Image-Retrieval.

##### Abstract (translated by Google)
虽然深度学习已经成为许多计算机视觉任务的顶级执行方法中的关键要素，但迄今为止还没有为实例级图像检索带来类似的改进。在这篇文章中，我们认为，深层次的图像检索方法的结果令人沮丧的原因有三：一是有噪声的训练数据，二是不恰当的深层结构，三是次优的训练过程。我们解决所有三个问题。首先，我们利用一个大规模但嘈杂的地标数据集，并开发一种自动清理方法，为深度检索提供合适的训练集。其次，基于最近的R-MAC描述符，表明它可以被解释为一个深刻而可区分的架构，并且提出改进来加强它。最后，我们用一个暹罗式的结构来训练这个网络，这个结构把三个流结合起来，造成三重损失。在训练过程结束时，所提出的体系结构在单个正向通道中产生全局图像表示，其非常适合于图像检索。大量实验表明，我们的方法明显优于先前的检索方法，包括基于昂贵的局部描述符索引和空间验证的最新方法。在牛津5k，巴黎6k和假期，我们分别报告了94.7,96.6和94.8的平均精确度。我们的表示也可以使用产品量化严重压缩，精度损失很小。有关其他材料，请参阅www.xrce.xerox.com/Deep-Image-Retrieval。

##### URL
[https://arxiv.org/abs/1610.07940](https://arxiv.org/abs/1610.07940)

##### PDF
[https://arxiv.org/pdf/1610.07940](https://arxiv.org/pdf/1610.07940)

