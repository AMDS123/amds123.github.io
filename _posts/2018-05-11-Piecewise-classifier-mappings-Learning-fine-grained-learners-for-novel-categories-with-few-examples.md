---
layout: post
title: "Piecewise classifier mappings: Learning fine-grained learners for novel categories with few examples"
date: 2018-05-11 09:24:15
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Recognition
author: Xiu-Shen Wei, Peng Wang, Lingqiao Liu, Chunhua Shen, Jianxin Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Humans are capable of learning a new fine-grained concept with very little supervision, e.g., few exemplary images for a species of bird, yet our best deep learning systems need hundreds or thousands of labeled examples. In this paper, we try to reduce this gap by studying the fine-grained image recognition problem in a challenging few-shot learning setting, termed few-shot fine-grained recognition (FSFG). The task of FSFG requires the learning systems to build classifiers for novel fine-grained categories from few examples (only one or less than five). To solve this problem, we propose an end-to-end trainable deep network which is inspired by the state-of-the-art fine-grained recognition model and is tailored for the FSFG task. 
 Specifically, our network consists of a bilinear feature learning module and a classifier mapping module: while the former encodes the discriminative information of an exemplar image into a feature vector, the latter maps the intermediate feature into the decision boundary of the novel category. The key novelty of our model is a "piecewise mappings" function in the classifier mapping module, which generates the decision boundary via learning a set of more attainable sub-classifiers in a more parameter-economic way. We learn the exemplar-to-classifier mapping based on an auxiliary dataset in a meta-learning fashion, which is expected to be able to generalize to novel categories. By conducting comprehensive experiments on three fine-grained datasets, we demonstrate that the proposed method achieves superior performance over the competing baselines.

##### Abstract (translated by Google)
人类能够在很少监督的情况下学习一种新的细粒度概念，例如，一些鸟类的典型图像很少，但是我们最好的深度学习系统需要数百或数千个标记的例子。在本文中，我们试图通过在一个具有挑战性的少量镜头学习环境中研究细粒度图像识别问题来缩小这种差距，称为少镜头细粒度识别（FSFG）。 FSFG的任务要求学习系统从几个例子（只有一个或少于五个）为新的细粒度类别构建分类器。为了解决这个问题，我们提出了一个端到端的可训练深度网络，它受到最先进的细粒度识别模型的启发，并且为FSFG任务量身定制。
 具体而言，我们的网络由双线性特征学习模块和分类器映射模块组成：前者将示例图像的区分信息编码为特征向量，后者将中间特征映射到新类别的决策边界。我们的模型的关键新颖之处在于分类器映射模块中的“分段映射”功能，其通过以更多参数经济的方式学习一组更可达到的子分类器来产生决策边界。我们以元学习的方式学习基于辅助数据集的范例到分类器映射，预计它能够推广到新的范畴。通过对三个细粒度数据集进行全面的实验，我们证明了所提出的方法在竞争基线上实现了优越的性能。

##### URL
[http://arxiv.org/abs/1805.04288](http://arxiv.org/abs/1805.04288)

##### PDF
[http://arxiv.org/pdf/1805.04288](http://arxiv.org/pdf/1805.04288)

