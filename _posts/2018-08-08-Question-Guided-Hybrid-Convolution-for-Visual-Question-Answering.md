---
layout: post
title: "Question-Guided Hybrid Convolution for Visual Question Answering"
date: 2018-08-08 05:39:00
categories: arXiv_AI
tags: arXiv_AI QA Attention Relation VQA
author: Peng Gao, Pan Lu, Hongsheng Li, Shuang Li, Yikang Li, Steven Hoi, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel Question-Guided Hybrid Convolution (QGHC) network for Visual Question Answering (VQA). Most state-of-the-art VQA methods fuse the high-level textual and visual features from the neural network and abandon the visual spatial information when learning multi-modal features.To address these problems, question-guided kernels generated from the input question are designed to convolute with visual features for capturing the textual and visual relationship in the early stage. The question-guided convolution can tightly couple the textual and visual information but also introduce more parameters when learning kernels. We apply the group convolution, which consists of question-independent kernels and question-dependent kernels, to reduce the parameter size and alleviate over-fitting. The hybrid convolution can generate discriminative multi-modal features with fewer parameters. The proposed approach is also complementary to existing bilinear pooling fusion and attention based VQA methods. By integrating with them, our method could further boost the performance. Extensive experiments on public VQA datasets validate the effectiveness of QGHC.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的问题引导混合卷积（QGHC）网络用于视觉问答（VQA）。大多数最先进的VQA方法融合了神经网络中的高级文本和视觉特征，并在学习多模态特征时放弃了视觉空间信息。为了解决这些问题，从输入问题生成问题引导的内核旨在与视觉特征卷积，以捕捉早期阶段的文本和视觉关系。问题引导的卷积可以紧密耦合文本和视觉信息，但在学习内核时也会引入更多参数。我们应用组卷积，它由与问题无关的内核和与问题相关的内核组成，以减小参数大小并减轻过度拟合。混合卷积可以用较少的参数生成具有辨别力的多模态特征。所提出的方法还补充了现有的双线性池化融合和基于注意力的VQA方法。通过与它们集成，我们的方法可以进一步提高性能。对公共VQA数据集的广泛实验验证了QGHC的有效性。

##### URL
[http://arxiv.org/abs/1808.02632](http://arxiv.org/abs/1808.02632)

##### PDF
[http://arxiv.org/pdf/1808.02632](http://arxiv.org/pdf/1808.02632)

