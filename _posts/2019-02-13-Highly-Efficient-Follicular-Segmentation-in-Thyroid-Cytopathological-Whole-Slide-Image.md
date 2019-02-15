---
layout: post
title: "Highly Efficient Follicular Segmentation in Thyroid Cytopathological Whole Slide Image"
date: 2019-02-13 10:16:54
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Siyan Tao, Yao Guo, Chuang Zhu, Huang Chen, Yue Zhang, Jie Yang, Jun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel method for highly efficient follicular segmentation of thyroid cytopathological WSIs. Firstly, we propose a hybrid segmentation architecture, which integrates a classifier into Deeplab V3 by adding a branch. A large amount of the WSI segmentation time is saved by skipping the irrelevant areas using the classification branch. Secondly, we merge the low scale fine features into the original atrous spatial pyramid pooling (ASPP) in Deeplab V3 to accurately represent the details in cytopathological images. Thirdly, our hybrid model is trained by a criterion-oriented adaptive loss function, which leads the model converging much faster. Experimental results on a collection of thyroid patches demonstrate that the proposed model reaches 80.9% on the segmentation accuracy. Besides, 93% time is reduced for the WSI segmentation by using our proposed method, and the WSI-level accuracy achieves 53.4%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05431](http://arxiv.org/abs/1902.05431)

##### PDF
[http://arxiv.org/pdf/1902.05431](http://arxiv.org/pdf/1902.05431)

