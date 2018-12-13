---
layout: post
title: "Learning Semantic Segmentation from Synthetic Data: A Geometrically Guided Input-Output Adaptation Approach"
date: 2018-12-12 17:23:24
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation Attention Semantic_Segmentation Relation
author: Yuhua Chen, Wen Li, Xiaoran Chen, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, increasing attention has been drawn to training semantic segmentation models using synthetic data and computer-generated annotation. However, domain gap remains a major barrier and prevents models learned from synthetic data from generalizing well to real-world applications. In this work, we take the advantage of additional geometric information from synthetic data, a powerful yet largely neglected cue, to bridge the domain gap. Such geometric information can be generated easily from synthetic data, and is proven to be closely coupled with semantic information. With the geometric information, we propose a model to reduce domain shift on two levels: on the input level, we augment the traditional image translation network with the additional geometric information to translate synthetic images into realistic styles; on the output level, we build a task network which simultaneously performs depth estimation and semantic segmentation on the synthetic data. Meanwhile, we encourage the network to preserve correlation between depth and semantics by adversarial training on the output space. We then validate our method on two pairs of synthetic to real dataset: Virtual KITTI to KITTI, and SYNTHIA to Cityscapes, where we achieve a significant performance gain compared to the non-adapt baseline and methods using only semantic label. This demonstrates the usefulness of geometric information from synthetic data for cross-domain semantic segmentation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05040](http://arxiv.org/abs/1812.05040)

##### PDF
[http://arxiv.org/pdf/1812.05040](http://arxiv.org/pdf/1812.05040)

