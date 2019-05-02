---
layout: post
title: "Self-Supervised Convolutional Subspace Clustering Network"
date: 2019-05-01 01:05:25
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification
author: Junjian Zhang, Chun-Guang Li, Chong You, Xianbiao Qi, Honggang Zhang, Jun Guo, Zhouchen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Subspace clustering methods based on data self-expression have become very popular for learning from data that lie in a union of low-dimensional linear subspaces. However, the applicability of subspace clustering has been limited because practical visual data in raw form do not necessarily lie in such linear subspaces. On the other hand, while Convolutional Neural Network (ConvNet) has been demonstrated to be a powerful tool for extracting discriminative features from visual data, training such a ConvNet usually requires a large amount of labeled data, which are unavailable in subspace clustering applications. To achieve simultaneous feature learning and subspace clustering, we propose an end-to-end trainable framework, called Self-Supervised Convolutional Subspace Clustering Network (S$^2$ConvSCN), that combines a ConvNet module (for feature learning), a self-expression module (for subspace clustering) and a spectral clustering module (for self-supervision) into a joint optimization framework. Particularly, we introduce a dual self-supervision that exploits the output of spectral clustering to supervise the training of the feature learning module (via a classification loss) and the self-expression module (via a spectral clustering loss). Our experiments on four benchmark datasets show the effectiveness of the dual self-supervision and demonstrate superior performance of our proposed approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.00149](http://arxiv.org/abs/1905.00149)

##### PDF
[http://arxiv.org/pdf/1905.00149](http://arxiv.org/pdf/1905.00149)

