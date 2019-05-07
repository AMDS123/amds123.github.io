---
layout: post
title: "CARAFE: Content-Aware ReAssembly of FEatures"
date: 2019-05-06 17:58:06
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Prediction Detection
author: Jiaqi Wang, Kai Chen, Rui Xu, Ziwei Liu, Chen Change Loy, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Feature upsampling is a key operation in a number of modern convolutional network architectures, e.g. feature pyramids. Its design is critical for dense prediction tasks such as object detection and semantic/instance segmentation. In this work, we propose Content-Aware ReAssembly of FEatures (CARAFE), a universal, lightweight and highly effective operator to fulfill this goal. CARAFE has several appealing properties: (1) Large field of view. Unlike previous works (e.g. bilinear interpolation) that only exploit sub-pixel neighborhood, CARAFE can aggregate contextual information within a large receptive field. (2) Content-aware handling. Instead of using a fixed kernel for all samples (e.g. deconvolution), CARAFE enables instance specific content-aware handling, which generates adaptive kernels on-the-fly. (3) Lightweight and fast to compute. CARAFE introduces little computational overhead and can be readily integrated into modern network architectures. We conduct comprehensive evaluations on standard benchmarks in object detection, instance/semantic segmentation and inpainting. CARAFE shows consistent and substantial gains across all the tasks (1.2%, 1.3%, 1.8%, 1.1db respectively) with negligible computational overhead. It has great potential to serve as a strong building block for future research.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.02188](http://arxiv.org/abs/1905.02188)

##### PDF
[http://arxiv.org/pdf/1905.02188](http://arxiv.org/pdf/1905.02188)

