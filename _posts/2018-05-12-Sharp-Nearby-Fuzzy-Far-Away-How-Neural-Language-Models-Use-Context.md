---
layout: post
title: "Sharp Nearby, Fuzzy Far Away: How Neural Language Models Use Context"
date: 2018-05-12 00:26:29
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Urvashi Khandelwal, He He, Peng Qi, Dan Jurafsky
mathjax: true
---

* content
{:toc}

##### Abstract
We know very little about how neural language models (LM) use prior linguistic context. In this paper, we investigate the role of context in an LSTM LM, through ablation studies. Specifically, we analyze the increase in perplexity when prior context words are shuffled, replaced, or dropped. On two standard datasets, Penn Treebank and WikiText-2, we find that the model is capable of using about 200 tokens of context on average, but sharply distinguishes nearby context (recent 50 tokens) from the distant history. The model is highly sensitive to the order of words within the most recent sentence, but ignores word order in the long-range context (beyond 50 tokens), suggesting the distant past is modeled only as a rough semantic field or topic. We further find that the neural caching model (Grave et al., 2017b) especially helps the LSTM to copy words from within this distant context. Overall, our analysis not only provides a better understanding of how neural LMs use their context, but also sheds light on recent success from cache-based models.

##### Abstract (translated by Google)
我们对神经语言模型（LM）如何在语言环境之前使用知之甚少。在本文中，我们通过消融研究来研究背景在LSTM LM中的作用。具体而言，我们分析了之前的情境词语被洗牌，替换或丢弃时困惑的增加。在两个标准数据集Penn Treebank和WikiText-2上，我们发现该模型平均可以使用大约200个令牌，但是可以将远程历史中的近似背景（最近的50个令牌）区分开来。该模型对最近一句话中的单词顺序高度敏感，但忽略了远程语境中的单词顺序（超过50个单词），这表明遥远的过去仅被建模为粗略的语义领域或主题。我们进一步发现神经缓存模型（Grave et al。，2017b）特别有助于LSTM从这种遥远的语境中复制单词。总的来说，我们的分析不仅更好地理解神经LM如何使用它们的上下文，还揭示了基于缓存模型的最近成功。

##### URL
[https://arxiv.org/abs/1805.04623](https://arxiv.org/abs/1805.04623)

##### PDF
[https://arxiv.org/pdf/1805.04623](https://arxiv.org/pdf/1805.04623)

