---
layout: post
title: "Learning Deep Multi-Level Similarity for Thermal Infrared Object Tracking"
date: 2019-06-09 05:09:05
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking
author: Qiao Liu, Xin Li, Zhenyu He, Nana Fan, Di Yuan, Hongpeng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Existing deep Thermal InfraRed (TIR) trackers only use semantic features to describe the TIR object, which lack the sufficient discriminative capacity for handling distractors. This becomes worse when the feature extraction network is only trained on RGB images.To address this issue, we propose a multi-level similarity model under a Siamese framework for robust TIR object tracking. Specifically, we compute different pattern similarities on two convolutional layers using the proposed multi-level similarity network. One of them focuses on the global semantic similarity and the other computes the local structural similarity of the TIR object. These two similarities complement each other and hence enhance the discriminative capacity of the network for handling distractors. In addition, we design a simple while effective relative entropy based ensemble subnetwork to integrate the semantic and structural similarities. This subnetwork can adaptive learn the weights of the semantic and structural similarities at the training stage. To further enhance the discriminative capacity of the tracker, we construct the first large scale TIR video sequence dataset for training the proposed model. The proposed TIR dataset not only benefits the training for TIR tracking but also can be applied to numerous TIR vision tasks. Extensive experimental results on the VOT-TIR2015 and VOT-TIR2017 benchmarks demonstrate that the proposed algorithm performs favorably against the state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03568](http://arxiv.org/abs/1906.03568)

##### PDF
[http://arxiv.org/pdf/1906.03568](http://arxiv.org/pdf/1906.03568)

