---
layout: post
title: "SLSDeep: Skin Lesion Segmentation Based on Dilated Residual and Pyramid Pooling Networks"
date: 2018-05-25 16:38:50
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning Detection
author: Md. Mostafa Kamal Sarker, Hatem A. Rashwan, Syeda Furruka Banu, Adel Saleh, Vivek Kumar Singh, Forhad U H Chowdhury, Saddam Abdulwahab, Santiago Romani, Petia Radeva, Domenec Puig
mathjax: true
---

* content
{:toc}

##### Abstract
Skin lesion segmentation (SLS) in dermoscopic images is a crucial task for automated diagnosis of melanoma. In this paper, we present a robust deep learning SLS model, so-called SLSDeep, which is represented as an encoder-decoder network. The encoder network is constructed by dilated residual layers, in turn, a pyramid pooling network followed by three convolution layers is used for the decoder. Unlike the traditional methods employing a cross-entropy loss, we investigated a loss function by combining both Negative Log Likelihood (NLL) and End Point Error (EPE) to accurately segment the melanoma regions with sharp boundaries. The robustness of the proposed model was evaluated on two public databases: ISBI 2016 and 2017 for skin lesion analysis towards melanoma detection challenge. The proposed model outperforms the state-of-the-art methods in terms of segmentation accuracy. Moreover, it is capable to segment more than $100$ images of size 384x384 per second on a recent GPU.

##### Abstract (translated by Google)
皮肤镜像中的皮肤病变分割（SLS）是黑素瘤自动诊断的关键任务。在本文中，我们提出了一个强大的深度学习SLS模型，即所谓的SLSDeep，它被表示为编码器 - 解码器网络。编码器网络由膨胀的残余层构成，反过来，解码器使用金字塔池网络，然后是三个卷积层。与使用交叉熵损失的传统方法不同，我们通过结合负对数似然（NLL）和终点误差（EPE）来调查损失函数，以准确地分割具有清晰边界的黑色素瘤区域。该模型的稳健性在两个公共数据库上进行了评估：ISBI 2016和2017年针对黑素瘤检测挑战的皮肤病变分析。所提出的模型在分割准确性方面优于最先进的方法。此外，它能够在最近的GPU上分割每秒大小超过100美元的大小为384x384的图像。

##### URL
[http://arxiv.org/abs/1805.10241](http://arxiv.org/abs/1805.10241)

##### PDF
[http://arxiv.org/pdf/1805.10241](http://arxiv.org/pdf/1805.10241)

