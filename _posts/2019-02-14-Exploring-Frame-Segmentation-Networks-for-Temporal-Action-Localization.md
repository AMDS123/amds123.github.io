---
layout: post
title: "Exploring Frame Segmentation Networks for Temporal Action Localization"
date: 2019-02-14 16:46:34
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Prediction
author: Ke Yang, Xiaolong Shen, Peng Qiao, Shijie Li, Dongsheng Li, Yong Dou
mathjax: true
---

* content
{:toc}

##### Abstract
Temporal action localization is an important task of computer vision. Though many methods have been proposed, it still remains an open question how to predict the temporal location of action segments precisely. Most state-of-the-art works train action classifiers on video segments pre-determined by action proposal. However, recent work found that a desirable model should move beyond segment-level and make dense predictions at a fine granularity in time to determine precise temporal boundaries. In this paper, we propose a Frame Segmentation Network (FSN) that places a temporal CNN on top of the 2D spatial CNNs. Spatial CNNs are responsible for abstracting semantics in spatial dimension while temporal CNN is responsible for introducing temporal context information and performing dense predictions. The proposed FSN can make dense predictions at frame-level for a video clip using both spatial and temporal context information. FSN is trained in an end-to-end manner, so the model can be optimized in spatial and temporal domain jointly. We also adapt FSN to use it in weakly supervised scenario (WFSN), where only video level labels are provided when training. Experiment results on public dataset show that FSN achieves superior performance in both frame-level action localization and temporal action localization.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05488](http://arxiv.org/abs/1902.05488)

##### PDF
[http://arxiv.org/pdf/1902.05488](http://arxiv.org/pdf/1902.05488)

