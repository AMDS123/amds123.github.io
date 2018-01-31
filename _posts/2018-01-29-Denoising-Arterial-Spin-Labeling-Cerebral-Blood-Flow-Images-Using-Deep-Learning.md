---
layout: post
title: "Denoising Arterial Spin Labeling Cerebral Blood Flow Images Using Deep Learning"
date: 2018-01-29 20:54:29
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Deep_Learning Quantitative Relation
author: Danfeng Xie, Li Bai, Ze Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Arterial spin labeling perfusion MRI is a noninvasive technique for measuring quantitative cerebral blood flow (CBF), but the measurement is subject to a low signal-to-noise-ratio(SNR). Various post-processing methods have been proposed to denoise ASL MRI but only provide moderate improvement. Deep learning (DL) is an emerging technique that can learn the most representative signal from data without prior modeling which can be highly complex and analytically indescribable. The purpose of this study was to assess whether the record breaking performance of DL can be translated into ASL MRI denoising. We used convolutional neural network (CNN) to build the DL ASL denosing model (DL-ASL) to inherently consider the inter-voxel correlations. To better guide DL-ASL training, we incorporated prior knowledge about ASL MRI: the structural similarity between ASL CBF map and grey matter probability map. A relatively large sample data were used to train the model which was subsequently applied to a new set of data for testing. Experimental results showed that DL-ASL achieved state-of-the-art denoising performance for ASL MRI as compared to current routine methods in terms of higher SNR, keeping CBF quantification quality while shorten the acquisition time by 75%, and automatic partial volume correction.

##### Abstract (translated by Google)
动脉自旋标记灌注MRI是测量定量脑血流量（CBF）的非侵入性技术，但测量受到低信噪比（SNR）的限制。已经提出各种后处理方法来消除ASL MRI，但仅提供适度的改善。深度学习（DL）是一种新兴的技术，可以从数据中学习最具代表性的信号，而不需要事先建模，而这种建模可能非常复杂，分析上也是难以描述的。本研究的目的是评估DL的破纪录性能是否可以转化为ASL MRI去噪。我们使用卷积神经网络（CNN）来构建DL ASL去噪模型（DL-ASL）以固有地考虑体素间相关性。为了更好地指导DL-ASL训练，我们引入了ASL MRI的先验知识：ASL CBF图与灰质概率图之间的结构相似性。使用相对较大的样本数据来训练模型，随后将其应用于一组新的数据以进行测试。实验结果表明，与现有常规方法相比，DL-ASL在信噪比较高方面达到了ASL MRI的最新降噪性能，保持CBF量化质量，同时缩短了75％的采集时间，并且自动部分音量校正。

##### URL
[http://arxiv.org/abs/1801.09672](http://arxiv.org/abs/1801.09672)

##### PDF
[http://arxiv.org/pdf/1801.09672](http://arxiv.org/pdf/1801.09672)

