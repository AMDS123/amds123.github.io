---
layout: post
title: "Non-rigid Object Tracking via Deep Multi-scale Spatial-temporal Discriminative Saliency Maps"
date: 2019-02-28 02:18:06
categories: arXiv_CV
tags: arXiv_CV Salient Tracking CNN Object_Tracking Classification Detection
author: Pingping Zhang, Wei Liu, Dong Wang, Yinjie Lei, Hongyu Wang, Chunhua Shen, Huchuan Lu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel effective non-rigid object tracking framework based on the spatial-temporal consistent saliency detection. In contrast to most existing trackers that utilize a bounding box to specify the tracked target, the proposed framework can extract accurate regions of the target as tracking outputs. It achieves a better description of the non-rigid objects and reduces the background pollution for the tracking model. Furthermore, our model has several unique features. First, a tailored fully convolutional neural network (TFCN) is developed to model the local saliency prior for a given image region, which not only provides the pixel-wise outputs but also integrates the semantic information. Second, a novel multi-scale multi-region mechanism is proposed to generate local saliency maps that effectively consider visual perceptions with different spatial layouts and scale variations. Subsequently, local saliency maps are fused via a weighted entropy method, resulting in a final discriminative saliency map. Finally, we present a non-rigid object tracking algorithm based on the predicted saliency maps. By utilizing a spatial-temporal consistent saliency map (STCSM), we conduct target-background classification and use a simple fine-tuning scheme for online updating. Extensive experiments demonstrate that the proposed algorithm achieves competitive performance in both saliency detection and visual tracking, especially outperforming other related trackers on the non-rigid object tracking datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.07957](http://arxiv.org/abs/1802.07957)

##### PDF
[http://arxiv.org/pdf/1802.07957](http://arxiv.org/pdf/1802.07957)

