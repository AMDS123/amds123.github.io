---
layout: post
title: "BIRNet: Brain Image Registration Using Dual-Supervised Fully Convolutional Networks"
date: 2018-02-13 15:49:34
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Jingfan Fan, Xiaohuan Cao, Pew-Thian Yap, Dinggang Shen
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a deep learning approach for image registration by predicting deformation from image appearance. Since obtaining ground-truth deformation fields for training can be challenging, we design a fully convolutional network that is subject to dual-guidance: (1) Coarse guidance using deformation fields obtained by an existing registration method; and (2) Fine guidance using image similarity. The latter guidance helps avoid overly relying on the supervision from the training deformation fields, which could be inaccurate. For effective training, we further improve the deep convolutional network with gap filling, hierarchical loss, and multi-source strategies. Experiments on a variety of datasets show promising registration accuracy and efficiency compared with state-of-the-art methods.

##### Abstract (translated by Google)
在本文中，我们提出了一种通过预测图像外观变形来进行图像配准的深度学习方法。由于获得用于训练的地面真值变形场可能具有挑战性，因此我们设计了完全卷积网络，其受到双向引导：（1）使用通过现有配准方法获得的变形场的粗略引导;和（2）使用图像相似性的精细引导。后者的指导有助于避免过度依赖训练变形领域的监督，这可能是不准确的。为了进行有效的培训，我们进一步完善了填补空缺，分层损失和多源战略的深度卷积网络。与最先进的方法相比，各种数据集上的实验显示出有前途的配准精度和效率。

##### URL
[http://arxiv.org/abs/1802.04692](http://arxiv.org/abs/1802.04692)

##### PDF
[http://arxiv.org/pdf/1802.04692](http://arxiv.org/pdf/1802.04692)

