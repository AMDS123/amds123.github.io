---
layout: post
title: "StructADMM: A Systematic, High-Efficiency Framework of Structured Weight Pruning for DNNs"
date: 2019-03-27 02:37:46
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Gradient_Descent
author: Tianyun Zhang, Shaokai Ye, Kaiqi Zhang, Xiaolong Ma, Ning Liu, Linfeng Zhang, Jian Tang, Kaisheng Ma, Xue Lin, Makan Fardad, Yanzhi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Weight pruning methods of DNNs have been demonstrated to achieve a good model pruning rate without loss of accuracy, thereby alleviating the significant computation/storage requirements of large-scale DNNs. Structured weight pruning methods have been proposed to overcome the limitation of irregular network structure and demonstrated actual GPU acceleration. However, in prior work the pruning rate (degree of sparsity) and GPU acceleration are limited (to less than 50%) when accuracy needs to be maintained. In this work,we overcome these limitations by proposing a unified, systematic framework of structured weight pruning for DNNs. It is a framework that can be used to induce different types of structured sparsity, such as filter-wise, channel-wise, and shape-wise sparsity, as well non-structured sparsity. The proposed framework incorporates stochastic gradient descent with ADMM, and can be understood as a dynamic regularization method in which the regularization target is analytically updated in each iteration. Without loss of accuracy on the AlexNet model, we achieve 2.58X and 3.65X average measured speedup on two GPUs, clearly outperforming the prior work. The average speedups reach 3.15X and 8.52X when allowing a moderate ac-curacy loss of 2%. In this case the model compression for convolutional layers is 15.0X, corresponding to 11.93X measured CPU speedup. Our experiments on ResNet model and on other data sets like UCF101 and CIFAR-10 demonstrate the consistently higher performance of our framework.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.11091](http://arxiv.org/abs/1807.11091)

##### PDF
[http://arxiv.org/pdf/1807.11091](http://arxiv.org/pdf/1807.11091)

