---
layout: post
title: "CMCGAN: A Uniform Framework for Cross-Modal Visual-Audio Mutual Generation"
date: 2017-12-09 04:01:40
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Classification
author: Wangli Hao, Zhaoxiang Zhang, He Guan
mathjax: true
---

* content
{:toc}

##### Abstract
Visual and audio modalities are two symbiotic modalities underlying videos, which contain both common and complementary information. If they can be mined and fused sufficiently, performances of related video tasks can be significantly enhanced. However, due to the environmental interference or sensor fault, sometimes, only one modality exists while the other is abandoned or missing. By recovering the missing modality from the existing one based on the common information shared between them and the prior information of the specific modality, great bonus will be gained for various vision tasks. In this paper, we propose a Cross-Modal Cycle Generative Adversarial Network (CMCGAN) to handle cross-modal visual-audio mutual generation. Specifically, CMCGAN is composed of four kinds of subnetworks: audio-to-visual, visual-to-audio, audio-to-audio and visual-to-visual subnetworks respectively, which are organized in a cycle architecture. CMCGAN has several remarkable advantages. Firstly, CMCGAN unifies visual-audio mutual generation into a common framework by a joint corresponding adversarial loss. Secondly, through introducing a latent vector with Gaussian distribution, CMCGAN can handle dimension and structure asymmetry over visual and audio modalities effectively. Thirdly, CMCGAN can be trained end-to-end to achieve better convenience. Benefiting from CMCGAN, we develop a dynamic multimodal classification network to handle the modality missing problem. Abundant experiments have been conducted and validate that CMCGAN obtains the state-of-the-art cross-modal visual-audio generation results. Furthermore, it is shown that the generated modality achieves comparable effects with those of original modality, which demonstrates the effectiveness and advantages of our proposed method.

##### Abstract (translated by Google)
视频和音频模式是视频下的两种共生模式，其中包含常见信息和补充信息。如果能够充分挖掘和融合，相关视频任务的表现可以得到显着提高。但是，由于环境干扰或传感器故障，有时只有一种方式存在，另一种方式被遗弃或丢失。通过基于共享信息和特定形式的先验信息，从现有信息中恢复缺失的模式，可以为各种视觉任务获得巨大的收益。在本文中，我们提出了一个跨模态循环生成对抗网络（CMCGAN）来处理跨模态视觉 - 音频相互生成。具体来说，CMCGAN由四种子网组成：音视频，视音频，音视频和视觉子网，分别组成循环体系结构。 CMCGAN有几个显着的优点。首先，CMCGAN通过共同的相应对抗损失，将视音频共生成为一个共同的框架。其次，通过引入具有高斯分布的潜在向量，CMCGAN可以有效地处理视觉和音频模式的维度和结构不对称。第三，CMCGAN可以进行端到端的培训，以获得更好的便利。受益于CMCGAN，我们开发了一个动态多模式分类网络来处理模式缺失问题。已经进行了大量的实验并验证了CMCGAN获得了最先进的跨模态视觉音频产生结果。此外，表明生成的模态达到了与原模态相当的效果，证明了本文方法的有效性和优越性。

##### URL
[http://arxiv.org/abs/1711.08102](http://arxiv.org/abs/1711.08102)

##### PDF
[http://arxiv.org/e-print/1711.08102](http://arxiv.org/e-print/1711.08102)

