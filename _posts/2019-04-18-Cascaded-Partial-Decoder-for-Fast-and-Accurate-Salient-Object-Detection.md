---
layout: post
title: "Cascaded Partial Decoder for Fast and Accurate Salient Object Detection"
date: 2019-04-18 12:53:30
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection CNN Detection
author: Zhe Wu, Li Su, Qingming Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Existing state-of-the-art salient object detection networks rely on aggregating multi-level features of pre-trained convolutional neural networks (CNNs). Compared to high-level features, low-level features contribute less to performance but cost more computations because of their larger spatial resolutions. In this paper, we propose a novel Cascaded Partial Decoder (CPD) framework for fast and accurate salient object detection. On the one hand, the framework constructs partial decoder which discards larger resolution features of shallower layers for acceleration. On the other hand, we observe that integrating features of deeper layers obtain relatively precise saliency map. Therefore we directly utilize generated saliency map to refine the features of backbone network. This strategy efficiently suppresses distractors in the features and significantly improves their representation ability. Experiments conducted on five benchmark datasets exhibit that the proposed model not only achieves state-of-the-art performance but also runs much faster than existing models. Besides, the proposed framework is further applied to improve existing multi-level feature aggregation models and significantly improve their efficiency and accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08739](http://arxiv.org/abs/1904.08739)

##### PDF
[http://arxiv.org/pdf/1904.08739](http://arxiv.org/pdf/1904.08739)

