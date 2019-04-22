---
layout: post
title: "Weakly Supervised Adversarial Domain Adaptation for Semantic Segmentation in Urban Scenes"
date: 2019-04-19 06:30:36
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Weakly_Supervised CNN Semantic_Segmentation Detection
author: Qi Wang, Junyu Gao, Xuelong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic segmentation, a pixel-level vision task, is developed rapidly by using convolutional neural networks (CNNs). Training CNNs requires a large amount of labeled data, but manually annotating data is difficult. For emancipating manpower, in recent years, some synthetic datasets are released. However, they are still different from real scenes, which causes that training a model on the synthetic data (source domain) cannot achieve a good performance on real urban scenes (target domain). In this paper, we propose a weakly supervised adversarial domain adaptation to improve the segmentation performance from synthetic data to real scenes, which consists of three deep neural networks. To be specific, a detection and segmentation ("DS" for short) model focuses on detecting objects and predicting segmentation map; a pixel-level domain classifier ("PDC" for short) tries to distinguish the image features from which domains; an object-level domain classifier ("ODC" for short) discriminates the objects from which domains and predicts the objects classes. PDC and ODC are treated as the discriminators, and DS is considered as the generator. By adversarial learning, DS is supposed to learn domain-invariant features. In experiments, our proposed method yields the new record of mIoU metric in the same problem.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09092](http://arxiv.org/abs/1904.09092)

##### PDF
[http://arxiv.org/pdf/1904.09092](http://arxiv.org/pdf/1904.09092)

