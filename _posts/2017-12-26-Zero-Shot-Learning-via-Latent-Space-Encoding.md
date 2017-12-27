---
layout: post
title: "Zero-Shot Learning via Latent Space Encoding"
date: 2017-12-26 16:26:36
categories: arXiv_CV
tags: arXiv_CV Knowledge Embedding Relation
author: Yunlong Yu, Zhong Ji, Jichang Guo, Zhongfei (Mark) Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Zero-Shot Learning (ZSL) is typically achieved by resorting to a class semantic embedding space to transfer the knowledge from the seen classes to unseen ones. Capturing the common semantic characteristics between the visual modality and the class semantic modality (e.g., attributes or word vector) is a key to the success of ZSL. In this paper, we present a novel approach called Latent Space Encoding (LSE) for ZSL based on an encoder-decoder framework, which learns a highly effective latent space to well reconstruct both the visual space and the semantic embedding space. For each modality, the encoderdecoder framework jointly maximizes the recoverability of the original space from the latent space and the predictability of the latent space from the original space, thus making the latent space feature-aware. To relate the visual and class semantic modalities together, their features referring to the same concept are enforced to share the same latent codings. In this way, the semantic relations of different modalities are generalized with the latent representations. We also show that the proposed encoder-decoder framework is easily extended to more modalities. Extensive experimental results on four benchmark datasets (AwA, CUB, aPY, and ImageNet) clearly demonstrate the superiority of the proposed approach on several ZSL tasks, including traditional ZSL, generalized ZSL, and zero-shot retrieval (ZSR).

##### Abstract (translated by Google)
零点学习（Zero-Shot Learning，ZSL）典型地通过利用类语义嵌入空间来将知识从所看到的类转移到看不见的类。捕捉视觉形态与类语义形态（例如，属性或词向量）之间的共同语义特征是ZSL成功的关键。在本文中，我们提出了一种基于编码器 - 解码器框架的用于ZSL的潜在空间编码（Latent Space Encoding，LSE）方法，该方法学习了一个高效的潜在空间，可以很好地重构视觉空间和语义嵌入空间。对于每种模式，编码器解码器框架将原始空间的可恢复性与潜在空间的可恢复性以及原始空间的潜在空间的可预测性联合最大化，从而使潜在空间特征感知。为了将视觉和语义模式联系在一起，强调指向同一概念的特征共享相同的潜在编码。这样，不同形式的语义关系就与潜在的表征一起推广了。我们还表明，提出的编码器 - 解码器框架很容易扩展到更多的模态。在四个基准数据集（AwA，CUB，aPY和ImageNet）上的广泛的实验结果清楚地证明了所提出的方法在几个ZSL任务中的优越性，包括传统的ZSL，广义ZSL和零点检索（ZSR）。

##### URL
[http://arxiv.org/abs/1712.09300](http://arxiv.org/abs/1712.09300)

##### PDF
[http://arxiv.org/pdf/1712.09300](http://arxiv.org/pdf/1712.09300)

