---
layout: post
title: "Unsupervised Natural Image Patch Learning"
date: 2018-06-28 18:21:43
categories: arXiv_CV
tags: arXiv_CV Embedding
author: Dov Danon, Hadar Averbuch-Elor, Ohad Fried, Daniel Cohen-Or
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a metric of natural image patches is an important tool for analyzing images. An efficient means is to train a deep network to map an image patch to a vector space, in which the Euclidean distance reflects patch similarity. Previous attempts learned such an embedding in a supervised manner, requiring the availability of many annotated images. In this paper, we present an unsupervised embedding of natural image patches, avoiding the need for annotated images. The key idea is that the similarity of two patches can be learned from the prevalence of their spatial proximity in natural images. Clearly, relying on this simple principle, many spatially nearby pairs are outliers, however, as we show, the outliers do not harm the convergence of the metric learning. We show that our unsupervised embedding approach is more effective than a supervised one or one that uses deep patch representations. Moreover, we show that it naturally leads itself to an efficient self-supervised domain adaptation technique onto a target domain that contains a common foreground object.

##### Abstract (translated by Google)
学习自然图像块的度量是分析图像的重要工具。一种有效的方法是训练深度网络以将图像块映射到向量空间，其中欧几里德距离反映了块的相似性。先前的尝试以受监督的方式学习了这种嵌入，需要许多带注释的图像的可用性。在本文中，我们提出了一种无监督的自然图像补丁嵌入，避免了对带注释图像的需求。关键思想是两个斑块的相似性可以从它们在自然图像中的空间接近度的普遍性中学习。很明显，依靠这个简单的原理，许多空间上邻近的对是异常值，然而，正如我们所示，异常值不会损害度量学习的收敛性。我们证明了我们的无监督嵌入方法比使用深度补丁表示的监督方法或方法更有效。此外，我们表明它自然地将自身引导到包含共同前景对象的目标域上的有效自监督域自适应技术。

##### URL
[http://arxiv.org/abs/1807.03130](http://arxiv.org/abs/1807.03130)

##### PDF
[http://arxiv.org/pdf/1807.03130](http://arxiv.org/pdf/1807.03130)

