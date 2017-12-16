---
layout: post
title: "The Devil is in the Decoder"
date: 2017-08-12 21:59:03
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Prediction Detection
author: Zbigniew Wojna, Vittorio Ferrari, Sergio Guadarrama, Nathan Silberman, Liang-Chieh Chen, Alireza Fathi, Jasper Uijlings
mathjax: true
---

* content
{:toc}

##### Abstract
Many machine vision applications require predictions for every pixel of the input image (for example semantic segmentation, boundary detection). Models for such problems usually consist of encoders which decreases spatial resolution while learning a high-dimensional representation, followed by decoders who recover the original input resolution and result in low-dimensional predictions. While encoders have been studied rigorously, relatively few studies address the decoder side. Therefore this paper presents an extensive comparison of a variety of decoders for a variety of pixel-wise prediction tasks. Our contributions are: (1) Decoders matter: we observe significant variance in results between different types of decoders on various problems. (2) We introduce a novel decoder: bilinear additive upsampling. (3) We introduce new residual-like connections for decoders. (4) We identify two decoder types which give a consistently high performance.

##### Abstract (translated by Google)
许多机器视觉应用需要对输入图像的每个像素进行预测（例如语义分割，边界检测）。这些问题的模型通常由编码器组成，这些编码器在学习高维表示的同时降低了空间分辨率，接着是恢复原始输入分辨率并导致低维预测的解码器。尽管对编码器进行了严格的研究，但相对较少的研究致力于解码器方面。因此，本文介绍了各种解码器在各种像素级预测任务中的广泛比较。我们的贡献是：（1）解码器很重要：我们注意到不同类型的解码器在各种问题上的结果有显着的差异。 （2）我们介绍一种新颖的解码器：双线性加法上采样。 （3）为解码器引入新的类似残差的连接。 （4）我们确定两种解码器类型，使其性能始终如一。

##### URL
[https://arxiv.org/abs/1707.05847](https://arxiv.org/abs/1707.05847)

##### PDF
[https://arxiv.org/pdf/1707.05847](https://arxiv.org/pdf/1707.05847)

