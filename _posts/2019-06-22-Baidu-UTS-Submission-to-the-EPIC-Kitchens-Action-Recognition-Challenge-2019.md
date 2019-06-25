---
layout: post
title: "Baidu-UTS Submission to the EPIC-Kitchens Action Recognition Challenge 2019"
date: 2019-06-22 03:45:41
categories: arXiv_CV
tags: arXiv_CV Object_Detection Action_Recognition CNN Prediction Detection Recognition
author: Xiaohan Wang, Yu Wu, Linchao Zhu, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this report, we present the Baidu-UTS submission to the EPIC-Kitchens Action Recognition Challenge in CVPR 2019. This is the winning solution to this challenge. In this task, the goal is to predict verbs, nouns, and actions from the vocabulary for each video segment. The EPIC-Kitchens dataset contains various small objects, intense motion blur, and occlusions. It is challenging to locate and recognize the object that an actor interacts with. To address these problems, we utilize object detection features to guide the training of 3D Convolutional Neural Networks (CNN), which can significantly improve the accuracy of noun prediction. Specifically, we introduce a Gated Feature Aggregator module to learn from the clip feature and the object feature. This module can strengthen the interaction between the two kinds of activations and avoid gradient exploding. Experimental results demonstrate our approach outperforms other methods on both seen and unseen test set.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09383](http://arxiv.org/abs/1906.09383)

##### PDF
[http://arxiv.org/pdf/1906.09383](http://arxiv.org/pdf/1906.09383)

