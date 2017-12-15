---
layout: post
title: "Unsupervised Domain Adaptation for Robust Speech Recognition via Variational Autoencoder-Based Data Augmentation"
date: 2017-09-22 16:31:05
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Recognition
author: Wei-Ning Hsu, Yu Zhang, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
Domain mismatch between training and testing can lead to significant degradation in performance in many machine learning scenarios. Unfortunately, this is not a rare situation for automatic speech recognition deployments in real-world applications. Research on robust speech recognition can be regarded as trying to overcome this domain mismatch issue. In this paper, we address the unsupervised domain adaptation problem for robust speech recognition, where both source and target domain speech are presented, but word transcripts are only available for the source domain speech. We present novel augmentation-based methods that transform speech in a way that does not change the transcripts. Specifically, we first train a variational autoencoder on both source and target domain data (without supervision) to learn a latent representation of speech. We then transform nuisance attributes of speech that are irrelevant to recognition by modifying the latent representations, in order to augment labeled training data with additional data whose distribution is more similar to the target domain. The proposed method is evaluated on the CHiME-4 dataset and reduces the absolute word error rate (WER) by as much as 35% compared to the non-adapted baseline.

##### Abstract (translated by Google)
训练和测试之间的域不匹配会导致许多机器学习场景中的性能显着下降。不幸的是，在实际应用中，自动语音识别部署并不罕见。对鲁棒语音识别的研究可以被看作是试图克服这个领域的不匹配问题。在本文中，我们提出了鲁棒语音识别的无监督域自适应问题，其中源语言和目标语言都被提出，但是单词转录只能用于源域语音。我们提出新的基于增强的方法，以不改变成绩单的方式转换语音。具体来说，我们首先训练源和目标域数据（无监督）的变分自动编码器来学习语音的潜在表示。然后，我们通过修改潜在表示来转换与识别无关的语音的讨厌属性，以便用标记的训练数据增加具有更接近目标域的分布数据。所提出的方法在CHiME-4数据集上进行评估，与非适应的基线相比，绝对误码率（WER）降低了35％。

##### URL
[https://arxiv.org/abs/1707.06265](https://arxiv.org/abs/1707.06265)

##### PDF
[https://arxiv.org/pdf/1707.06265](https://arxiv.org/pdf/1707.06265)

