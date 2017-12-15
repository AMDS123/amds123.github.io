---
layout: post
title: "Multi-task CNN Model for Attribute Prediction"
date: 2016-01-04 07:42:56
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Prediction
author: Abrar H. Abdulnabi, Gang Wang, Jiwen Lu, Kui Jia
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a joint multi-task learning algorithm to better predict attributes in images using deep convolutional neural networks (CNN). We consider learning binary semantic attributes through a multi-task CNN model, where each CNN will predict one binary attribute. The multi-task learning allows CNN models to simultaneously share visual knowledge among different attribute categories. Each CNN will generate attribute-specific feature representations, and then we apply multi-task learning on the features to predict their attributes. In our multi-task framework, we propose a method to decompose the overall model's parameters into a latent task matrix and combination matrix. Furthermore, under-sampled classifiers can leverage shared statistics from other classifiers to improve their performance. Natural grouping of attributes is applied such that attributes in the same group are encouraged to share more knowledge. Meanwhile, attributes in different groups will generally compete with each other, and consequently share less knowledge. We show the effectiveness of our method on two popular attribute datasets.

##### Abstract (translated by Google)
本文提出了一个联合多任务学习算法，以更好地预测图像属性使用深度卷积神经网络（CNN）。我们考虑通过多任务CNN模型学习二进制语义属性，其中每个CNN将预测一个二进制属性。多任务学习允许CNN模型同时在不同的属性类别之间共享视觉知识。每个CNN将生成属性特定的特征表示，然后对特征进行多任务学习，以预测其特征。在我们的多任务框架中，我们提出了一种将整体模型的参数分解为潜在任务矩阵和组合矩阵的方法。此外，欠采样分类器可以利用其他分类器的共享统计信息来提高其性能。应用属性的自然分组，以鼓励同一组中的属性共享更多的知识。同时，不同群体的属性通常会相互竞争，共享较少的知识。我们在两个流行的属性数据集上展示了我们的方法的有效性。

##### URL
[https://arxiv.org/abs/1601.00400](https://arxiv.org/abs/1601.00400)

##### PDF
[https://arxiv.org/pdf/1601.00400](https://arxiv.org/pdf/1601.00400)

