---
layout: post
title: "Face Parsing with RoI Tanh-Warping"
date: 2019-06-04 11:01:17
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Jinpeng Lin, Hao Yang, Dong Chen, Ming Zeng, Fang Wen, Lu Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
Face parsing computes pixel-wise label maps for different semantic components (e.g., hair, mouth, eyes) from face images. Existing face parsing literature have illustrated significant advantages by focusing on individual regions of interest (RoIs) for faces and facial components. However, the traditional crop-and-resize focusing mechanism ignores all contextual area outside the RoIs, and thus is not suitable when the component area is unpredictable, e.g. hair. Inspired by the physiological vision system of human, we propose a novel RoI Tanh-warping operator that combines the central vision and the peripheral vision together. It addresses the dilemma between a limited sized RoI for focusing and an unpredictable area of surrounding context for peripheral information. To this end, we propose a novel hybrid convolutional neural network for face parsing. It uses hierarchical local based method for inner facial components and global methods for outer facial components. The whole framework is simple and principled, and can be trained end-to-end. To facilitate future research of face parsing, we also manually relabel the training data of the HELEN dataset and will make it public. Experiments on both HELEN and LFW-PL benchmarks demonstrate that our method surpasses state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.01342](http://arxiv.org/abs/1906.01342)

##### PDF
[http://arxiv.org/pdf/1906.01342](http://arxiv.org/pdf/1906.01342)

