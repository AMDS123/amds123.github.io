---
layout: post
title: "Multi-source weak supervision for saliency detection"
date: 2019-04-01 05:19:19
categories: arXiv_CV
tags: arXiv_CV Salient Attention Weakly_Supervised Caption Classification Prediction Detection
author: Yu Zeng, Yunzhi Zhuge, Huchuan Lu, Lihe Zhang, Mingyang Qian, Yizhou Yu
mathjax: true
---

* content
{:toc}

##### Abstract
The high cost of pixel-level annotations makes it appealing to train saliency detection models with weak supervision. However, a single weak supervision source usually does not contain enough information to train a well-performing model. To this end, we propose a unified framework to train saliency detection models with diverse weak supervision sources. In this paper, we use category labels, captions, and unlabelled data for training, yet other supervision sources can also be plugged into this flexible framework. We design a classification network (CNet) and a caption generation network (PNet), which learn to predict object categories and generate captions, respectively, meanwhile highlight the most important regions for corresponding tasks. An attention transfer loss is designed to transmit supervision signal between networks, such that the network designed to be trained with one supervision source can benefit from another. An attention coherence loss is defined on unlabelled data to encourage the networks to detect generally salient regions instead of task-specific regions. We use CNet and PNet to generate pixel-level pseudo labels to train a saliency prediction network (SNet). During the testing phases, we only need SNet to predict saliency maps. Experiments demonstrate the performance of our method compares favourably against unsupervised and weakly supervised methods and even some supervised methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00566](http://arxiv.org/abs/1904.00566)

##### PDF
[http://arxiv.org/pdf/1904.00566](http://arxiv.org/pdf/1904.00566)

