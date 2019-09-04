---
layout: post
title: "Adversarial Learning and Self-Teaching Techniques for Domain Adaptation in Semantic Segmentation"
date: 2019-09-02 16:05:05
categories: arXiv_AI
tags: arXiv_AI Adversarial Segmentation Semantic_Segmentation Deep_Learning
author: Umberto Michieli, Matteo Biasetton, Gianluca Agresti, Pietro Zanuttigh
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning techniques have been widely used in autonomous driving systems for the semantic understanding of urban scenes, however they need a huge amount of labeled data for training, which is difficult and expensive to acquire. A recently proposed workaround is to train deep networks using synthetic data, however the domain shift between real world and synthetic representations limits the performance. In this work a novel unsupervised domain adaptation strategy is introduced to solve this issue. The proposed learning strategy is driven by three components: a standard supervised learning loss on labeled synthetic data, an adversarial learning module that exploits both labeled synthetic data and unlabeled real data and finally a self-teaching strategy exploiting unlabeled data. The last component exploits a region growing framework guided by the segmentation confidence. Furthermore, we weighted this component on the basis of the class frequencies to enhance the performance on less common classes. Experimental results prove the effectiveness of the proposed strategy in adapting a segmentation network trained on synthetic datasets, like GTA5 and SYNTHIA, to real world datasets like Cityscapes and Mapillary.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1909.00781](http://arxiv.org/abs/1909.00781)

##### PDF
[http://arxiv.org/pdf/1909.00781](http://arxiv.org/pdf/1909.00781)

