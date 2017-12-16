---
layout: post
title: "Spatial-Temporal Recurrent Neural Network for Emotion Recognition"
date: 2017-05-12 11:23:07
categories: arXiv_CV
tags: arXiv_CV Salient Sparse Face RNN Deep_Learning Recognition
author: Tong Zhang (1 and 2), Wenming Zheng (2), Zhen Cui (2), Yuan Zong (2), Yang Li (1 and 2) ((1) the Department of Information Science and Engineering, Southeast University, Nanjing, China (2) the Key Laboratory of Child Development and Learning Science of Ministry of Education, Research Center for Learning Science, Southeast University, Nanjing, China)
mathjax: true
---

* content
{:toc}

##### Abstract
Emotion analysis is a crucial problem to endow artifact machines with real intelligence in many large potential applications. As external appearances of human emotions, electroencephalogram (EEG) signals and video face signals are widely used to track and analyze human's affective information. According to their common characteristics of spatial-temporal volumes, in this paper we propose a novel deep learning framework named spatial-temporal recurrent neural network (STRNN) to unify the learning of two different signal sources into a spatial-temporal dependency model. In STRNN, to capture those spatially cooccurrent variations of human emotions, a multi-directional recurrent neural network (RNN) layer is employed to capture longrange contextual cues by traversing the spatial region of each time slice from multiple angles. Then a bi-directional temporal RNN layer is further used to learn discriminative temporal dependencies from the sequences concatenating spatial features of each time slice produced from the spatial RNN layer. To further select those salient regions of emotion representation, we impose sparse projection onto those hidden states of spatial and temporal domains, which actually also increases the model discriminant ability because of this global consideration. Consequently, such a two-layer RNN model builds spatial dependencies as well as temporal dependencies of the input signals. Experimental results on the public emotion datasets of EEG and facial expression demonstrate the proposed STRNN method is more competitive over those state-of-the-art methods.

##### Abstract (translated by Google)
情感分析是在许多大型潜在应用中赋予工件机器真实智能的关键问题。作为人类情感的外在表现，脑电图（EEG）信号和视频人脸信号被广泛用于追踪和分析人类的情感信息。本文提出了一种新的时空递归神经网络（STRNN）深度学习框架，将两种不同信号源的学习方式统一为时空依赖模型。在STRNN中，为了捕获人类情绪的空间并发变化，采用多向递归神经网络（RNN）层从多个角度穿越每个时间片的空间区域来捕捉长时间的情境线索。然后，双向时间RNN层被进一步用于从连接从空间RNN层产生的每个时间片的空间特征的序列学习判别性时间依赖性。为了进一步选择那些显着的情感表征区域，我们对这些隐藏的时空域进行了稀疏投影，实际上也由于这个全局考虑而增加了模型的判别能力。因此，这种两层RNN模型建立输入信号的空间依赖性和时间依赖性。在EEG和面部表情的公共情绪数据集上的实验结果表明，所提出的STRNN方法比那些最先进的方法更具竞争力。

##### URL
[https://arxiv.org/abs/1705.04515](https://arxiv.org/abs/1705.04515)

##### PDF
[https://arxiv.org/pdf/1705.04515](https://arxiv.org/pdf/1705.04515)

