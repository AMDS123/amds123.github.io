---
layout: post
title: "Learning Group Convolution for Efficient Inference"
date: 2019-04-06 19:36:46
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Inference
author: Ruizhe Zhao, Wayne Luk
mathjax: true
---

* content
{:toc}

##### Abstract
Efficient inference of Convolutional Neural Networks is a thriving topic recently. It is desirable to achieve the maximal test accuracy under given inference budget constraints when deploying a pre-trained model. Network pruning is a commonly used technique while it may produce irregular sparse models that can hardly gain actual speed-up. Group convolution is a promising pruning target due to its regular structure; however, incorporating such structure into the pruning procedure is challenging. It is because structural constraints are hard to describe and can make pruning intractable to solve. The need for configuring sparsity that maximises test accuracy also increases difficulty. 
 This paper presents an efficient method to address this challenge. We formulate group convolution pruning as finding the optimal channel permutation to impose structural constraints and solve it efficiently by heuristics. We also apply local search to exploring the sparsity configuration that maximises test accuracy. Compared to prior work, results show that our method produces competitive group convolution models for various tasks within a shorter pruning period and enables rapid model sparsity exploration subject to inference budget constraints

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09341](http://arxiv.org/abs/1811.09341)

##### PDF
[http://arxiv.org/pdf/1811.09341](http://arxiv.org/pdf/1811.09341)

