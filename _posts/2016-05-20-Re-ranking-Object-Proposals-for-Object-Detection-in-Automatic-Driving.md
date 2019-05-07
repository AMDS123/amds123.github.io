---
layout: post
title: "Re-ranking Object Proposals for Object Detection in Automatic Driving"
date: 2016-05-20 01:45:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Detection
author: Zhun Zhong, Mingyi Lei, Shaozi Li, Jianping Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection often suffers from a plenty of bootless proposals, selecting high quality proposals remains a great challenge. In this paper, we propose a semantic, class-specific approach to re-rank object proposals, which can consistently improve the recall performance even with less proposals. We first extract features for each proposal including semantic segmentation, stereo information, contextual information, CNN-based objectness and low-level cue, and then score them using class-specific weights learnt by Structured SVM. The advantages of the proposed model are twofold: 1) it can be easily merged to existing generators with few computational costs, and 2) it can achieve high recall rate uner strict critical even using less proposals. Experimental evaluation on the KITTI benchmark demonstrates that our approach significantly improves existing popular generators on recall performance. Moreover, in the experiment conducted for object detection, even with 1,500 proposals, our approach can still have higher average precision (AP) than baselines with 5,000 proposals.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1605.05904](https://arxiv.org/abs/1605.05904)

##### PDF
[https://arxiv.org/pdf/1605.05904](https://arxiv.org/pdf/1605.05904)

