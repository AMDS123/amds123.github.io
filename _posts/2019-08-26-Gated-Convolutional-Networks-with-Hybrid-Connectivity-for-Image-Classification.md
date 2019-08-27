---
layout: post
title: "Gated Convolutional Networks with Hybrid Connectivity for Image Classification"
date: 2019-08-26 14:13:21
categories: arXiv_CV
tags: arXiv_CV Attention CNN Image_Classification Classification
author: Chuanguang Yang, Zhulin An, Hui Zhu, Xiaolong Hu, Kaiqiang Xu, Chao Li, Boyu Diao, Yongjun Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We design a highly efficient architecture called Gated Convolutional Network with Hybrid Connectivity (HCGNet), which is equipped with the combination of local residual and global dense connectivity to enjoy their individual superiorities as well as attention-based gate mechanism to assist feature recalibration. To adapt our hybrid connectivity, we further propose a novel module which includes a squeeze cell for obtaining the compact features from input and then a multi-scale excitation cell attached an update gate to model the global context features for capturing long-range dependency based on multi-scale information. We also locate a forget gate on residual connectivity to decay the reused features, which can be aggergated with newly global context features to form the output that can facilitate effective feature exploration as well as re-exploitation to some extent. Moreover, the number of our proposed modules under dense connectivity can quite fewer than classical DenseNet thus reducing considerable redundancy but with empirically better performance. On CIFAR-10/100 datasets, HCGNets significantly outperform state-of-the-art both human-designed and auto-searched networks with much fewer parameters. It can also consistently obtain better performance and interpretability than widely applied networks in practice on ImageNet dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09699](http://arxiv.org/abs/1908.09699)

##### PDF
[http://arxiv.org/pdf/1908.09699](http://arxiv.org/pdf/1908.09699)

