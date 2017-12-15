---
layout: post
title: "Global-Context Neural Machine Translation through Target-Side Attentive Residual Connections"
date: 2017-09-26 15:51:21
categories: arXiv_CL
tags: arXiv_CL Attention Language_Model
author: Lesly Miculicich Werlen, Nikolaos Pappas, Dhananjay Ram, Andrei Popescu-Belis
mathjax: true
---

* content
{:toc}

##### Abstract
Neural sequence-to-sequence models achieve remarkable performance not only in machine translation (MT) but also in other language processing tasks. One of the reasons for their effectiveness is the ability of their decoder to capture contextual information through its recurrent layer. However, its sequential modeling over-emphasizes the local context, i.e. the previously translated word in the case of MT. As a result, the model ignores important information from the global context of the translation. In this paper, we address this limitation by introducing attentive residual connections from the previously translated words to the output of the decoder, which enable the learning of longer-range dependencies between words. The proposed model can emphasize any of the previously translated words, as opposed to only the last one, gaining access to the global context of the translated text. The model outperforms strong neural MT baselines on three language pairs, as well as a neural language modeling baseline. The analysis of the attention learned by the decoder confirms that it emphasizes a wide context, and reveals resemblance to syntactic-like structures.

##### Abstract (translated by Google)
神经序列 - 序列模型不仅在机器翻译（MT）中而且在其他语言处理任务中都实现了显着的性能。其有效性的原因之一是其解码器通过其循环层捕获上下文信息的能力。然而，它的顺序建模过分强调了本地的情况，即在MT的情况下，先前翻译的字。因此，该模型忽略了全球范围内翻译的重要信息。在本文中，我们通过引入来自先前翻译的单词到解码器的输出的细致的剩余连接来解决这个限制，这使得能够学习单词之间的较长范围的依赖性。所提出的模型可以强调任何以前翻译的单词，而不仅仅是最后一个，获得翻译文本的全球背景。该模型优于三个语言对上强大的神经MT基线，以及神经语言建模基线。对解码器所学习到的注意力的分析证实它强调了广泛的语境，并且揭示了类似于句法结构的相似性。

##### URL
[https://arxiv.org/abs/1709.04849](https://arxiv.org/abs/1709.04849)

##### PDF
[https://arxiv.org/pdf/1709.04849](https://arxiv.org/pdf/1709.04849)

