---
layout: post
title: "Student-Teacher Learning for BLSTM Mask-based Speech Enhancement"
date: 2018-03-27 10:55:42
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition RNN Recognition
author: Aswin Shanmugam Subramanian, Szu-Jui Chen, Shinji Watanabe
mathjax: true
---

* content
{:toc}

##### Abstract
Spectral mask estimation using bidirectional long short-term memory (BLSTM) neural networks has been widely used in various speech enhancement applications, and it has achieved great success when it is applied to multichannel enhancement techniques with a mask-based beamformer. However, when these masks are used for single channel speech enhancement they severely distort the speech signal and make them unsuitable for speech recognition. This paper proposes a student-teacher learning paradigm for single channel speech enhancement. The beamformed signal from multichannel enhancement is given as input to the teacher network to obtain soft masks. An additional cross-entropy loss term with the soft mask target is combined with the original loss, so that the student network with single-channel input is trained to mimic the soft mask obtained with multichannel input through beamforming. Experiments with the CHiME-4 challenge single channel track data shows improvement in ASR performance.

##### Abstract (translated by Google)
使用双向长期短期记忆（BLSTM）神经网络的谱掩模估计已经广泛用于各种语音增强应用中，并且它在用于基于掩模的波束形成器的多通道增强技术中取得了巨大成功。但是，当这些掩模用于单声道语音增强时，它们会严重扭曲语音信号，使其不适用于语音识别。本文提出了单声道语音增强的学生 - 教师学习范式。将来自多声道增强的波束形成信号作为输入给予教师网络以获得软掩模。将软掩模目标的另一个交叉熵损失项与原始损失相结合，以便具有单通道输入的学生网络被训练以模仿通过波束形成使用多通道输入获得的软掩模。 CHiME-4挑战单通道跟踪数据的实验表明，ASR性能有所提高。

##### URL
[https://arxiv.org/abs/1803.10013](https://arxiv.org/abs/1803.10013)

##### PDF
[https://arxiv.org/pdf/1803.10013](https://arxiv.org/pdf/1803.10013)

