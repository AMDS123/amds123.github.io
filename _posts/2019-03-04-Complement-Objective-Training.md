---
layout: post
title: "Complement Objective Training"
date: 2019-03-04 11:35:27
categories: arXiv_CV
tags: arXiv_CV Adversarial Classification
author: Hao-Yun Chen, Pei-Hsin Wang, Chun-Hao Liu, Shih-Chieh Chang, Jia-Yu Pan, Yu-Ting Chen, Wei Wei, Da-Cheng Juan
mathjax: true
---

* content
{:toc}

##### Abstract
Learning with a primary objective, such as softmax cross entropy for classification and sequence generation, has been the norm for training deep neural networks for years. Although being a widely-adopted approach, using cross entropy as the primary objective exploits mostly the information from the ground-truth class for maximizing data likelihood, and largely ignores information from the complement (incorrect) classes. We argue that, in addition to the primary objective, training also using a complement objective that leverages information from the complement classes can be effective in improving model performance. This motivates us to study a new training paradigm that maximizes the likelihood of the groundtruth class while neutralizing the probabilities of the complement classes. We conduct extensive experiments on multiple tasks ranging from computer vision to natural language understanding. The experimental results confirm that, compared to the conventional training with just one primary objective, training also with the complement objective further improves the performance of the state-of-the-art models across all tasks. In addition to the accuracy improvement, we also show that models trained with both primary and complement objectives are more robust to single-step adversarial attacks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01182](http://arxiv.org/abs/1903.01182)

##### PDF
[http://arxiv.org/pdf/1903.01182](http://arxiv.org/pdf/1903.01182)

