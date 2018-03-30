---
layout: post
title: "Multi-range Reasoning for Machine Comprehension"
date: 2018-03-24 08:10:04
categories: arXiv_AI
tags: arXiv_AI QA RNN Relation
author: Yi Tay, Luu Anh Tuan, Siu Cheung Hui
mathjax: true
---

* content
{:toc}

##### Abstract
We propose MRU (Multi-Range Reasoning Units), a new fast compositional encoder for machine comprehension (MC). Our proposed MRU encoders are characterized by multi-ranged gating, executing a series of parameterized contract-and-expand layers for learning gating vectors that benefit from long and short-term dependencies. The aims of our approach are as follows: (1) learning representations that are concurrently aware of long and short-term context, (2) modeling relationships between intra-document blocks and (3) fast and efficient sequence encoding. We show that our proposed encoder demonstrates promising results both as a standalone encoder and as well as a complementary building block. We conduct extensive experiments on three challenging MC datasets, namely RACE, SearchQA and NarrativeQA, achieving highly competitive performance on all. On the RACE benchmark, our model outperforms DFN (Dynamic Fusion Networks) by 1.5%-6% without using any recurrent or convolution layers. Similarly, we achieve competitive performance relative to AMANDA on the SearchQA benchmark and BiDAF on the NarrativeQA benchmark without using any LSTM/GRU layers. Finally, incorporating MRU encoders with standard BiLSTM architectures further improves performance, achieving state-of-the-art results.

##### Abstract (translated by Google)
我们提出MRU（多范围推理单元），一种用于机器理解（MC）的新型快速合成编码器。我们提出的MRU编码器的特点是多范围选通，执行一系列参数化的合同 - 扩展层，用于学习受长期和短期依赖性影响的门控向量。我们的方法的目标如下：（1）同时知道长期和短期背景的学习表示，（2）建模文档内部块之间的关系和（3）快速和有效的序列编码。我们表明，我们提出的编码器作为独立的编码器和互补的构建块展现出了前景光明的结果。我们对三个具有挑战性的MC数据集进行了广泛的实验，即RACE，SearchQA和NarrativeQA，从而实现了极具竞争力的性能。在RACE基准测试中，我们的模型在不使用任何经常性或卷积层的情况下，性能优于DFN（动态融合网络）1.5％-6％。同样，我们在没有使用任何LSTM / GRU层的情况下，在SearchQA基准测试中获得与AMANDA相竞争的表现，在NarrativeQA基准测试中获得BiDAF。最后，将MRU编码器与标准BiLSTM架构结合在一起，进一步提高了性能，实现了最先进的结果。

##### URL
[https://arxiv.org/abs/1803.09074](https://arxiv.org/abs/1803.09074)

##### PDF
[https://arxiv.org/pdf/1803.09074](https://arxiv.org/pdf/1803.09074)

