---
layout: post
title: "Conditional Prior Networks for Optical Flow"
date: 2018-07-26 21:49:36
categories: arXiv_CV
tags: arXiv_CV Regularization Relation
author: Yanchao Yang, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
Classical computation of optical flow involves generic priors (regularizers) that capture rudimentary statistics of images, but not long-range correlations or semantics. On the other hand, fully supervised methods learn the regularity in the annotated data, without explicit regularization and with the risk of overfitting. We seek to learn richer priors on the set of possible flows that are statistically compatible with an image. Once the prior is learned in a supervised fashion, one can easily learn the full map to infer optical flow directly from two or more images, without any need for (additional) supervision. We introduce a novel architecture, called Conditional Prior Network (CPN), and show how to train it to yield a conditional prior. When used in conjunction with a simple optical flow architecture, the CPN beats all variational methods and all unsupervised learning-based ones using the same data term. It performs comparably to fully supervised ones, that however are fine-tuned to a particular dataset. Our method, on the other hand, performs well even when transferred between datasets.

##### Abstract (translated by Google)
光流的经典计算涉及通用先验（正则化器），其捕获图像的基本统计，但不捕获远程相关或语义。另一方面，完全监督的方法学习注释数据的规律性，没有明确的正规化和过度拟合的风险。我们寻求在统计上与图像兼容的可能流的集合上学习更丰富的先验。一旦以受监督的方式学习先验，可以容易地学习完整的地图以直接从两个或更多图像推断光流，而无需（附加）监督。我们引入了一种称为条件先验网络（CPN）的新颖架构，并展示了如何训练它以产生条件先验。当与简单的光流结构一起使用时，CPN使用相同的数据项击败所有变分方法和所有无监督的基于学习的方法。它与完全受监督的相比具有相同的性能，然而它们可以根据特定的数据集进行微调。另一方面，即使在数据集之间传输，我们的方法也表现良好。

##### URL
[http://arxiv.org/abs/1807.10378](http://arxiv.org/abs/1807.10378)

##### PDF
[http://arxiv.org/pdf/1807.10378](http://arxiv.org/pdf/1807.10378)

