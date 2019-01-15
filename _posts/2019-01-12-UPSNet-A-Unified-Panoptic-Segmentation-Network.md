---
layout: post
title: "UPSNet: A Unified Panoptic Segmentation Network"
date: 2019-01-12 02:39:03
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference Classification Prediction
author: Yuwen Xiong, Renjie Liao, Hengshuang Zhao, Rui Hu, Min Bai, Ersin Yumer, Raquel Urtasun
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a unified panoptic segmentation network (UPSNet) for tackling the newly proposed panoptic segmentation task. On top of a single backbone residual network, we first design a deformable convolution based semantic segmentation head and a Mask R-CNN style instance segmentation head which solve these two subtasks simultaneously. More importantly, we introduce a parameter-free panoptic head which solves the panoptic segmentation via pixel-wise classification. It first leverages the logits from the previous two heads and then innovatively expands the representation for enabling prediction of an extra unknown class which helps better resolve the conflicts between semantic and instance segmentation. Additionally, it handles the challenge caused by the varying number of instances and permits back propagation to the bottom modules in an end-to-end manner. Extensive experimental results on Cityscapes, COCO and our internal dataset demonstrate that our UPSNet achieves state-of-the-art performance with much faster inference.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.03784](http://arxiv.org/abs/1901.03784)

##### PDF
[http://arxiv.org/pdf/1901.03784](http://arxiv.org/pdf/1901.03784)

