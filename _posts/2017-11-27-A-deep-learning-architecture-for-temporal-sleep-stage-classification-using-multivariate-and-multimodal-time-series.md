---
layout: post
title: "A deep learning architecture for temporal sleep stage classification using multivariate and multimodal time series"
date: 2017-11-27 09:37:28
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning
author: Stanislas Chambon, Mathieu Galtier, Pierrick Arnal, Gilles Wainrib, Alexandre Gramfort
mathjax: true
---

* content
{:toc}

##### Abstract
Sleep stage classification constitutes an important preliminary exam in the diagnosis of sleep disorders. It is traditionally performed by a sleep expert who assigns to each 30s of signal a sleep stage, based on the visual inspection of signals such as electroencephalograms (EEG), electrooculograms (EOG), electrocardiograms (ECG) and electromyograms (EMG). We introduce here the first deep learning approach for sleep stage classification that learns end-to-end without computing spectrograms or extracting hand-crafted features, that exploits all multivariate and multimodal Polysomnography (PSG) signals (EEG, EMG and EOG), and that can exploit the temporal context of each 30s window of data. For each modality the first layer learns linear spatial filters that exploit the array of sensors to increase the signal-to-noise ratio, and the last layer feeds the learnt representation to a softmax classifier. Our model is compared to alternative automatic approaches based on convolutional networks or decisions trees. Results obtained on 61 publicly available PSG records with up to 20 EEG channels demonstrate that our network architecture yields state-of-the-art performance. Our study reveals a number of insights on the spatio-temporal distribution of the signal of interest: a good trade-off for optimal classification performance measured with balanced accuracy is to use 6 EEG with 2 EOG (left and right) and 3 EMG chin channels. Also exploiting one minute of data before and after each data segment offers the strongest improvement when a limited number of channels is available. As sleep experts, our system exploits the multivariate and multimodal nature of PSG signals in order to deliver state-of-the-art classification performance with a small computational cost.

##### Abstract (translated by Google)
睡眠阶段分类是诊断睡眠障碍的重要初步检查。传统上，睡眠专家根据对脑电图（EEG），眼电图（EOG），心电图（ECG）和肌电图（EMG）等信号的视觉检查将睡眠阶段分配给每30秒的信号。我们在这里介绍的第一个深度学习方法的睡眠阶段分类，学习端到端没有计算光谱图或提取手工制作的功能，利用所有多元和多模态多导睡眠监测（PSG）信号（脑电图，肌电图和眼电图），可以利用每个30s窗口数据的时间上下文。对于每种模式，第一层学习利用传感器阵列增加信噪比的线性空间滤波器，最后一层将学习的表示馈送到softmax分类器。我们的模型与基于卷积网络或决策树的替代自动方法进行比较。在61个公开可用的PSG记录中获得的结果可以达到20个EEG通道，这表明我们的网络架构可以获得最先进的性能。我们的研究揭示了关于感兴趣的信号的时空分布的一些见解：以平衡的准确度测量的最佳分类性能的良好折衷是使用具有2个EOG（左和右）和3个EMG下巴通道的6个EEG 。在有限数量的信道可用的情况下，在每个数据段之前和之后还利用一分钟的数据提供最强的改进。作为睡眠专家，我们的系统利用PSG信号的多变量和多模态性质，以最小的计算成本提供最先进的分类性能。

##### URL
[https://arxiv.org/abs/1707.03321](https://arxiv.org/abs/1707.03321)

##### PDF
[https://arxiv.org/pdf/1707.03321](https://arxiv.org/pdf/1707.03321)

