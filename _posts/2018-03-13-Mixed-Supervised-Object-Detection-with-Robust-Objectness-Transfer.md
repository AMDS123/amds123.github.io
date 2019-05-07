---
layout: post
title: "Mixed Supervised Object Detection with Robust Objectness Transfer"
date: 2018-03-13 11:15:50
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge Weakly_Supervised Detection
author: Yan Li, Junge Zhang, Kaiqi Huang, Jianguo Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider the problem of leveraging existing fully labeled categories to improve the weakly supervised detection (WSD) of new object categories, which we refer to as mixed supervised detection (MSD). Different from previous MSD methods that directly transfer the pre-trained object detectors from existing categories to new categories, we propose a more reasonable and robust objectness transfer approach for MSD. In our framework, we first learn domain-invariant objectness knowledge from the existing fully labeled categories. The knowledge is modeled based on invariant features that are robust to the distribution discrepancy between the existing categories and new categories; therefore the resulting knowledge would generalize well to new categories and could assist detection models to reject distractors (e.g., object parts) in weakly labeled images of new categories. Under the guidance of learned objectness knowledge, we utilize multiple instance learning (MIL) to model the concepts of both objects and distractors and to further improve the ability of rejecting distractors in weakly labeled images. Our robust objectness transfer approach outperforms the existing MSD methods, and achieves state-of-the-art results on the challenging ILSVRC2013 detection dataset and the PASCAL VOC datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.09778](https://arxiv.org/abs/1802.09778)

##### PDF
[https://arxiv.org/pdf/1802.09778](https://arxiv.org/pdf/1802.09778)

