---
layout: post
title: "Unsupervised Event-based Learning of Optical Flow, Depth, and Egomotion"
date: 2018-12-19 18:50:54
categories: arXiv_CV
tags: arXiv_CV
author: Alex Zihao Zhu, Liangzhe Yuan, Kenneth Chaney, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a novel framework for unsupervised learning for event cameras that learns motion information from only the event stream. In particular, we propose an input representation of the events in the form of a discretized volume that maintains the temporal distribution of the events, which we pass through a neural network to predict the motion of the events. This motion is used to attempt to remove any motion blur in the event image. We then propose a loss function applied to the motion compensated event image that measures the motion blur in this image. We train two networks with this framework, one to predict optical flow, and one to predict egomotion and depths, and evaluate these networks on the Multi Vehicle Stereo Event Camera dataset, along with qualitative results from a variety of different scenes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08156](http://arxiv.org/abs/1812.08156)

##### PDF
[http://arxiv.org/pdf/1812.08156](http://arxiv.org/pdf/1812.08156)

