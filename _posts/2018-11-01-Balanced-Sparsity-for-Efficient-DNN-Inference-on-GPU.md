---
layout: post
title: "Balanced Sparsity for Efficient DNN Inference on GPU"
date: 2018-11-01 03:30:51
categories: arXiv_CV
tags: arXiv_CV Sparse Inference Deep_Learning
author: Zhuliang Yao, Shijie Cao, Wencong Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
In trained deep neural networks, unstructured pruning can reduce redundant weights to lower storage cost. However, it requires the customization of hardwares to speed up practical inference. Another trend accelerates sparse model inference on general-purpose hardwares by adopting coarse-grained sparsity to prune or regularize consecutive weights for efficient computation. But this method often sacrifices model accuracy. In this paper, we propose a novel fine-grained sparsity approach, balanced sparsity, to achieve high model accuracy with commercial hardwares efficiently. Our approach adapts to high parallelism property of GPU, showing incredible potential for sparsity in the widely deployment of deep learning services. Experiment results show that balanced sparsity achieves up to 3.1x practical speedup for model inference on GPU, while retains the same high model accuracy as fine-grained sparsity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00206](http://arxiv.org/abs/1811.00206)

##### PDF
[http://arxiv.org/pdf/1811.00206](http://arxiv.org/pdf/1811.00206)

