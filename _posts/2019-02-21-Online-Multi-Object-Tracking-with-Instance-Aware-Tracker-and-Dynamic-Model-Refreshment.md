---
layout: post
title: "Online Multi-Object Tracking with Instance-Aware Tracker and Dynamic Model Refreshment"
date: 2019-02-21 19:50:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking CNN Object_Tracking Detection
author: Peng Chu, Heng Fan, Chiu C Tan, Haibin Ling
mathjax: true
---

* content
{:toc}

##### Abstract
Recent progresses in model-free single object tracking (SOT) algorithms have largely inspired applying SOT to \emph{multi-object tracking} (MOT) to improve the robustness as well as relieving dependency on external detector. However, SOT algorithms are generally designed for distinguishing a target from its environment, and hence meet problems when a target is spatially mixed with similar objects as observed frequently in MOT. To address this issue, in this paper we propose an instance-aware tracker to integrate SOT techniques for MOT by encoding awareness both within and between target models. In particular, we construct each target model by fusing information for distinguishing target both from background and other instances (tracking targets). To conserve uniqueness of all target models, our instance-aware tracker considers response maps from all target models and assigns spatial locations exclusively to optimize the overall accuracy. Another contribution we make is a dynamic model refreshing strategy learned by a convolutional neural network. This strategy helps to eliminate initialization noise as well as to adapt to the variation of target size and appearance. To show the effectiveness of the proposed approach, it is evaluated on the popular MOT15 and MOT16 challenge benchmarks. On both benchmarks, our approach achieves the best overall performances in comparison with published results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08231](http://arxiv.org/abs/1902.08231)

##### PDF
[http://arxiv.org/pdf/1902.08231](http://arxiv.org/pdf/1902.08231)

