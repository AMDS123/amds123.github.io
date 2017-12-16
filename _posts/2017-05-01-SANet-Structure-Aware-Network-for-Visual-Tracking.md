---
layout: post
title: "SANet: Structure-Aware Network for Visual Tracking"
date: 2017-05-01 17:43:07
categories: arXiv_CV
tags: arXiv_CV Tracking CNN RNN Classification
author: Heng Fan, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural network (CNN) has drawn increasing interest in visual tracking owing to its powerfulness in feature extraction. Most existing CNN-based trackers treat tracking as a classification problem. However, these trackers are sensitive to similar distractors because their CNN models mainly focus on inter-class classification. To address this problem, we use self-structure information of object to distinguish it from distractors. Specifically, we utilize recurrent neural network (RNN) to model object structure, and incorporate it into CNN to improve its robustness to similar distractors. Considering that convolutional layers in different levels characterize the object from different perspectives, we use multiple RNNs to model object structure in different levels respectively. Extensive experiments on three benchmarks, OTB100, TC-128 and VOT2015, show that the proposed algorithm outperforms other methods. Code is released at this http URL

##### Abstract (translated by Google)
卷积神经网络（CNN）由于其强大的特征提取功能而引起了人们对视觉追踪的兴趣。大多数现有的基于CNN的跟踪器将跟踪视为分类问题。然而，这些跟踪器对于类似的分心者很敏感，因为他们的CNN模型主要集中在类间分类上。为了解决这个问题，我们使用对象的自我结构信息来区分它与分心。具体而言，我们利用递归神经网络（RNN）对对象结构进行建模，并将其纳入到CNN中，以提​​高其对类似干扰者的鲁棒性。考虑到不同层次的卷积层从不同角度刻画了对象，我们分别使用多个RNN对不同层次的对象结构进行建模。在三个基准OTB100，TC-128和VOT2015上的大量实验表明，该算法优于其他方法。代码在这个http URL上发布

##### URL
[https://arxiv.org/abs/1611.06878](https://arxiv.org/abs/1611.06878)

##### PDF
[https://arxiv.org/pdf/1611.06878](https://arxiv.org/pdf/1611.06878)

