---
layout: post
title: "Context-Aware Neural Machine Translation Learns Anaphora Resolution"
date: 2018-05-25 14:03:27
categories: arXiv_CL
tags: arXiv_CL Attention Relation
author: Elena Voita, Pavel Serdyukov, Rico Sennrich, Ivan Titov
mathjax: true
---

* content
{:toc}

##### Abstract
Standard machine translation systems process sentences in isolation and hence ignore extra-sentential information, even though extended context can both prevent mistakes in ambiguous cases and improve translation coherence. We introduce a context-aware neural machine translation model designed in such way that the flow of information from the extended context to the translation model can be controlled and analyzed. We experiment with an English-Russian subtitles dataset, and observe that much of what is captured by our model deals with improving pronoun translation. We measure correspondences between induced attention distributions and coreference relations and observe that the model implicitly captures anaphora. It is consistent with gains for sentences where pronouns need to be gendered in translation. Beside improvements in anaphoric cases, the model also improves in overall BLEU, both over its context-agnostic version (+0.7) and over simple concatenation of the context and source sentences (+0.6).

##### Abstract (translated by Google)
标准机器翻译系统单独处理句子，因此忽略超额信息，即使扩展的上下文既可以防止模糊情况下的错误，也可以提高翻译的一致性。我们引入了一种上下文感知的神经机器翻译模型，它可以控制和分析从扩展上下文到翻译模型的信息流。我们尝试了一个英文 - 俄文字幕数据集，并观察到我们的模型所捕获的大部分内容涉及改进代词翻译。我们测量引起的注意分布和共因关系之间的对应关系，并观察模型隐含捕获照应。这与代词在翻译中需要性别化的句子的收益是一致的。除了在指示性案例中的改进之外，该模型在整个BLEU中都得到了改进，无论是通过上下文无关的版本（+0.7）还是上下文和源语句（+0.6）的简单连接。

##### URL
[http://arxiv.org/abs/1805.10163](http://arxiv.org/abs/1805.10163)

##### PDF
[http://arxiv.org/pdf/1805.10163](http://arxiv.org/pdf/1805.10163)

