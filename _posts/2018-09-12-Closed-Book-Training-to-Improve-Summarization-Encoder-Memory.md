---
layout: post
title: "Closed-Book Training to Improve Summarization Encoder Memory"
date: 2018-09-12 17:50:07
categories: arXiv_AI
tags: arXiv_AI Salient Attention Summarization
author: Yichen Jiang, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
A good neural sequence-to-sequence summarization model should have a strong encoder that can distill and memorize the important information from long input texts so that the decoder can generate salient summaries based on the encoder's memory. In this paper, we aim to improve the memorization capabilities of the encoder of a pointer-generator model by adding an additional 'closed-book' decoder without attention and pointer mechanisms. Such a decoder forces the encoder to be more selective in the information encoded in its memory state because the decoder can't rely on the extra information provided by the attention and possibly copy modules, and hence improves the entire model. On the CNN/Daily Mail dataset, our 2-decoder model outperforms the baseline significantly in terms of ROUGE and METEOR metrics, for both cross-entropy and reinforced setups (and on human evaluation). Moreover, our model also achieves higher scores in a test-only DUC-2002 generalizability setup. We further present a memory ability test, two saliency metrics, as well as several sanity-check ablations (based on fixed-encoder, gradient-flow cut, and model capacity) to prove that the encoder of our 2-decoder model does in fact learn stronger memory representations than the baseline encoder.

##### Abstract (translated by Google)
一个好的神经序列到序列汇总模型应该有一个强大的编码器，可以从长输入文本中提取和记忆重要信息，以便解码器可以根据编码器的内存生成显着的摘要。在本文中，我们的目标是通过添加额外的“闭书”解码器来提高指针生成器模型的编码器的记忆能力，而无需注意和指针机制。这种解码器迫使编码器在其存储器状态中编码的信息中更具选择性，因为解码器不能依赖注意力提供的额外信息并且可能复制模块，因此改善了整个模型。在CNN /每日邮报数据集中，对于交叉熵和强化设置（以及人类评估），我们的2解码器模型在ROUGE和METEOR指标方面显着优于基线。此外，我们的模型在仅测试DUC-2002普遍性设置中也获得了更高的分数。我们进一步提出了一个记忆能力测试，两个显着性度量，以及几个健全性检查消融（基于固定编码器，梯度流切割和模型容量），以证明我们的2解码器模型的编码器确实学习比基线编码器更强的记忆表示。

##### URL
[http://arxiv.org/abs/1809.04585](http://arxiv.org/abs/1809.04585)

##### PDF
[http://arxiv.org/pdf/1809.04585](http://arxiv.org/pdf/1809.04585)

