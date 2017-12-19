---
layout: post
title: "Do We Need More Training Data?"
date: 2015-03-05 01:51:12
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection Detection Recognition
author: Xiangxin Zhu, Carl Vondrick, Charless Fowlkes, Deva Ramanan
mathjax: true
---

* content
{:toc}

##### Abstract
Datasets for training object recognition systems are steadily increasing in size. This paper investigates the question of whether existing detectors will continue to improve as data grows, or saturate in performance due to limited model complexity and the Bayes risk associated with the feature spaces in which they operate. We focus on the popular paradigm of discriminatively trained templates defined on oriented gradient features. We investigate the performance of mixtures of templates as the number of mixture components and the amount of training data grows. Surprisingly, even with proper treatment of regularization and "outliers", the performance of classic mixture models appears to saturate quickly ($\sim$10 templates and $\sim$100 positive training examples per template). This is not a limitation of the feature space as compositional mixtures that share template parameters via parts and that can synthesize new templates not encountered during training yield significantly better performance. Based on our analysis, we conjecture that the greatest gains in detection performance will continue to derive from improved representations and learning algorithms that can make efficient use of large datasets.

##### Abstract (translated by Google)
用于训练目标识别系统的数据集正在稳步增加。本文研究了现有检测器是否会随着数据增长而继续改进的问题，或者由于模型复杂性有限以及与其运行的特征空间相关的贝叶斯风险而导致性能饱和。我们专注于在定向渐变特征上定义的受歧视训练模板的流行范例。我们调查模板的混合物的性能随着混合物组分的数量和培训数据的增长。令人惊讶的是，即使对正则化和“异常值”进行了适当的处理，经典混合模型的表现也会迅速饱和（每个模板$ $ sim $ 10个模板和$ 100个正面训练示例）。这不是对特征空间的限制，因为通过部件共享模板参数的组成混合物并且可以合成在训练期间不遇到的新模板产生显着更好的性能。基于我们的分析，我们猜测检测性能的最大收益将继续来自改进的表示和学习算法，可以有效利用大型数据集。

##### URL
[https://arxiv.org/abs/1503.01508](https://arxiv.org/abs/1503.01508)

##### PDF
[https://arxiv.org/pdf/1503.01508](https://arxiv.org/pdf/1503.01508)

