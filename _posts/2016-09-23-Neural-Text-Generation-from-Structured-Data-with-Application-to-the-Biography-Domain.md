---
layout: post
title: "Neural Text Generation from Structured Data with Application to the Biography Domain"
date: 2016-09-23 15:16:46
categories: arXiv_SD
tags: arXiv_SD Text_Generation Language_Model
author: Remi Lebret, David Grangier, Michael Auli
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a neural model for concept-to-text generation that scales to large, rich domains. We experiment with a new dataset of biographies from Wikipedia that is an order of magnitude larger than existing resources with over 700k samples. The dataset is also vastly more diverse with a 400k vocabulary, compared to a few hundred words for Weathergov or Robocup. Our model builds upon recent work on conditional neural language model for text generation. To deal with the large vocabulary, we extend these models to mix a fixed vocabulary with copy actions that transfer sample-specific words from the input database to the generated output sentence. Our neural model significantly out-performs a classical Kneser-Ney language model adapted to this task by nearly 15 BLEU.

##### Abstract (translated by Google)
本文介绍了一个概念到文本生成的神经模型，可扩展到大而丰富的领域。我们试用维基百科传记的新数据集，其数量比现有资源大700多个样本。数据集也更多样化，词汇量为400k，而Weathergov或Robocup则为数百个单词。我们的模型建立在最近关于文本生成的条件神经语言模型上。为了处理庞大的词汇量，我们扩展了这些模型，将固定的词汇与复制行为混合在一起，从输入数据库中将样本特定的单词转换为生成的输出句子。我们的神经模型大大超出了近15个BLEU的经典Kneser-Ney语言模型。

##### URL
[https://arxiv.org/abs/1603.07771](https://arxiv.org/abs/1603.07771)

##### PDF
[https://arxiv.org/pdf/1603.07771](https://arxiv.org/pdf/1603.07771)

