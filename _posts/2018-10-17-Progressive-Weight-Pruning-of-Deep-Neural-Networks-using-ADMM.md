---
layout: post
title: "Progressive Weight Pruning of Deep Neural Networks using ADMM"
date: 2018-10-17 03:51:38
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Shaokai Ye, Tianyun Zhang, Kaiqi Zhang, Jiayu Li, Kaidi Xu, Yunfei Yang, Fuxun Yu, Jian Tang, Makan Fardad, Sijia Liu, Xiang Chen, Xue Lin, Yanzhi Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) although achieving human-level performance in many domains, have very large model size that hinders their broader applications on edge computing devices. Extensive research work have been conducted on DNN model compression or pruning. However, most of the previous work took heuristic approaches. This work proposes a progressive weight pruning approach based on ADMM (Alternating Direction Method of Multipliers), a powerful technique to deal with non-convex optimization problems with potentially combinatorial constraints. Motivated by dynamic programming, the proposed method reaches extremely high pruning rate by using partial prunings with moderate pruning rates. Therefore, it resolves the accuracy degradation and long convergence time problems when pursuing extremely high pruning ratios. It achieves up to 34 times pruning rate for ImageNet dataset and 167 times pruning rate for MNIST dataset, significantly higher than those reached by the literature work. Under the same number of epochs, the proposed method also achieves faster convergence and higher compression rates. The codes and pruned DNN models are released in the link bit.ly/2zxdlss

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.07378](http://arxiv.org/abs/1810.07378)

##### PDF
[http://arxiv.org/pdf/1810.07378](http://arxiv.org/pdf/1810.07378)

