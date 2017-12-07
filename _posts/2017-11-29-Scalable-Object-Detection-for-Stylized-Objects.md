---
layout: post
title: "Scalable Object Detection for Stylized Objects"
date: 2017-11-29 10:04:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection Recognition
author: Aayush Garg, Thilo Will, William Darling, Willi Richert, Clemens Marschner
mathjax: true
---

* content
{:toc}

##### Abstract
Following recent breakthroughs in convolutional neural networks and monolithic model architectures, state-of-the-art object detection models can reliably and accurately scale into the realm of up to thousands of classes. Things quickly break down, however, when scaling into the tens of thousands, or, eventually, to millions or billions of unique objects. Further, bounding box-trained end-to-end models require extensive training data. Even though - with some tricks using hierarchies - one can sometimes scale up to thousands of classes, the labor requirements for clean image annotations quickly get out of control. In this paper, we present a two-layer object detection method for brand logos and other stylized objects for which prototypical images exist. It can scale to large numbers of unique classes. Our first layer is a CNN from the Single Shot Multibox Detector family of models that learns to propose regions where some stylized object is likely to appear. The contents of a proposed bounding box is then run against an image index that is targeted for the retrieval task at hand. The proposed architecture scales to a large number of object classes, allows to continously add new classes without retraining, and exhibits state-of-the-art quality on a stylized object detection task such as logo recognition.

##### Abstract (translated by Google)
在卷积神经网络和单片模型体系结构的最新突破之后，最先进的物体检测模型可以可靠而精确地扩展到多达数千个类的领域。然而，当数以万计甚至数以百万计或数十亿计的独特物体扩展时，情况会迅速恶化。此外，边界盒训练的端到端模型需要大量的训练数据。即使 - 使用层次结构的一些技巧 - 有时可以扩展到数以千计的类，干净的图像注释的劳动需求很快失去控制。在本文中，我们提出了一个品牌标识和其他程式化对象的原型图像存在的两层对象检测方法。它可以扩展到大量的独特类。我们的第一层是来自Single Shot Multibox Detector系列模型的CNN，该模型学习提出可能出现某些程式化对象的区域。然后针对目标检索任务的图像索引运行提出的边界框的内容。所提出的体系结构扩展到大量的对象类别，允许不经过再培训而连续地添加新的类别，并且在程序化的对象检测任务（例如标识识别）上展现最新的质量。

##### URL
[https://arxiv.org/abs/1711.09822](https://arxiv.org/abs/1711.09822)

##### PDF
[https://arxiv.org/pdf/1711.09822](https://arxiv.org/pdf/1711.09822)

