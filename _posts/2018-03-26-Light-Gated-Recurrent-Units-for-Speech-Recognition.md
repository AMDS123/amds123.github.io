---
layout: post
title: "Light Gated Recurrent Units for Speech Recognition"
date: 2018-03-26 17:48:18
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition RNN Deep_Learning Recognition
author: Mirco Ravanelli, Philemon Brakel, Maurizio Omologo, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
A field that has directly benefited from the recent advances in deep learning is Automatic Speech Recognition (ASR). Despite the great achievements of the past decades, however, a natural and robust human-machine speech interaction still appears to be out of reach, especially in challenging environments characterized by significant noise and reverberation. To improve robustness, modern speech recognizers often employ acoustic models based on Recurrent Neural Networks (RNNs), that are naturally able to exploit large time contexts and long-term speech modulations. It is thus of great interest to continue the study of proper techniques for improving the effectiveness of RNNs in processing speech signals. In this paper, we revise one of the most popular RNN models, namely Gated Recurrent Units (GRUs), and propose a simplified architecture that turned out to be very effective for ASR. The contribution of this work is two-fold: First, we analyze the role played by the reset gate, showing that a significant redundancy with the update gate occurs. As a result, we propose to remove the former from the GRU design, leading to a more efficient and compact single-gate model. Second, we propose to replace hyperbolic tangent with ReLU activations. This variation couples well with batch normalization and could help the model learn long-term dependencies without numerical issues. Results show that the proposed architecture, called Light GRU (Li-GRU), not only reduces the per-epoch training time by more than 30% over a standard GRU, but also consistently improves the recognition accuracy across different tasks, input features, noisy conditions, as well as across different ASR paradigms, ranging from standard DNN-HMM speech recognizers to end-to-end CTC models.

##### Abstract (translated by Google)
自动语音识别（ASR）是一个直接受益于近期深度学习进展的领域。然而，尽管过去几十年取得了巨大成就，但自然而强大的人机语音交互似乎仍遥不可及，特别是在具有显着噪音和混响特征的具有挑战性的环境中。为了提高鲁棒性，现代语音识别器通常采用基于递归神经网络（RNN）的声学模型，这些模型自然能够利用大时间背景和长期语音调制。因此，继续研究用于提高RNN在处理语音信号中的有效性的适当技术是非常有意义的。在本文中，我们修改了最受欢迎的RNN模型之一，即门控重发单元（GRU），并提出了一个简化的体系结构，对于ASR非常有效。这项工作的贡献有两个方面：首先，我们分析重置门的作用，表明出现更新门的重要冗余。因此，我们建议从GRU设计中删除前者，从而导致更高效和紧凑的单门模型。其次，我们建议用ReLU激活代替双曲正切。这种变化与批量归一化很好地结合在一起，可以帮助模型学习长期依赖关系，而不会产生数值问题。结果表明，所提出的称为Light GRU（Li-GRU）的体系结构不仅使每个历元训练时间比标准GRU降低30％以上，而且不断地提高不同任务之间的识别精度，输入特征，噪声条件以及跨越不同的ASR范例，从标准的DNN-HMM语音识别器到端到端的CTC模型。

##### URL
[https://arxiv.org/abs/1803.10225](https://arxiv.org/abs/1803.10225)

##### PDF
[https://arxiv.org/pdf/1803.10225](https://arxiv.org/pdf/1803.10225)

