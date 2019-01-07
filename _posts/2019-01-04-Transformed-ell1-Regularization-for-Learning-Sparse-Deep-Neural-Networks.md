---
layout: post
title: "Transformed $ell_1$ Regularization for Learning Sparse Deep Neural Networks"
date: 2019-01-04 08:46:16
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Knowledge Optimization
author: Rongrong Ma, Jianyu Miao, Lingfeng Niu, Peng Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have achieved extraordinary success in numerous areas. However, to attain this success, DNNs often carry a large number of weight parameters, leading to heavy costs of memory and computation resources. Overfitting is also likely to happen in such network when the training data are insufficient. These shortcomings severely hinder the application of DNNs in resource-constrained platforms. In fact, many network weights are known to be redundant and can be removed from the network without much loss of performance. To this end, we introduce a new non-convex integrated transformed $\ell_1$ regularizer to promote sparsity for DNNs, which removes both redundant connections and unnecessary neurons simultaneously. To be specific, we apply the transformed $\ell_1$ to the matrix space of network weights and utilize it to remove redundant connections. Besides, group sparsity is also employed as an auxiliary to remove unnecessary neurons. An efficient stochastic proximal gradient algorithm is presented to solve the new model at the same time. To the best of our knowledge, this is the first work to utilize a non-convex regularizer in sparse optimization based method to promote sparsity for DNNs. Experiments on several public datasets demonstrate the effectiveness of the proposed method.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1901.01021](https://arxiv.org/abs/1901.01021)

##### PDF
[https://arxiv.org/pdf/1901.01021](https://arxiv.org/pdf/1901.01021)

