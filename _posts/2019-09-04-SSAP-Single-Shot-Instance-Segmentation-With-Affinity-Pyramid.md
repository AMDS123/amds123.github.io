---
layout: post
title: "SSAP: Single-Shot Instance Segmentation With Affinity Pyramid"
date: 2019-09-04 08:33:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Semantic_Segmentation Inference Prediction
author: Naiyu Gao, Yanhu Shan, Yupei Wang, Xin Zhao, Yinan Yu, Ming Yang, Kaiqi Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, proposal-free instance segmentation has received increasing attention due to its concise and efficient pipeline. Generally, proposal-free methods generate instance-agnostic semantic segmentation labels and instance-aware features to group pixels into different object instances. However, previous methods mostly employ separate modules for these two sub-tasks and require multiple passes for inference. We argue that treating these two sub-tasks separately is suboptimal. In fact, employing multiple separate modules significantly reduces the potential for application. The mutual benefits between the two complementary sub-tasks are also unexplored. To this end, this work proposes a single-shot proposal-free instance segmentation method that requires only one single pass for prediction. Our method is based on a pixel-pair affinity pyramid, which computes the probability that two pixels belong to the same instance in a hierarchical manner. The affinity pyramid can also be jointly learned with the semantic class labeling and achieve mutual benefits. Moreover, incorporating with the learned affinity pyramid, a novel cascaded graph partition module is presented to sequentially generate instances from coarse to fine. Unlike previous time-consuming graph partition methods, this module achieves $5\times$ speedup and 9% relative improvement on Average-Precision (AP). Our approach achieves state-of-the-art results on the challenging Cityscapes dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.01616](http://arxiv.org/abs/1909.01616)

##### PDF
[http://arxiv.org/pdf/1909.01616](http://arxiv.org/pdf/1909.01616)

