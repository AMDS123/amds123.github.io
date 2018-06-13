---
layout: post
title: "Physical Representation-based Predicate Optimization for a Visual Analytics Database"
date: 2018-06-11 20:28:12
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference
author: Michael R. Anderson, Michael Cafarella, German Ros, Thomas F. Wenisch
mathjax: true
---

* content
{:toc}

##### Abstract
Querying the content of images, video, and other non-textual data sources requires expensive content extraction methods. Modern extraction techniques are based on deep convolutional neural networks (CNNs) and can classify objects within images with astounding accuracy. Unfortunately, these methods are slow: processing a single image can take about 10 milliseconds on modern GPU-based hardware. As massive video libraries become ubiquitous, running a content-based query over millions of video frames is prohibitive. 
 One promising approach to reduce the runtime cost of queries of visual content is to use a hierarchical model, such as a cascade, where simple cases are handled by an inexpensive classifier. Prior work has sought to design cascades that optimize the computational cost of inference by, for example, using smaller CNNs. However, we observe that there are critical factors besides the inference time that dramatically impact the overall query time. Notably, by treating the physical representation of the input image as part of our query optimization---that is, by including image transforms, such as resolution scaling or color-depth reduction, within the cascade---we can optimize data handling costs and enable drastically more efficient classifier cascades. 
 In this paper, we propose Tahoma, which generates and evaluates many potential classifier cascades that jointly optimize the CNN architecture and input data representation. Our experiments on a subset of ImageNet show that Tahoma's input transformations speed up cascades by up to 35 times. We also find up to a 98x speedup over the ResNet50 classifier with no loss in accuracy, and a 280x speedup if some accuracy is sacrificed.

##### Abstract (translated by Google)
查询图像，视频和其他非文本数据源的内容需要昂贵的内容提取方法。现代提取技术基于深度卷积神经网络（CNN），可以以惊人的准确性对图像中的对象进行分类。不幸的是，这些方法很慢：在现代基于GPU的硬件上处理单个图像可能需要大约10毫秒。随着海量视频库变得无处不在，在数百万视频帧中运行基于内容的查询是令人望而却步的。
 减少可视内容查询的运行时成本的一种有前途的方法是使用分层模型，例如级联，其中简单的情况由廉价的分类器处理。之前的工作试图设计级联，通过例如使用更小的CNN来优化推断的计算成本。但是，我们观察到，除了推理时间之外，还有一些关键因素会显着影响整个查询时间。值得注意的是，通过将输入图像的物理表示视为查询优化的一部分---也就是说，通过在级联中包含图像转换（如分辨率缩放或颜色深度缩减）---我们可以优化数据处理成本并能够大幅提高分类器的级联效率。
 在本文中，我们提出Tahoma，它生成和评估许多潜在的分类器级联，共同优化CNN体系结构和输入数据表示。我们对ImageNet的一个子集进行的实验表明，Tahoma的输入转换可以将级联速度提高35倍。我们还发现ResNet50分类器的速度提高了98倍，精度没有损失，如果牺牲一些准确度，则速度提高了280倍。

##### URL
[http://arxiv.org/abs/1806.04226](http://arxiv.org/abs/1806.04226)

##### PDF
[http://arxiv.org/pdf/1806.04226](http://arxiv.org/pdf/1806.04226)

