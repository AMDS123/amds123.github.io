---
layout: post
title: "A Structured Model For Action Detection"
date: 2019-06-05 17:55:42
categories: arXiv_CV
tags: arXiv_CV Video_Caption Knowledge Tracking CNN Optimization Detection Recognition
author: Yubo Zhang, Pavel Tokmakov, Martial Hebert, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
A dominant paradigm for learning-based approaches in computer vision is training generic models, such as ResNet for image recognition, or I3D for video understanding, on large datasets and allowing them to discover the optimal representation for the problem at hand. While this is an obviously attractive approach, it is not applicable in all scenarios. We claim that action detection is one such challenging problem - the models that need to be trained are large, and labeled data is expensive to obtain. To address this limitation, we propose to incorporate domain knowledge into the structure of the model, simplifying optimization. In particular, we augment a standard I3D network with a tracking module to aggregate long term motion patterns, and use a graph convolutional network to reason about interactions between actors and objects. Evaluated on the challenging AVA dataset, the proposed approach improves over the I3D baseline by 5.5% mAP and over the state-of-the-art by 4.8% mAP.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03544](http://arxiv.org/abs/1812.03544)

##### PDF
[http://arxiv.org/pdf/1812.03544](http://arxiv.org/pdf/1812.03544)

