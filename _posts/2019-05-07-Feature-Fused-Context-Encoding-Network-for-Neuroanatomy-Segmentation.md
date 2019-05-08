---
layout: post
title: "Feature-Fused Context-Encoding Network for Neuroanatomy Segmentation"
date: 2019-05-07 16:43:12
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Attention CNN
author: Yuemeng Li, Hangfan Liu, Hongming Li, Yong Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic segmentation of fine-grained brain structures remains a challenging task. Current segmentation methods mainly utilize 2D and 3D deep neural networks. The 2D networks take image slices as input to produce coarse segmentation in less processing time, whereas the 3D networks take the whole image volumes to generated fine-detailed segmentation with more computational burden. In order to obtain accurate fine-grained segmentation efficiently, in this paper, we propose an end-to-end Feature-Fused Context-Encoding Network for brain structure segmentation from MR (magnetic resonance) images. Our model is implemented based on a 2D convolutional backbone, which integrates a 2D encoding module to acquire planar image features and a spatial encoding module to extract spatial context information. A global context encoding module is further introduced to capture global context semantics from the fused 2D encoding and spatial features. The proposed network aims to fully leverage the global anatomical prior knowledge learned from context semantics, which is represented by a structure-aware attention factor to recalibrate the outputs of the network. In this way, the network is guaranteed to be aware of the class-dependent feature maps to facilitate the segmentation. We evaluate our model on 2012 Brain Multi-Atlas Labelling Challenge dataset for 134 fine-grained structure segmentation. Besides, we validate our network on 27 coarse structure segmentation tasks. Experimental results have demonstrated that our model can achieve improved performance compared with the state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.02686](https://arxiv.org/abs/1905.02686)

##### PDF
[https://arxiv.org/pdf/1905.02686](https://arxiv.org/pdf/1905.02686)

