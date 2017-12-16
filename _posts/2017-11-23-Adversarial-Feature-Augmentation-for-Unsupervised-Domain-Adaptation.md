---
layout: post
title: "Adversarial Feature Augmentation for Unsupervised Domain Adaptation"
date: 2017-11-23 03:17:11
categories: arXiv_CV
tags: arXiv_CV Adversarial Attention GAN Deep_Learning
author: Riccardo Volpi, Pietro Morerio, Silvio Savarese, Vittorio Murino
mathjax: true
---

* content
{:toc}

##### Abstract
Recent works showed that Generative Adversarial Networks (GANs) can be successfully applied in unsupervised domain adaptation, where, given a labeled source dataset and an unlabeled target dataset, the goal is to train powerful classifiers for the target samples. In particular, it was shown that a GAN objective function can be used to learn target features indistinguishable from the source ones. In this work, we extend this framework by (i) forcing the learned feature extractor to be domain-invariant, and (ii) training it through data augmentation in the feature space, namely performing feature augmentation. While data augmentation in the image space is a well established technique in deep learning, feature augmentation has not yet received the same level of attention. We accomplish it by means of a feature generator trained by playing the GAN minimax game against source features. Results show that both enforcing domain-invariance and performing feature augmentation lead to superior or comparable performance to state-of-the-art results in several unsupervised domain adaptation benchmarks.

##### Abstract (translated by Google)
最近的工作表明，生成对手网络（GANs）可以成功地应用于无监督领域适应，其中，给定一个标记的源数据集和一个未标记的目标数据集，目标是训练目标样本强大的分类器。特别是，显示GAN目标函数可以用来学习与源代码不可区分的目标特征。在这项工作中，我们通过以下方式来扩展这个框架：（i）迫使学习的特征提取器是域不变的;（ii）通过特征空间中的数据增强来训练它，即执行特征增强。虽然图像空间中的数据增强在深度学习中是一种成熟的技术，但是特征增强还没有得到同样的关注。我们通过使用GAN minimax游戏对源代码特征进行训练的特征生成器来实现它。结果表明，在几个无监督的域适应基准中，执行域不变性和执行特征增强导致优异的或可比较的性能与最先进的结果。

##### URL
[https://arxiv.org/abs/1711.08561](https://arxiv.org/abs/1711.08561)

##### PDF
[https://arxiv.org/pdf/1711.08561](https://arxiv.org/pdf/1711.08561)

