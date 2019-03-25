---
layout: post
title: "Towards Optimal Structured CNN Pruning via Generative Adversarial Learning"
date: 2019-03-22 01:26:33
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Sparse CNN Optimization
author: Shaohui Lin, Rongrong Ji, Chenqian Yan, Baochang Zhang, Liujuan Cao, Qixiang Ye, Feiyue Huang, David Doermann
mathjax: true
---

* content
{:toc}

##### Abstract
Structured pruning of filters or neurons has received increased focus for compressing convolutional neural networks. Most existing methods rely on multi-stage optimizations in a layer-wise manner for iteratively pruning and retraining which may not be optimal and may be computation intensive. Besides, these methods are designed for pruning a specific structure, such as filter or block structures without jointly pruning heterogeneous structures. In this paper, we propose an effective structured pruning approach that jointly prunes filters as well as other structures in an end-to-end manner. To accomplish this, we first introduce a soft mask to scale the output of these structures by defining a new objective function with sparsity regularization to align the output of baseline and network with this mask. We then effectively solve the optimization problem by generative adversarial learning (GAL), which learns a sparse soft mask in a label-free and an end-to-end manner. By forcing more scaling factors in the soft mask to zero, the fast iterative shrinkage-thresholding algorithm (FISTA) can be leveraged to fast and reliably remove the corresponding structures. Extensive experiments demonstrate the effectiveness of GAL on different datasets, including MNIST, CIFAR-10 and ImageNet ILSVRC 2012. For example, on ImageNet ILSVRC 2012, the pruned ResNet-50 achieves 10.88\% Top-5 error and results in a factor of 3.7x speedup. This significantly outperforms state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.09291](http://arxiv.org/abs/1903.09291)

##### PDF
[http://arxiv.org/pdf/1903.09291](http://arxiv.org/pdf/1903.09291)

