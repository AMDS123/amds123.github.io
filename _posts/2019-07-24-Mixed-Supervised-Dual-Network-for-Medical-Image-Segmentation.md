---
layout: post
title: "Mixed-Supervised Dual-Network for Medical Image Segmentation"
date: 2019-07-24 02:31:45
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning Detection
author: Duo Wang, Ming Li, Nir Ben-Shlomo, C. Eduardo Corrales, Yu Cheng, Tao Zhang, Jagadeesan Jayender
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning-based medical image segmentation models usually require large datasets with high-quality dense segmentations to train, which are very time-consuming and expensive to prepare. One way to tackle this difficulty is using the mixed-supervised learning framework, where only a part of data is densely annotated with segmentation label and the rest is weakly labeled with bounding boxes. The model is trained jointly in a multi-task learning setting. In this paper, we propose Mixed-Supervised Dual-Network (MSDN), a novel architecture which consists of two separate networks for the detection and segmentation tasks respectively, and a series of connection modules between the layers of the two networks. These connection modules are used to transfer useful information from the auxiliary detection task to help the segmentation task. We propose to use a recent technique called "Squeeze and Excitation" in the connection module to boost the transfer. We conduct experiments on two medical image segmentation datasets. The proposed MSDN model outperforms multiple baselines.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10209](http://arxiv.org/abs/1907.10209)

##### PDF
[http://arxiv.org/pdf/1907.10209](http://arxiv.org/pdf/1907.10209)

