---
layout: post
title: "Monotonic Chunkwise Attention"
date: 2017-12-14 18:29:42
categories: arXiv_CL
tags: arXiv_CL Attention Summarization Speech_Recognition Recognition
author: Chung-Cheng Chiu, Colin Raffel
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence models with soft attention have been successfully applied to a wide variety of problems, but their decoding process incurs a quadratic time and space cost and is inapplicable to real-time sequence transduction. To address these issues, we propose Monotonic Chunkwise Attention (MoChA), which adaptively splits the input sequence into small chunks over which soft attention is computed. We show that models utilizing MoChA can be trained efficiently with standard backpropagation while allowing online and linear-time decoding at test time. When applied to online speech recognition, we obtain state-of-the-art results and match the performance of a model using an offline soft attention mechanism. In document summarization experiments where we do not expect monotonic alignments, we show significantly improved performance compared to a baseline monotonic attention-based model.

##### Abstract (translated by Google)
软注意的序列 - 序列模型已经成功地应用于各种各样的问题，但是它们的解码过程产生二次时间和空间成本，并且不适用于实时序列转换。为了解决这些问题，我们提出了Monotonic Chunkwise Attention（MoChA），它将输入序列自适应地分割成小块，从而计算软注意力。我们表明，使用MoChA的模型可以用标准反向传播进行有效训练，同时允许在测试时进行在线和线性时间解码。当应用于在线语音识别时，我们获得了最新的结果，并使用离线软注意机制来匹配模型的性能。在不期望单调对齐的文档摘要实验中，与基线单调注意模型相比，我们显示出显着改进的性能。

##### URL
[http://arxiv.org/abs/1712.05382](http://arxiv.org/abs/1712.05382)

##### PDF
[http://arxiv.org/pdf/1712.05382](http://arxiv.org/pdf/1712.05382)

