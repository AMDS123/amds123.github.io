---
layout: post
title: "Attentive Normalization"
date: 2019-08-04 02:17:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Attention Classification Deep_Learning Detection
author: Xilai Li, Wei Sun, Tianfu Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Batch Normalization (BN) is a vital pillar in the development of deep learning with many recent variations such as Group Normalization (GN) and Switchable Normalization. Channel-wise feature attention methods such as the squeeze-and-excitation (SE) unit have also shown impressive performance improvement. BN and its variants take into account different ways of computing the mean and variance within a min-batch for feature normalization, followed by a learnable channel-wise affine transformation. SE explicitly learns how to adaptively recalibrate channel-wise feature responses. They have been studied separately, however. In this paper, we propose a novel and lightweight integration of feature normalization and feature channel-wise attention. We present Attentive Normalization (AN) as a simple and unified alternative. AN absorbs SE into the affine transformation of BN. AN learns a small number of scale and offset parameters per channel (i.e., different affine transformations). Their weighted sums (i.e., mixture) are used in the final affine transformation. The weights are instance-specific and learned in a way that channel-wise attention is considered, similar in spirit to the squeeze module in the SE unit. AN is complementary and applicable to existing variants of BN. In experiments, we test AN in the ImageNet-1K classification dataset and the MS-COCO object detection and instance segmentation dataset with significantly better performance obtained than the vanilla BN. Our AN also outperforms two state-of-the-art variants of BN, GN and SN. The source code will be released at \url{<a href="http://github.com/ivMCL/AttentiveNorm">this http URL</a>}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01259](http://arxiv.org/abs/1908.01259)

##### PDF
[http://arxiv.org/pdf/1908.01259](http://arxiv.org/pdf/1908.01259)

