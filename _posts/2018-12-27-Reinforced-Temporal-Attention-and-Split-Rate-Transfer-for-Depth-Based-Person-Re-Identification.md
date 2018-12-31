---
layout: post
title: "Reinforced Temporal Attention and Split-Rate Transfer for Depth-Based Person Re-Identification"
date: 2018-12-27 01:06:54
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification Reinforcement_Learning CNN Recognition
author: Nikolaos Karianakis, Zicheng Liu, Yinpeng Chen, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of person re-identification from commodity depth sensors. One challenge for depth-based recognition is data scarcity. Our first contribution addresses this problem by introducing split-rate RGB-to-Depth transfer, which leverages large RGB datasets more effectively than popular fine-tuning approaches. Our transfer scheme is based on the observation that the model parameters at the bottom layers of a deep convolutional neural network can be directly shared between RGB and depth data while the remaining layers need to be fine-tuned rapidly. Our second contribution enhances re-identification for video by implementing temporal attention as a Bernoulli-Sigmoid unit acting upon frame-level features. Since this unit is stochastic, the temporal attention parameters are trained using reinforcement learning. Extensive experiments validate the accuracy of our method in person re-identification from depth sequences. Finally, in a scenario where subjects wear unseen clothes, we show large performance gains compared to a state-of-the-art model which relies on RGB data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1705.09882](http://arxiv.org/abs/1705.09882)

##### PDF
[http://arxiv.org/pdf/1705.09882](http://arxiv.org/pdf/1705.09882)

