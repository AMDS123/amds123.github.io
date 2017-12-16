---
layout: post
title: "Context-aware Single-Shot Detector"
date: 2017-07-27 01:50:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Relation
author: Wei Xiang, Dong-Qing Zhang, Vassilis Athitsos, Heather Yu
mathjax: true
---

* content
{:toc}

##### Abstract
SSD is one of the state-of-the-art object detection algorithms, and it combines high detection accuracy with real-time speed. However, it is widely recognized that SSD is less accurate in detecting small objects compared to large objects, because it ignores the context from outside the proposal boxes. In this paper, we present CSSD--a shorthand for context-aware single-shot multibox object detector. CSSD is built on top of SSD, with additional layers modeling multi-scale contexts. We describe two variants of CSSD, which differ in their context layers, using dilated convolution layers (DiCSSD) and deconvolution layers (DeCSSD) respectively. The experimental results show that the multi-scale context modeling significantly improves the detection accuracy. In addition, we study the relationship between effective receptive fields (ERFs) and the theoretical receptive fields (TRFs), particularly on a VGGNet. The empirical results further strengthen our conclusion that SSD coupled with context layers achieves better detection results especially for small objects ($+3.2\% {\rm AP}_{@0.5}$ on MS-COCO compared to the newest SSD), while maintaining comparable runtime performance.

##### Abstract (translated by Google)
SSD是最先进的物体检测算法之一，它将高检测精度与实时速度相结合。然而，人们普遍认为，与大型对象相比，SSD在检测小型对象时不够准确，因为它忽略了来自提案框之外的上下文。在本文中，我们提出CSSD  - 一个上下文感知的单发多盒物体检测器的简写。 CSSD建立在SSD的基础之上，其他图层建模多尺度上下文。我们描述了CSSD的两个变体，它们的上下文层不同，分别使用扩张卷积层（DiCSSD）和解卷积层（DeCSSD）。实验结果表明，多尺度上下文建模显着提高了检测精度。此外，我们还研究了有效接受领域（ERFs）与理论接受领域（TRFs）之间的关系，特别是在VGGNet上。实验结果进一步加强了我们的结论：SSD与上下文层相结合可以获得更好的检测结果，特别是对于小型对象（与最新的SSD相比，MS-COCO上的$ + 3.2％{\ rm AP }_{@0.5}），而保持可比的运行时性能

##### URL
[https://arxiv.org/abs/1707.08682](https://arxiv.org/abs/1707.08682)

##### PDF
[https://arxiv.org/pdf/1707.08682](https://arxiv.org/pdf/1707.08682)

