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
我们每天都在创造多媒体内容。虽然自动内容生成几十年来一直是多媒体社区面临的根本挑战，但深度学习的最新进展使这一问题变得可行。例如，生成对抗网络（GAN）是一种合成图像的有益方法。然而，在利用GAN生成视频时，这并非易事。困难源于内在结构，其中视频是视觉上连贯和语义相关的帧的序列。这促使我们在设计GAN以生成视频时探索语义和时间的一致性。在本文中，我们提出了一种新的时间GAN调节字幕，即TGANs-C，其中生成器网络的输入是潜在噪声矢量和字幕嵌入的串联，然后转换为具有3D空间的帧序列 - 时间卷积。与只判断假对或真对的天真鉴别器不同，我们的鉴别器还指出视频是否与正确的标题匹配。特别是，鉴别器网络由三个鉴别器组成：视频鉴别器从生成的视频鉴别器中分类逼真的视频并优化视频字幕匹配，区分真实帧和假帧的帧鉴别器以及将帧与条件标题对齐，以及运动鉴别器强调的理念是生成的视频中的相邻帧应该像真实的那样平滑地连接。我们定性地展示了我们的TGANs-C在两个合成数据集（SBMG和TBMG）和一个真实世界数据集（MSVD）上的给定字幕上生成似乎合理的视频的能力。此外，进行MSVD定量实验以通过Generative Adversarial Metric和人体研究验证我们的建议。

##### URL
[https://arxiv.org/abs/1804.08264](https://arxiv.org/abs/1804.08264)

##### PDF
[https://arxiv.org/pdf/1804.08264](https://arxiv.org/pdf/1804.08264)

