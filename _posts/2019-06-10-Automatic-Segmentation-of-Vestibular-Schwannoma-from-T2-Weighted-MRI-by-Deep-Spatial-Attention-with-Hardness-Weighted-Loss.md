---
layout: post
title: "Automatic Segmentation of Vestibular Schwannoma from T2-Weighted MRI by Deep Spatial Attention with Hardness-Weighted Loss"
date: 2019-06-10 11:28:22
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN
author: Guotai Wang, Jonathan Shapey, Wenqi Li, Reuben Dorent, Alex Demitriadis, Sotirios Bisdas, Ian Paddick, Robert Bradford, Sebastien Ourselin, Tom Vercauteren
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic segmentation of vestibular schwannoma (VS) tumors from magnetic resonance imaging (MRI) would facilitate efficient and accurate volume measurement to guide patient management and improve clinical workflow. The accuracy and robustness is challenged by low contrast, small target region and low through-plane resolution. We introduce a 2.5D convolutional neural network (CNN) able to exploit the different in-plane and through-plane resolutions encountered in standard of care imaging protocols. We use an attention module to enable the CNN to focus on the small target and propose a supervision on the learning of attention maps for more accurate segmentation. Additionally, we propose a hardness-weighted Dice loss function that gives higher weights to harder voxels to boost the training of CNNs. Experiments with ablation studies on the VS tumor segmentation task show that: 1) the proposed 2.5D CNN outperforms its 2D and 3D counterparts, 2) our supervised attention mechanism outperforms unsupervised attention, 3) the voxel-level hardness-weighted Dice loss can improve the performance of CNNs. Our method achieved an average Dice score and ASSD of 0.87 and 0.43~mm respectively. This will facilitate patient management decisions in clinical practice.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03906](http://arxiv.org/abs/1906.03906)

##### PDF
[http://arxiv.org/pdf/1906.03906](http://arxiv.org/pdf/1906.03906)

