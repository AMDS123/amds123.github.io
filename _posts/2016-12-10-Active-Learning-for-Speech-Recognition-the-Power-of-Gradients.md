---
layout: post
title: "Active Learning for Speech Recognition: the Power of Gradients"
date: 2016-12-10 00:09:45
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Jiaji Huang, Rewon Child, Vinay Rao, Hairong Liu, Sanjeev Satheesh, Adam Coates
mathjax: true
---

* content
{:toc}

##### Abstract
In training speech recognition systems, labeling audio clips can be expensive, and not all data is equally valuable. Active learning aims to label only the most informative samples to reduce cost. For speech recognition, confidence scores and other likelihood-based active learning methods have been shown to be effective. Gradient-based active learning methods, however, are still not well-understood. This work investigates the Expected Gradient Length (EGL) approach in active learning for end-to-end speech recognition. We justify EGL from a variance reduction perspective, and observe that EGL's measure of informativeness picks novel samples uncorrelated with confidence scores. Experimentally, we show that EGL can reduce word errors by 11\%, or alternatively, reduce the number of samples to label by 50\%, when compared to random sampling.

##### Abstract (translated by Google)
在训练语音识别系统时，标记音频片段可能是昂贵的，并不是所有的数据都是同样有价值的。主动学习的目的是仅标注最丰富的样本以降低成本。对于语音识别，置信度分数和其他基于可能性的主动学习方法已被证明是有效的。然而，基于渐变的主动学习方法仍然不是很好理解。这项工作调查了端到端语音识别主动学习中的预期梯度长度（EGL）方法。我们从方差减少的角度证明了EGL的正确性，并且观察到EGL的信息性度量选择与置信度分数不相关的新样本。在实验上，我们表明，与随机抽样相比，EGL可以减少11％的单词错误，或者减少50％的样本数量。

##### URL
[https://arxiv.org/abs/1612.03226](https://arxiv.org/abs/1612.03226)

##### PDF
[https://arxiv.org/pdf/1612.03226](https://arxiv.org/pdf/1612.03226)

