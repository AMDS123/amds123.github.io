---
layout: post
title: "Localization-Aware Active Learning for Object Detection"
date: 2018-01-16 05:43:53
categories: arXiv_CV
tags: arXiv_CV Object_Detection Image_Classification Classification Prediction Detection
author: Chieh-Chi Kao, Teng-Yok Lee, Pradeep Sen, Ming-Yu Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Active learning - a class of algorithms that iteratively searches for the most informative samples to include in a training dataset - has been shown to be effective at annotating data for image classification. However, the use of active learning for object detection is still largely unexplored as determining informativeness of an object-location hypothesis is more difficult. In this paper, we address this issue and present two metrics for measuring the informativeness of an object hypothesis, which allow us to leverage active learning to reduce the amount of annotated data needed to achieve a target object detection performance. Our first metric measures 'localization tightness' of an object hypothesis, which is based on the overlapping ratio between the region proposal and the final prediction. Our second metric measures 'localization stability' of an object hypothesis, which is based on the variation of predicted object locations when input images are corrupted by noise. Our experimental results show that by augmenting a conventional active-learning algorithm designed for classification with the proposed metrics, the amount of labeled training data required can be reduced up to 25%. Moreover, on PASCAL 2007 and 2012 datasets our localization-stability method has an average relative improvement of 96.5% and 81.9% over the baseline method using classification only.

##### Abstract (translated by Google)
主动学习 - 一类迭代搜索最丰富的样本以包含在训练数据集中的算法 - 已经被证明对于图像分类的数据注释是有效的。然而，主动学习在物体检测中的使用仍然在很大程度上尚未被探索，因为确定物体位置假设的信息性更加困难。在本文中，我们解决了这个问题，并提出了衡量一个对象假设的信息性的两个指标，这使我们能够利用主动学习来减少实现目标对象检测性能所需的注释数据量。我们的第一个度量标准是基于区域建议与最终预测之间重叠比例的对象假设的“局部紧密度”。我们的第二个度量标准是对象假设的“局部稳定性”，它是基于输入图像被噪声破坏时预测对象位置的变化。我们的实验结果表明，通过增加传统的主动学习算法设计的分类与提出的指标，标记的训练数据所需的数量可以减少高达25％。此外，在PASCAL 2007和2012数据集上，我们的定位稳定性方法与仅使用分类的基线方法相比，平均相对提高了96.5％和81.9％。

##### URL
[http://arxiv.org/abs/1801.05124](http://arxiv.org/abs/1801.05124)

##### PDF
[http://arxiv.org/pdf/1801.05124](http://arxiv.org/pdf/1801.05124)

