---
layout: post
title: "Disentangling by Partitioning: A Representation Learning Framework for Multimodal Sensory Data"
date: 2018-05-29 06:45:02
categories: arXiv_CL
tags: arXiv_CL Represenation_Learning Inference Classification Quantitative
author: Wei-Ning Hsu, James Glass
mathjax: true
---

* content
{:toc}

##### Abstract
Multimodal sensory data resembles the form of information perceived by humans for learning, and are easy to obtain in large quantities. Compared to unimodal data, synchronization of concepts between modalities in such data provides supervision for disentangling the underlying explanatory factors of each modality. Previous work leveraging multimodal data has mainly focused on retaining only the modality-invariant factors while discarding the rest. In this paper, we present a partitioned variational autoencoder (PVAE) and several training objectives to learn disentangled representations, which encode not only the shared factors, but also modality-dependent ones, into separate latent variables. Specifically, PVAE integrates a variational inference framework and a multimodal generative model that partitions the explanatory factors and conditions only on the relevant subset of them for generation. We evaluate our model on two parallel speech/image datasets, and demonstrate its ability to learn disentangled representations by qualitatively exploring within-modality and cross-modality conditional generation with semantics and styles specified by examples. For quantitative analysis, we evaluate the classification accuracy of automatically discovered semantic units. Our PVAE can achieve over 99% accuracy on both modalities.

##### Abstract (translated by Google)
多模态感觉数据类似于人类为了学习而感知的信息的形式，并且很容易大量获得。与单峰数据相比，这种数据中模态之间概念的同步提供了监督，以解开每种模态的基本解释因素。利用多模式数据的先前工作主要集中在只保留模态不变因素，而忽略其余部分。在本文中，我们提出了一个分区变分自动编码器（PVAE）和几个培训目标来学习解缠表示，它不仅将共享因子编码，而且还编码依赖于模态的变量，分解为不同的潜变量。具体而言，PVAE集成了变分推理框架和多模式生成模型，该模型将解释性因素和条件仅分配给相关子集进行生成。我们在两个并行的语音/图像数据集上评估我们的模型，并通过定性地探索内部模态和跨模态条件生成（通过示例指定的语义和样式）来演示其学习解开表示的能力。对于定量分析，我们评估自动发现的语义单元的分类准确性。我们的PVAE在两种模式上都可以达到99％以上的准确度。

##### URL
[http://arxiv.org/abs/1805.11264](http://arxiv.org/abs/1805.11264)

##### PDF
[http://arxiv.org/pdf/1805.11264](http://arxiv.org/pdf/1805.11264)

