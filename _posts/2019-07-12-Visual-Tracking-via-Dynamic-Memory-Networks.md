---
layout: post
title: "Visual Tracking via Dynamic Memory Networks"
date: 2019-07-12 14:07:24
categories: arXiv_CV
tags: arXiv_CV Dynamic_Memory_Network Attention Tracking RNN Classification Detection Memory_Networks
author: Tianyu Yang, Antoni B. Chan
mathjax: true
---

* content
{:toc}

##### Abstract
Template-matching methods for visual tracking have gained popularity recently due to their good performance and fast speed. However, they lack effective ways to adapt to changes in the target object's appearance, making their tracking accuracy still far from state-of-the-art. In this paper, we propose a dynamic memory network to adapt the template to the target's appearance variations during tracking. The reading and writing process of the external memory is controlled by an LSTM network with the search feature map as input. A spatial attention mechanism is applied to concentrate the LSTM input on the potential target as the location of the target is at first unknown. To prevent aggressive model adaptivity, we apply gated residual template learning to control the amount of retrieved memory that is used to combine with the initial template. In order to alleviate the drift problem, we also design a "negative" memory unit that stores templates for distractors, which are used to cancel out wrong responses from the object template. To further boost the tracking performance, an auxiliary classification loss is added after the feature extractor part. Unlike tracking-by-detection methods where the object's information is maintained by the weight parameters of neural networks, which requires expensive online fine-tuning to be adaptable, our tracker runs completely feed-forward and adapts to the target's appearance changes by updating the external memory. Moreover, the capacity of our model is not determined by the network size as with other trackers --- the capacity can be easily enlarged as the memory requirements of a task increase, which is favorable for memorizing long-term object information. Extensive experiments on the OTB and VOT datasets demonstrate that our trackers perform favorably against state-of-the-art tracking methods while retaining real-time speed.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07613](http://arxiv.org/abs/1907.07613)

##### PDF
[http://arxiv.org/pdf/1907.07613](http://arxiv.org/pdf/1907.07613)

