---
layout: post
title: "Guiding Neural Machine Translation with Retrieved Translation Pieces"
date: 2018-04-07 13:20:24
categories: arXiv_CL
tags: arXiv_CL Salient NMT
author: Jingyi Zhang, Masao Utiyama, Eiichro Sumita, Graham Neubig, Satoshi Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
One of the difficulties of neural machine translation (NMT) is the recall and appropriate translation of low-frequency words or phrases. In this paper, we propose a simple, fast, and effective method for recalling previously seen translation examples and incorporating them into the NMT decoding process. Specifically, for an input sentence, we use a search engine to retrieve sentence pairs whose source sides are similar with the input sentence, and then collect $n$-grams that are both in the retrieved target sentences and aligned with words that match in the source sentences, which we call "translation pieces". We compute pseudo-probabilities for each retrieved sentence based on similarities between the input sentence and the retrieved source sentences, and use these to weight the retrieved translation pieces. Finally, an existing NMT model is used to translate the input sentence, with an additional bonus given to outputs that contain the collected translation pieces. We show our method improves NMT translation results up to 6 BLEU points on three narrow domain translation tasks where repetitiveness of the target sentences is particularly salient. It also causes little increase in the translation time, and compares favorably to another alternative retrieval-based method with respect to accuracy, speed, and simplicity of implementation.

##### Abstract (translated by Google)
神经机器翻译（NMT）的困难之一是召回和适当翻译低频词或短语。在本文中，我们提出了一个简单，快速和有效的方法来回忆以前看到的翻译例子，并将它们纳入NMT解码过程。具体而言，对于输入句子，我们使用搜索引擎来检索其源端与输入句子相似的句对，然后收集在检索到的目标句子中的$ n $ -grams，并且与在源句子，我们称之为“翻译件”。我们根据输入句子与检索到的源语句之间的相似度计算每个检索到的句子的伪概率，并用它们来加权检索到的翻译片段。最后，使用现有的NMT模型来翻译输入句子，并为输出包含收集的翻译片段提供额外的奖励。我们展示了我们的方法在三个狭窄领域翻译任务中将NMT翻译结果提高到6个BLEU点，其中目标语句的重复性特别突出。它也使翻译时间几乎没有增加，并且在准确性，速度和实施简单性方面与另一种替代的基于检索的方法相比有利。

##### URL
[https://arxiv.org/abs/1804.02559](https://arxiv.org/abs/1804.02559)

##### PDF
[https://arxiv.org/pdf/1804.02559](https://arxiv.org/pdf/1804.02559)

