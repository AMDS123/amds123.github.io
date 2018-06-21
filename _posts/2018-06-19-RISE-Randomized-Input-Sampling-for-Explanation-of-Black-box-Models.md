---
layout: post
title: "RISE: Randomized Input Sampling for Explanation of Black-box Models"
date: 2018-06-19 18:41:30
categories: arXiv_CV
tags: arXiv_CV Salient Prediction
author: Vitali Petsiuk, Abir Das, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are increasingly being used to automate data analysis and decision making, yet their decision process remains largely unclear and difficult to explain to end users. In this paper, we address the problem of Explainable AI for deep neural networks that take images as input and output a class probability. We propose an approach called RISE that generates an importance map indicating how salient each pixel is for the model's prediction. In contrast to white-box approaches that estimate pixel importance using gradients or other internal network state, RISE works on black-box models. It estimates importance empirically by probing the model with randomly masked versions of the input image and obtaining the corresponding outputs. We compare our approach to state-of-the-art importance extraction methods using both an automatic deletion/insertion metric and a pointing metric based on human-annotated object segments. Extensive experiments on several benchmark datasets show that our approach matches or exceeds the performance of other methods, including white-box approaches.

##### Abstract (translated by Google)
深度神经网络越来越多地被用于数据分析和决策自动化，但他们的决策过程在很大程度上仍不清楚，难以向最终用户解释。在本文中，我们解决了将图像作为输入并输出类概率的深度神经网络的可解释AI的问题。我们提出了一种称为RISE的方法，该方法生成一个重要图，指示每个像素对于模型预测的显着程度。与使用梯度或其他内部网络状态估计像素重要性的白盒方法相反，RISE适用于黑盒模型。它通过用输入图像的随机掩蔽版本探测模型并获得相应的输出来估计经验上的重要性。我们将我们的方法与使用自动删除/插入度量和基于人类注释对象段的指向度量的最新重要性提取方法进行比较。对几个基准数据集进行的大量实验表明，我们的方法与其他方法的性能相匹配或超过其他方法的性能，包括白盒方法。

##### URL
[http://arxiv.org/abs/1806.07421](http://arxiv.org/abs/1806.07421)

##### PDF
[http://arxiv.org/pdf/1806.07421](http://arxiv.org/pdf/1806.07421)

