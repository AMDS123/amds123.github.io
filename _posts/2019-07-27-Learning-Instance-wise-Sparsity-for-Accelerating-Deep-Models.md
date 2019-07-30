---
layout: post
title: "Learning Instance-wise Sparsity for Accelerating Deep Models"
date: 2019-07-27 02:59:38
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse CNN Inference
author: Chuanjian Liu, Yunhe Wang, Kai Han, Chunjing Xu, Chang Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Exploring deep convolutional neural networks of high efficiency and low memory usage is very essential for a wide variety of machine learning tasks. Most of existing approaches used to accelerate deep models by manipulating parameters or filters without data, e.g., pruning and decomposition. In contrast, we study this problem from a different perspective by respecting the difference between data. An instance-wise feature pruning is developed by identifying informative features for different instances. Specifically, by investigating a feature decay regularization, we expect intermediate feature maps of each instance in deep neural networks to be sparse while preserving the overall network performance. During online inference, subtle features of input images extracted by intermediate layers of a well-trained neural network can be eliminated to accelerate the subsequent calculations. We further take coefficient of variation as a measure to select the layers that are appropriate for acceleration. Extensive experiments conducted on benchmark datasets and networks demonstrate the effectiveness of the proposed method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11840](http://arxiv.org/abs/1907.11840)

##### PDF
[http://arxiv.org/pdf/1907.11840](http://arxiv.org/pdf/1907.11840)

