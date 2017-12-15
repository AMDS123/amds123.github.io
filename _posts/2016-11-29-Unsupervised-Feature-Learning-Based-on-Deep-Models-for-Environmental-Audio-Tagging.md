---
layout: post
title: "Unsupervised Feature Learning Based on Deep Models for Environmental Audio Tagging"
date: 2016-11-29 15:56:36
categories: arXiv_CV
tags: arXiv_CV Classification
author: Yong Xu, Qiang Huang, Wenwu Wang, Peter Foster, Siddharth Sigtia, Philip J. B. Jackson, Mark D. Plumbley
mathjax: true
---

* content
{:toc}

##### Abstract
Environmental audio tagging aims to predict only the presence or absence of certain acoustic events in the interested acoustic scene. In this paper we make contributions to audio tagging in two parts, respectively, acoustic modeling and feature learning. We propose to use a shrinking deep neural network (DNN) framework incorporating unsupervised feature learning to handle the multi-label classification task. For the acoustic modeling, a large set of contextual frames of the chunk are fed into the DNN to perform a multi-label classification for the expected tags, considering that only chunk (or utterance) level rather than frame-level labels are available. Dropout and background noise aware training are also adopted to improve the generalization capability of the DNNs. For the unsupervised feature learning, we propose to use a symmetric or asymmetric deep de-noising auto-encoder (sDAE or aDAE) to generate new data-driven features from the Mel-Filter Banks (MFBs) features. The new features, which are smoothed against background noise and more compact with contextual information, can further improve the performance of the DNN baseline. Compared with the standard Gaussian Mixture Model (GMM) baseline of the DCASE 2016 audio tagging challenge, our proposed method obtains a significant equal error rate (EER) reduction from 0.21 to 0.13 on the development set. The proposed aDAE system can get a relative 6.7% EER reduction compared with the strong DNN baseline on the development set. Finally, the results also show that our approach obtains the state-of-the-art performance with 0.15 EER on the evaluation set of the DCASE 2016 audio tagging task while EER of the first prize of this challenge is 0.17.

##### Abstract (translated by Google)
环境音频标注旨在仅仅预测感兴趣的声场中是否存在某些声学事件。在本文中，我们分别对音频标注做出了贡献，分别是声学建模和特征学习。我们建议使用缩小的深度神经网络（DNN）框架结合无监督的特征学习来处理多标签分类任务。对于声学建模，考虑到只有块（或话语）级别而不是帧级别标签可用，块的大量上下文帧被馈送到DNN以对期望的标签执行多标签分类。为了提高DNN的泛化能力，还采用了丢弃和背景噪声感知训练。对于无监督特征学习，我们建议使用对称或非对称深度去噪自动编码器（sDAE或aDAE）来从Mel滤波器组（MFB）特征生成新的数据驱动特征。这些新功能可以平滑背景噪音，并且可以使用上下文信息更紧凑，从而进一步提高DNN基线的性能。与DCASE 2016音频标签挑战的标准高斯混合模型（GMM）基线相比，我们提出的方法在开发集上获得了显着的等误差率（EER）从0.21降低到0.13。拟议的aDAE系统相对于开发集强DNN基线可以获得相对6.7％的EER减少量。最后，结果还表明，我们的方法在DCASE 2016音频标记任务的评估集上获得了0.15 EER的最新性能，而这个挑战的一等奖的EER为0.17。

##### URL
[https://arxiv.org/abs/1607.03681](https://arxiv.org/abs/1607.03681)

##### PDF
[https://arxiv.org/pdf/1607.03681](https://arxiv.org/pdf/1607.03681)

