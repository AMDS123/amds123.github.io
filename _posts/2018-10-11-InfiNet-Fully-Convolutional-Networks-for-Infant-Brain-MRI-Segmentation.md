---
layout: post
title: "InfiNet: Fully Convolutional Networks for Infant Brain MRI Segmentation"
date: 2018-10-11 16:05:00
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN Semantic_Segmentation Classification
author: Shubham Kumar, Sailesh Conjeti, Abhijit Guha Roy, Christian Wachinger, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel, parameter-efficient and practical fully convolutional neural network architecture, termed InfiNet, aimed at voxel-wise semantic segmentation of infant brain MRI images at iso-intense stage, which can be easily extended for other segmentation tasks involving multi-modalities. InfiNet consists of double encoder arms for T1 and T2 input scans that feed into a joint-decoder arm that terminates in the classification layer. The novelty of InfiNet lies in the manner in which the decoder upsamples lower resolution input feature map(s) from multiple encoder arms. Specifically, the pooled indices computed in the max-pooling layers of each of the encoder blocks are related to the corresponding decoder block to perform non-linear learning-free upsampling. The sparse maps are concatenated with intermediate encoder representations (skip connections) and convolved with trainable filters to produce dense feature maps. InfiNet is trained end-to-end to optimize for the Generalized Dice Loss, which is well-suited for high class imbalance. InfiNet achieves the whole-volume segmentation in under 50 seconds and we demonstrate competitive performance against multiple state-of-the art deep architectures and their multi-modal variants.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.05735](https://arxiv.org/abs/1810.05735)

##### PDF
[https://arxiv.org/pdf/1810.05735](https://arxiv.org/pdf/1810.05735)

