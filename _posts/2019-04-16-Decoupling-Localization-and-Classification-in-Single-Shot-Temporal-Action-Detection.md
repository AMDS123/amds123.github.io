---
layout: post
title: "Decoupling Localization and Classification in Single Shot Temporal Action Detection"
date: 2019-04-16 03:50:57
categories: arXiv_CV
tags: arXiv_CV Classification Detection
author: Yupan Huang, Qi Dai, Yutong Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Video temporal action detection aims to temporally localize and recognize the action in untrimmed videos. Existing one-stage approaches mostly focus on unifying two subtasks, i.e., localization of action proposals and classification of each proposal through a fully shared backbone. However, such design of encapsulating all components of two subtasks in one single network might restrict the training by ignoring the specialized characteristic of each subtask. In this paper, we propose a novel Decoupled Single Shot temporal Action Detection (Decouple-SSAD) method to mitigate such problem by decoupling the localization and classification in a one-stage scheme. Particularly, two separate branches are designed in parallel to enable each component to own representations privately for accurate localization or classification. Each branch produces a set of action anchor layers by applying deconvolution to the feature maps of the main stream. Each branch produces a set of feature maps by applying deconvolution to the feature maps of the main stream. High-level semantic information from deeper layers is thus incorporated to enhance the feature representations. We conduct extensive experiments on THUMOS14 dataset and demonstrate superior performance over state-of-the-art methods. Our code is available online.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07442](http://arxiv.org/abs/1904.07442)

##### PDF
[http://arxiv.org/pdf/1904.07442](http://arxiv.org/pdf/1904.07442)

