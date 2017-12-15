---
layout: post
title: "Fully DNN-based Multi-label regression for audio tagging"
date: 2016-08-13 10:39:29
categories: arXiv_CV
tags: arXiv_CV Classification Detection
author: Yong Xu, Qiang Huang, Wenwu Wang, Philip J. B. Jackson, Mark D. Plumbley
mathjax: true
---

* content
{:toc}

##### Abstract
Acoustic event detection for content analysis in most cases relies on lots of labeled data. However, manually annotating data is a time-consuming task, which thus makes few annotated resources available so far. Unlike audio event detection, automatic audio tagging, a multi-label acoustic event classification task, only relies on weakly labeled data. This is highly desirable to some practical applications using audio analysis. In this paper we propose to use a fully deep neural network (DNN) framework to handle the multi-label classification task in a regression way. Considering that only chunk-level rather than frame-level labels are available, the whole or almost whole frames of the chunk were fed into the DNN to perform a multi-label regression for the expected tags. The fully DNN, which is regarded as an encoding function, can well map the audio features sequence to a multi-tag vector. A deep pyramid structure was also designed to extract more robust high-level features related to the target tags. Further improved methods were adopted, such as the Dropout and background noise aware training, to enhance its generalization capability for new audio recordings in mismatched environments. Compared with the conventional Gaussian Mixture Model (GMM) and support vector machine (SVM) methods, the proposed fully DNN-based method could well utilize the long-term temporal information with the whole chunk as the input. The results show that our approach obtained a 15% relative improvement compared with the official GMM-based method of DCASE 2016 challenge.

##### Abstract (translated by Google)
在大多数情况下，用于内容分析的声音事件检测依赖于大量标记的数据。但是，手动注释数据是一项耗时的任务，因此至今尚未提供可用的注释资源。与音频事件检测不同，自动音频标记（多标签声音事件分类任务）仅依赖于弱标记的数据。这对于使用音频分析的一些实际应用是非常合乎需要的在本文中，我们建议使用全深度神经网络（DNN）框架以回归方式处理多标签分类任务。考虑到只有块级而不是帧级标签是可用的，块的全部或几乎整个帧被馈送到DNN以对期望的标签执行多标签回归。作为编码函数的完全DNN能很好地将音频特征序列映射到多标签向量。还设计了一个深层金字塔结构，以提取与目标标签相关的更强大的高级功能。采用了进一步改进的方法，如Dropout和背景噪声感知训练，以增强其在不匹配环境中的新录音的泛化能力。与传统的高斯混合模型（GMM）和支持向量机（SVM）方法相比，所提出的基于DNN的方法可以很好地利用以整个块为输入的长时间信息。结果显示，与DCASE 2016挑战的官方基于GMM的方法相比，我们的方法获得了15％的相对改进。

##### URL
[https://arxiv.org/abs/1606.07695](https://arxiv.org/abs/1606.07695)

##### PDF
[https://arxiv.org/pdf/1606.07695](https://arxiv.org/pdf/1606.07695)

