---
layout: post
title: "Robust LSTM-Autoencoders for Face De-Occlusion in the Wild"
date: 2016-12-27 08:36:48
categories: arXiv_CV
tags: arXiv_CV Adversarial Face RNN Recognition Face_Recognition
author: Fang Zhao, Jiashi Feng, Jian Zhao, Wenhan Yang, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
Face recognition techniques have been developed significantly in recent years. However, recognizing faces with partial occlusion is still challenging for existing face recognizers which is heavily desired in real-world applications concerning surveillance and security. Although much research effort has been devoted to developing face de-occlusion methods, most of them can only work well under constrained conditions, such as all the faces are from a pre-defined closed set. In this paper, we propose a robust LSTM-Autoencoders (RLA) model to effectively restore partially occluded faces even in the wild. The RLA model consists of two LSTM components, which aims at occlusion-robust face encoding and recurrent occlusion removal respectively. The first one, named multi-scale spatial LSTM encoder, reads facial patches of various scales sequentially to output a latent representation, and occlusion-robustness is achieved owing to the fact that the influence of occlusion is only upon some of the patches. Receiving the representation learned by the encoder, the LSTM decoder with a dual channel architecture reconstructs the overall face and detects occlusion simultaneously, and by feat of LSTM, the decoder breaks down the task of face de-occlusion into restoring the occluded part step by step. Moreover, to minimize identify information loss and guarantee face recognition accuracy over recovered faces, we introduce an identity-preserving adversarial training scheme to further improve RLA. Extensive experiments on both synthetic and real datasets of faces with occlusion clearly demonstrate the effectiveness of our proposed RLA in removing different types of facial occlusion at various locations. The proposed method also provides significantly larger performance gain than other de-occlusion methods in promoting recognition performance over partially-occluded faces.

##### Abstract (translated by Google)
人脸识别技术近年来得到了显着的发展。然而，对于现有的面部识别器来说，识别具有部分遮挡的面部仍然具有挑战性，这在实际应用中非常需要涉及监视和安全。虽然已经有很多研究工作致力于开发人脸去遮挡方法，但是他们中的大多数只能在受约束的条件下才能正常工作，比如所有的人脸都是来自预定义的闭集。在本文中，我们提出了一个强大的LSTM自动编码器（RLA）模型，即使在野外也能有效恢复部分遮挡的面部。 RLA模型由两个LSTM分量组成，分别针对遮挡鲁棒人脸编码和递归遮挡去除。第一种称为多尺度空间LSTM编码器，依次读取各种尺度的面部片段，输出一个潜在的表示，由于遮挡的影响仅在一些片上，所以实现了遮挡鲁棒性。接收到编码器学习到的表示，双通道架构的LSTM解码器同时重建整个人脸并检测遮挡，通过LSTM技术，解码器将面部遮挡任务分解为逐步恢复遮挡部分。此外，为了最大限度地减少识别信息丢失，保证恢复人脸识别的准确性，我们引入了身份保持对抗训练方案，以进一步提高RLA。对具有遮挡的人脸的合成和真实数据集的大量实验清楚地证明了我们提出的RLA在去除不同位置处的不同类型的面部遮挡的有效性。与其他去遮挡方法相比，所提出的方法在促进部分遮挡面上的识别性能方面也提供了显着更大的性能增益。

##### URL
[https://arxiv.org/abs/1612.08534](https://arxiv.org/abs/1612.08534)

##### PDF
[https://arxiv.org/pdf/1612.08534](https://arxiv.org/pdf/1612.08534)

