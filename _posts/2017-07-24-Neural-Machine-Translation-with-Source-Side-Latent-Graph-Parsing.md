---
layout: post
title: "Neural Machine Translation with Source-Side Latent Graph Parsing"
date: 2017-07-24 14:52:06
categories: arXiv_CL
tags: arXiv_CL NMT
author: Kazuma Hashimoto, Yoshimasa Tsuruoka
---

* content
{:toc}

##### Abstract
This paper presents a novel neural machine translation model which jointly learns translation and source-side latent graph representations of sentences. Unlike existing pipelined approaches using syntactic parsers, our end-to-end model learns a latent graph parser as part of the encoder of an attention-based neural machine translation model, and thus the parser is optimized according to the translation objective. In experiments, we first show that our model compares favorably with state-of-the-art sequential and pipelined syntax-based NMT models. We also show that the performance of our model can be further improved by pre-training it with a small amount of treebank annotations. Our final ensemble model significantly outperforms the previous best models on the standard English-to-Japanese translation dataset.

##### Abstract (translated by Google)
本文提出了一种新的神经机器翻译模型，它共同学习句子的翻译和源侧潜在图表示。与使用语法分析器的现有流水线方法不同，我们的端到端模型将潜在图解析器学习为基于注意的神经机器翻译模型的编码器的一部分，因此解析器根据翻译目标进行优化。在实验中，我们首先表明我们的模型与最先进的顺序和流水线语法NMT模型相比较。我们还表明，我们的模型的性能可以通过预先训练少量的树库注释来进一步提高。我们的最终整体模型显着优于标准的英文 - 日文翻译数据集的以前的最佳模型。

##### URL
[https://arxiv.org/abs/1702.02265](https://arxiv.org/abs/1702.02265)

