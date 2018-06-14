---
layout: post
title: "Multiple Instance Learning for Heterogeneous Images: Training a CNN for Histopathology"
date: 2018-06-13 14:24:44
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Prediction
author: Heather D. Couture, J.S. Marron, Charles M. Perou, Melissa A. Troester, Marc Niethammer
mathjax: true
---

* content
{:toc}

##### Abstract
Multiple instance (MI) learning with a convolutional neural network enables end-to-end training in the presence of weak image-level labels. We propose a new method for aggregating predictions from smaller regions of the image into an image-level classification by using the quantile function. The quantile function provides a more complete description of the heterogeneity within each image, improving image-level classification. We also adapt image augmentation to the MI framework by randomly selecting cropped regions on which to apply MI aggregation during each epoch of training. This provides a mechanism to study the importance of MI learning. We validate our method on five different classification tasks for breast tumor histology and provide a visualization method for interpreting local image classifications that could lead to future insights into tumor heterogeneity.

##### Abstract (translated by Google)
利用卷积神经网络进行多重实例（MI）学习，可以在存在弱图像级标签的情况下进行端到端培训。我们提出了一种新方法，通过使用分位数函数将来自图像较小区域的预测聚合到图像级分类中。分位函数提供了对每幅图像中异质性的更完整描述，从而改善了图像级分类。我们还通过随机选择在每个训练时期应用MI聚合的裁剪区域来将图像增强调整到MI框架。这提供了一个机制来研究MI学习的重要性。我们验证了我们的方法在乳腺肿瘤组织学五种不同的分类任务中，并提供了一种解释局部图像分类的可视化方法，可以导致未来洞察肿瘤异质性。

##### URL
[http://arxiv.org/abs/1806.05083](http://arxiv.org/abs/1806.05083)

##### PDF
[http://arxiv.org/pdf/1806.05083](http://arxiv.org/pdf/1806.05083)

