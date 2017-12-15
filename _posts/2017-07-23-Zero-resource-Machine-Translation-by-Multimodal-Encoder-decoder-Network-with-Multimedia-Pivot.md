---
layout: post
title: "Zero-resource Machine Translation by Multimodal Encoder-decoder Network with Multimedia Pivot"
date: 2017-07-23 15:52:08
categories: arXiv_CL
tags: arXiv_CL
author: Hideki Nakayama, Noriki Nishida
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an approach to build a neural machine translation system with no supervised resources (i.e., no parallel corpora) using multimodal embedded representation over texts and images. Based on the assumption that text documents are often likely to be described with other multimedia information (e.g., images) somewhat related to the content, we try to indirectly estimate the relevance between two languages. Using multimedia as the "pivot", we project all modalities into one common hidden space where samples belonging to similar semantic concepts should come close to each other, whatever the observed space of each sample is. This modality-agnostic representation is the key to bridging the gap between different modalities. Putting a decoder on top of it, our network can flexibly draw the outputs from any input modality. Notably, in the testing phase, we need only source language texts as the input for translation. In experiments, we tested our method on two benchmarks to show that it can achieve reasonable translation performance. We compared and investigated several possible implementations and found that an end-to-end model that simultaneously optimized both rank loss in multimodal encoders and cross-entropy loss in decoders performed the best.

##### Abstract (translated by Google)
我们提出了一种方法来建立一个神经机器翻译系统，没有监督资源（即没有平行的语料库）使用多模态嵌入代表文本和图像。基于假定文本文档通常可能与其他与内容有关的多媒体信息（例如图像）描述，我们试图间接估计两种语言之间的相关性。使用多媒体作为“支点”，我们将所有模态投影到一个共同的隐藏空间，不管每个样本的观察空间是多少，属于相似语义概念的样本应该彼此靠近。这种与形式无关的表现形式是弥合不同形式之间差距的关键。在它上面放置一个解码器，我们的网络可以灵活地从任何输入模式绘制输出。值得注意的是，在测试阶段，我们只需要源语言文本作为翻译的输入。在实验中，我们用两个基准测试了我们的方法，表明它可以达到合理的翻译性能。我们比较和调查了几种可能的实现，发现同时优化多模式编码器中的秩损失和解码器中的交叉熵损失的端到端模型表现最好。

##### URL
[https://arxiv.org/abs/1611.04503](https://arxiv.org/abs/1611.04503)

##### PDF
[https://arxiv.org/pdf/1611.04503](https://arxiv.org/pdf/1611.04503)

