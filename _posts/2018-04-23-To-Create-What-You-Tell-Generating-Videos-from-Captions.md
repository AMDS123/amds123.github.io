---
layout: post
title: "To Create What You Tell: Generating Videos from Captions"
date: 2018-04-23 07:07:20
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Caption Embedding Deep_Learning Quantitative
author: Yingwei Pan, Zhaofan Qiu, Ting Yao, Houqiang Li, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
We are creating multimedia contents everyday and everywhere. While automatic content generation has played a fundamental challenge to multimedia community for decades, recent advances of deep learning have made this problem feasible. For example, the Generative Adversarial Networks (GANs) is a rewarding approach to synthesize images. Nevertheless, it is not trivial when capitalizing on GANs to generate videos. The difficulty originates from the intrinsic structure where a video is a sequence of visually coherent and semantically dependent frames. This motivates us to explore semantic and temporal coherence in designing GANs to generate videos. In this paper, we present a novel Temporal GANs conditioning on Captions, namely TGANs-C, in which the input to the generator network is a concatenation of a latent noise vector and caption embedding, and then is transformed into a frame sequence with 3D spatio-temporal convolutions. Unlike the naive discriminator which only judges pairs as fake or real, our discriminator additionally notes whether the video matches the correct caption. In particular, the discriminator network consists of three discriminators: video discriminator classifying realistic videos from generated ones and optimizes video-caption matching, frame discriminator discriminating between real and fake frames and aligning frames with the conditioning caption, and motion discriminator emphasizing the philosophy that the adjacent frames in the generated videos should be smoothly connected as in real ones. We qualitatively demonstrate the capability of our TGANs-C to generate plausible videos conditioning on the given captions on two synthetic datasets (SBMG and TBMG) and one real-world dataset (MSVD). Moreover, quantitative experiments on MSVD are performed to validate our proposal via Generative Adversarial Metric and human study.

##### Abstract (translated by Google)
我们每天都在创造多媒体内容。虽然自动内容生成已经对多媒体社区造成了几十年的根本挑战，但最近深度学习的进展使这个问题变得可行。例如，生成敌对网络（GAN）是合成图像的有益方法。尽管如此，在利用GAN生成视频时，这并不是微不足道的。难题源于内在结构，视频是一系列视觉连贯且语义上相关的帧。这激励我们探索设计GAN来生成视频的语义和时间一致性。在本文中，我们提出了一种新的Caption的Temporal GANs调节，即TGANs-C，其中生成器网络的输入是一个潜在噪声矢量和字幕嵌入的串联，然后被转换成具有3D空间的帧序列 - 时间卷积。与仅将对视为伪造或真实的天真鉴别器不同，我们的鉴别器另外注意视频是否匹配正确的标题。具体来说，鉴别器网络由三个鉴别器组成：视频鉴别器根据所产生的视频对现实视频进行分类并优化视频 - 字幕匹配，识别真实帧和假帧的帧鉴别器以及将帧与调理字幕对齐，以及运动鉴别器强调生成的视频中的相邻帧应该像真实的那样平滑连接。我们定性证明了我们的TGANs-C能够在两个合成数据集（SBMG和TBMG）和一个真实世界数据集（MSVD）上的给定标题上生成合理的视频条件。此外，MSVD的定量实验通过生成敌对度量和人体研究来验证我们的建议。

##### URL
[https://arxiv.org/abs/1804.08264](https://arxiv.org/abs/1804.08264)

##### PDF
[https://arxiv.org/pdf/1804.08264](https://arxiv.org/pdf/1804.08264)

