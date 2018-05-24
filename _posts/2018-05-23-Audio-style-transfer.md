---
layout: post
title: "Audio style transfer"
date: 2018-05-23 06:34:11
categories: arXiv_SD
tags: arXiv_SD Style_Transfer CNN Optimization
author: Eric Grinstein, Ngoc Duong, Alexey Ozerov, Patrick P&#xe9;rez
mathjax: true
---

* content
{:toc}

##### Abstract
"Style transfer" among images has recently emerged as a very active research topic, fuelled by the power of convolution neural networks (CNNs), and has become fast a very popular technology in social media. This paper investigates the analogous problem in the audio domain: How to transfer the style of a reference audio signal to a target audio content? We propose a flexible framework for the task, which uses a sound texture model to extract statistics characterizing the reference audio style, followed by an optimization-based audio texture synthesis to modify the target content. In contrast to mainstream optimization-based visual transfer method, the proposed process is initialized by the target content instead of random noise and the optimized loss is only about texture, not structure. These differences proved key for audio style transfer in our experiments. In order to extract features of interest, we investigate different architectures, whether pre-trained on other tasks, as done in image style transfer, or engineered based on the human auditory system. Experimental results on different types of audio signal confirm the potential of the proposed approach.

##### Abstract (translated by Google)
最近，由于卷积神经网络（CNN）的强大推动，图像之间的“风格转移”成为一个非常活跃的研究课题，并且已成为社交媒体中非常流行的技术。本文调查了音频领域的类似问题：如何将参考音频信号的风格转换为目标音频内容？我们为任务提供了一个灵活的框架，该框架使用完善的纹理模型来提取表征参考音频风格的统计数据，然后是基于优化的音频纹理合成来修改目标内容。与基于主流优化的视觉传输方法相比，所提议的过程由目标内容而不是随机噪声初始化，并且优化的损失仅关于纹理而不是结构。这些差异在我们的实验中被证明是音频风格转换的关键。为了提取感兴趣的特征，我们研究了不同的体系结构，无论是在其他任务上进行过预先训练，还是在图像风格转换中完成，或者基于人类听觉系统进行设计。不同类型的音频信号的实验结果证实了所提出方法的潜力。

##### URL
[http://arxiv.org/abs/1710.11385](http://arxiv.org/abs/1710.11385)

##### PDF
[http://arxiv.org/pdf/1710.11385](http://arxiv.org/pdf/1710.11385)

