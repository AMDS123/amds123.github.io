---
layout: post
title: "Weakly Supervised Instance Segmentation Using Hybrid Network"
date: 2018-12-12 07:12:50
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Weakly_Supervised
author: Shisha Liao, Yongqing Sun, Chenqiang Gao, Pranav Shenoy K P, Song Mu, Jun Shimamura, Atsushi Sagata
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly-supervised instance segmentation, which could greatly save labor and time cost of pixel mask annotation, has attracted increasing attention in recent years. The commonly used pipeline firstly utilizes conventional image segmentation methods to automatically generate initial masks and then use them to train an off-the-shelf segmentation network in an iterative way. However, the initial generated masks usually contains a notable proportion of invalid masks which are mainly caused by small object instances. Directly using these initial masks to train segmentation model is harmful for the performance. To address this problem, we propose a hybrid network in this paper. In our architecture, there is a principle segmentation network which is used to handle the normal samples with valid generated masks. In addition, a complementary branch is added to handle the small and dim objects without valid masks. Experimental results indicate that our method can achieve significantly performance improvement both on the small object instances and large ones, and outperforms all state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04831](http://arxiv.org/abs/1812.04831)

##### PDF
[http://arxiv.org/pdf/1812.04831](http://arxiv.org/pdf/1812.04831)

