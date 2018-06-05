---
layout: post
title: "BoxNet: Deep Learning Based Biomedical Image Segmentation Using Boxes Only Annotation"
date: 2018-06-02 07:10:30
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised Deep_Learning
author: Lin Yang, Yizhe Zhang, Zhuo Zhao, Hao Zheng, Peixian Liang, Michael T. C. Ying, Anil T. Ahuja, Danny Z. Chen
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep learning (DL) methods have become powerful tools for biomedical image segmentation. However, high annotation efforts and costs are commonly needed to acquire sufficient biomedical training data for DL models. To alleviate the burden of manual annotation, in this paper, we propose a new weakly supervised DL approach for biomedical image segmentation using boxes only annotation. First, we develop a method to combine graph search (GS) and DL to generate fine object masks from box annotation, in which DL uses box annotation to compute a rough segmentation for GS and then GS is applied to locate the optimal object boundaries. During the mask generation process, we carefully utilize information from box annotation to filter out potential errors, and then use the generated masks to train an accurate DL segmentation network. Extensive experiments on gland segmentation in histology images, lymph node segmentation in ultrasound images, and fungus segmentation in electron microscopy images show that our approach attains superior performance over the best known state-of-the-art weakly supervised DL method and is able to achieve (1) nearly the same accuracy compared to fully supervised DL methods with far less annotation effort, (2) significantly better results with similar annotation time, and (3) robust performance in various applications.

##### Abstract (translated by Google)
近年来，深度学习（DL）方法已成为生物医学图像分割的强大工具。然而，通常需要高标注努力和成本来获取用于DL模型的足够的生物医学训练数据。为了减轻人工标注的负担，本文提出了一种新的弱监督DL方法用于仅使用方框标注的生物医学图像分割。首先，我们开发了一种组合图搜索（GS）和DL的方法，从盒注释生成精细的对象掩码，其中DL使用框注释来计算GS的粗分割，然后应用GS来定位最佳对象边界。在掩模生成过程中，我们仔细利用框注释中的信息来过滤潜在错误，然后使用生成的掩模来训练精确的DL分割网络。在组织学图像中的腺体分割，超声图像中的淋巴结分割以及电子显微镜图像中的真菌分割的大量实验表明，我们的方法比已知的最先进的弱监督DL方法获得优越的性能，并且能够实现（1）与完全监督的DL方法相比，具有几乎相同的精确度，但注释工作量少得多;（2）具有类似注释时间的显着更好的结果;以及（3）各种应用程序中的稳健性能。

##### URL
[http://arxiv.org/abs/1806.00593](http://arxiv.org/abs/1806.00593)

##### PDF
[http://arxiv.org/pdf/1806.00593](http://arxiv.org/pdf/1806.00593)

