---
layout: post
title: "Multi-channel Encoder for Neural Machine Translation"
date: 2017-12-06 09:59:43
categories: arXiv_CL
tags: arXiv_CL NMT RNN
author: Hao Xiong, Zhongjun He, Xiaoguang Hu, Hua Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Attention-based Encoder-Decoder has the effective architecture for neural machine translation (NMT), which typically relies on recurrent neural networks (RNN) to build the blocks that will be lately called by attentive reader during the decoding process. This design of encoder yields relatively uniform composition on source sentence, despite the gating mechanism employed in encoding RNN. On the other hand, we often hope the decoder to take pieces of source sentence at varying levels suiting its own linguistic structure: for example, we may want to take the entity name in its raw form while taking an idiom as a perfectly composed unit. Motivated by this demand, we propose Multi-channel Encoder (MCE), which enhances encoding components with different levels of composition. More specifically, in addition to the hidden state of encoding RNN, MCE takes 1) the original word embedding for raw encoding with no composition, and 2) a particular design of external memory in Neural Turing Machine (NTM) for more complex composition, while all three encoding strategies are properly blended during decoding. Empirical study on Chinese-English translation shows that our model can improve by 6.52 BLEU points upon a strong open source NMT system: DL4MT1. On the WMT14 English- French task, our single shallow system achieves BLEU=38.8, comparable with the state-of-the-art deep models.

##### Abstract (translated by Google)
基于注意的编码器 - 解码器具有神经机器翻译（NMT）的有效架构，其通常依赖于递归神经网络（RNN）来构建将在解码过程中由细心的读取器最近呼叫的块。尽管在编码RNN时使用了门控机制，但是这种编码器的设计在源语句上产生相对均匀的组合。另一方面，我们常常希望解码器在不同的层次上采取适合自己的语言结构的源句，例如，我们可能希望以其原始形式采用实体名称，而将习语作为完全合成的单位。受这种需求的驱动，我们提出了多通道编码器（MCE），其增强了具有不同级别组成的编码组件。更具体地说，除了编码RNN的隐藏状态之外，MCE还采取1）用于未编码的原始编码的原始字嵌入，以及2）用于更复杂构图的神经图灵机（NTM）中的外部存储器的特定设计，所有三种编码策略在解码期间被适当地混合。汉英翻译实证研究表明，我们的模型在一个强大的开源NMT系统上可以提高6.52 BLEU点：DL4MT1。在WMT14英语 - 法语任务中，我们的单一浅层系统达到了BLEU = 38.8，与最先进的深层模型相当。

##### URL
[http://arxiv.org/abs/1712.02109](http://arxiv.org/abs/1712.02109)

##### PDF
[http://arxiv.org/pdf/1712.02109](http://arxiv.org/pdf/1712.02109)

