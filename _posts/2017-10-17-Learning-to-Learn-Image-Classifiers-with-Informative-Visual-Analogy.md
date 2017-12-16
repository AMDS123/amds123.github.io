---
layout: post
title: "Learning to Learn Image Classifiers with Informative Visual Analogy"
date: 2017-10-17 09:17:33
categories: arXiv_CV
tags: arXiv_CV Knowledge GAN Embedding CNN Image_Classification Classification
author: Linjun Zhou, Peng Cui, Shiqiang Yang, Wenwu Zhu, Qi Tian
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, we witnessed a huge success of Convolutional Neural Networks on the task of the image classification. However, these models are notoriously data hungry and require tons of training images to learn the parameters. In contrast, people are far better learner who can learn a new concept very fast with only a few samples. The plausible mysteries making the difference are two fundamental learning mechanisms: learning to learn and learning by analogy. In this paper, we attempt to investigate a new human-like learning method by organically combining these two mechanisms. In particular, we study how to generalize the classification parameters of previously learned concepts to a new concept. we first propose a novel Visual Analogy Network Embedded Regression (VANER) model to jointly learn a low-dimensional embedding space and a linear mapping function from the embedding space to classification parameters for base classes. We then propose an out-of-sample embedding method to learn the embedding of a new class represented by a few samples through its visual analogy with base classes. By inputting the learned embedding into VANER, we can derive the classification parameters for the new class.These classification parameters are purely generalized from base classes (i.e. transferred classification parameters), while the samples in the new class, although only a few, can also be exploited to generate a set of classification parameters (i.e. model classification parameters). Therefore, we further investigate the fusion strategy of the two kinds of parameters so that the prior knowledge and data knowledge can be fully leveraged. We also conduct extensive experiments on ImageNet and the results show that our method can consistently and significantly outperform state-of-the-art baselines.

##### Abstract (translated by Google)
近年来，我们在卷积神经网络的图像分类任务上见证了巨大的成功。但是，这些模型是众所周知的数据饥饿，需要大量的训练图像来学习参数。相比之下，人们是一个更好的学习者，只有少数样本可以快速学习一个新的概念。造成差异的合理的奥秘是两个基本的学习机制：学习学习和类比学习。在本文中，我们试图通过有机结合这两种机制来研究一种新的类人学习方法。特别是，我们研究如何将以前学过的概念的分类参数推广到一个新的概念。我们首先提出了一种新颖的视觉类比网络嵌入回归（VANER）模型来联合学习一个低维的嵌入空间和一个从嵌入空间到基类的分类参数的线性映射函数。然后，我们提出一个样本外嵌入方法，通过它与基类的可视化类比来学习由几个样本表示的新类的嵌入。通过将学习到的嵌入输入到VANER中，我们可以导出新类的分类参数。这些分类参数纯粹从基类（即转移的分类参数）推广，而新类中的样本虽然只有少数也可以被利用来生成一组分类参数（即模型分类参数）。因此，我们进一步研究两种参数的融合策略，以充分利用现有的知识和数据知识。我们还对ImageNet进行了广泛的实验，结果表明，我们的方法可以始终如一地大大超越最先进的基线。

##### URL
[https://arxiv.org/abs/1710.06177](https://arxiv.org/abs/1710.06177)

##### PDF
[https://arxiv.org/pdf/1710.06177](https://arxiv.org/pdf/1710.06177)

