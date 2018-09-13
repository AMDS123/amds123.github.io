---
layout: post
title: "Unsupervised Representation Learning of Speech for Dialect Identification"
date: 2018-09-12 13:57:06
categories: arXiv_CL
tags: arXiv_CL Represenation_Learning
author: Suwon Shon, Wei-Ning Hsu, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we explore the use of a factorized hierarchical variational autoencoder (FHVAE) model to learn an unsupervised latent representation for dialect identification (DID). An FHVAE can learn a latent space that separates the more static attributes within an utterance from the more dynamic attributes by encoding them into two different sets of latent variables. Useful factors for dialect identification, such as phonetic or linguistic content, are encoded by a segmental latent variable, while irrelevant factors that are relatively constant within a sequence, such as a channel or a speaker information, are encoded by a sequential latent variable. The disentanglement property makes the segmental latent variable less susceptible to channel and speaker variation, and thus reduces degradation from channel domain mismatch. We demonstrate that on fully-supervised DID tasks, an end-to-end model trained on the features extracted from the FHVAE model achieves the best performance, compared to the same model trained on conventional acoustic features and an i-vector based system. Moreover, we also show that the proposed approach can leverage a large amount of unlabeled data for FHVAE training to learn domain-invariant features for DID, and significantly improve the performance in a low-resource condition, where the labels for the in-domain data are not available.

##### Abstract (translated by Google)
在本文中，我们探索使用分解层次变分自动编码器（FHVAE）模型来学习方言识别（DID）的无监督潜在表示。 FHVAE可以通过将它们编码为两组不同的潜在变量来学习将话语中的更多静态属性与更多动态属性分开的潜在空间。用于方言识别的有用因素，例如语音或语言内容，由分段潜变量编码，而在序列内相对恒定的无关因子，例如频道或说话者信息，由顺序潜变量编码。解缠结特性使得分段潜变量不易受到信道和扬声器变化的影响，从而减少了信道域失配的劣化。我们证明，在完全监督的DID任务中，与在传统声学特征和基于i矢量的系统上训练的相同模型相比，从FHVAE模型中提取的特征训练的端到端模型实现了最佳性能。此外，我们还表明，所提出的方法可以利用大量未标记的数据进行FHVAE培训，以学习DID的域不变特性，并在资源较低的情况下显着提高性能，其中域内数据的标签不可用。

##### URL
[http://arxiv.org/abs/1809.04458](http://arxiv.org/abs/1809.04458)

##### PDF
[http://arxiv.org/pdf/1809.04458](http://arxiv.org/pdf/1809.04458)

