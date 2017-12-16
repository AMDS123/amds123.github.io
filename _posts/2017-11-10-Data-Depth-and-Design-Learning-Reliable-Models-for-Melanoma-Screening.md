---
layout: post
title: "Data, Depth, and Design: Learning Reliable Models for Melanoma Screening"
date: 2017-11-10 16:49:34
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Optimization Deep_Learning
author: Eduardo Valle, Michel Fornaciali, Afonso Menegola, Julia Tavares, Flávia Vasques Bittencourt, Lin Tzy Li, Sandra Avila
mathjax: true
---

* content
{:toc}

##### Abstract
State of the art on melanoma screening evolved rapidly in the last two years, with the adoption of deep learning. Those models, however, pose challenges of their own, as they are expensive to train and difficult to parameterize. Objective: We investigate the methodological issues for designing and evaluating deep learning models for melanoma screening, by exploring nine choices often faced to design deep networks: model architecture, training dataset, image resolution, type of data augmentation, input normalization, use of segmentation, duration of training, additional use of SVM, and test data augmentation. Methods: We perform a two-level full factorial experiment, for five different test datasets, resulting in 2560 exhaustive trials, which we analyze using a multi-way ANOVA. Results: The main finding is that the size of training data has a disproportionate influence, explaining almost half the variation in performance. Of the other factors, test data augmentation and input resolution are the most helpful. Deeper models, when combined, with extra data, also help. We show that the costly full factorial design, or the unreliable sequential optimization, are not the only options: ensembles of models provide reliable results with limited resources. Conclusions and Significance: To move research forward on automated melanoma screening, we need to curate larger shared datasets. Optimizing hyperparameters and measuring performance on the same dataset is common, but leads to overoptimistic results. Ensembles of models are a cost-effective alternative to the expensive full-factorial and to the unstable sequential designs.

##### Abstract (translated by Google)
在过去的两年中，黑色素瘤筛查技术的发展迅速，通过深度学习。但是，这些模式本身就是一个挑战，因为它们的培训成本很高，而且难以参数化。目的：通过探索设计深度网络常常面临的九个选择：模型架构，训练数据集，图像分辨率，数据增强类型，输入标准化，分割的使用等，研究设计和评估黑素瘤筛查深度学习模型的方法学问题。训练持续时间，额外使用SVM和测试数据增加。方法：我们对5个不同的测试数据集进行了两级全因子实验，得到了2560个穷举实验，我们使用多方差分析进行分析。结果：主要的发现是，训练数据的大小具有不成比例的影响，几乎解释了一半的性能变化。其他因素中，测试数据增强和输入分辨率是最有帮助的。更深入的模型，加上额外的数据，也有帮助。我们表明，昂贵的全因子设计，或不可靠的顺序优化，不是唯一的选择：模型集合提供有限的资源可靠的结果。结论和意义：为了推动自动黑素瘤筛查的研究，我们需要策划更大的共享数据集。优化超参数和测量相同数据集的性能是常见的，但会导致过度乐观的结果。模型的集合是昂贵的全因子和不稳定的顺序设计的一种经济有效的替代方案。

##### URL
[https://arxiv.org/abs/1711.00441](https://arxiv.org/abs/1711.00441)

##### PDF
[https://arxiv.org/pdf/1711.00441](https://arxiv.org/pdf/1711.00441)

