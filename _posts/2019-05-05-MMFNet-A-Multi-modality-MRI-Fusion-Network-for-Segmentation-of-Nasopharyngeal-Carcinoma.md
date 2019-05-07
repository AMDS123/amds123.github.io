---
layout: post
title: "MMFNet: A Multi-modality MRI Fusion Network for Segmentation of Nasopharyngeal Carcinoma"
date: 2019-05-05 12:39:40
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Huai Chen, Yuxiao Qi, Yong Yin, Tengxiang Li, Guanzhong Gong, Lisheng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Segmentation of nasopharyngeal carcinoma (NPC) from Magnetic Resonance Images (MRI) is a crucial prerequisite for NPC radiotherapy. However, manually segmenting of NPC is time-consuming and labor-intensive. Additionally, single-modality MRI generally cannot provide enough information for its accurate delineation. Therefore, a multi-modality MRI fusion network (MMFNet) based on three modalities of MRI (T1, T2 and contrast-enhanced T1) is proposed to complete accurate segmentation of NPC. The backbone of MMFNet is designed as a multi-encoder-based network, consisting of several encoders to capture modality-specific features and one single decoder to fuse them and obtain high-level features for NPC segmentation. A fusion block is presented to effectively fuse features from multi-modality MRI. It firstly recalibrates low-level features captured from modality-specific encoders to highlight both informative features and regions of interest, then fuses weighted features by a residual fusion block to keep balance between fused ones and high-level features from decoder. Moreover, a training strategy named self-transfer, which utilizes pre-trained modality-specific encoders to initialize multi-encoder-based network, is proposed to make full mining of information from different modalities of MRI. The proposed method based on multi-modality MRI can effectively segment NPC and its advantages are validated by extensive experiments.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10033](http://arxiv.org/abs/1812.10033)

##### PDF
[http://arxiv.org/pdf/1812.10033](http://arxiv.org/pdf/1812.10033)

