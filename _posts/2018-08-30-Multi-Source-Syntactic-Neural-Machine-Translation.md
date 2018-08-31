---
layout: post
title: "Multi-Source Syntactic Neural Machine Translation"
date: 2018-08-30 13:18:57
categories: arXiv_CL
tags: arXiv_CL Attention
author: Anna Currey, Kenneth Heafield
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel multi-source technique for incorporating source syntax into neural machine translation using linearized parses. This is achieved by employing separate encoders for the sequential and parsed versions of the same source sentence; the resulting representations are then combined using a hierarchical attention mechanism. The proposed model improves over both seq2seq and parsed baselines by over 1 BLEU on the WMT17 English-German task. Further analysis shows that our multi-source syntactic model is able to translate successfully without any parsed input, unlike standard parsed methods. In addition, performance does not deteriorate as much on long sentences as for the baselines.

##### Abstract (translated by Google)
我们介绍了一种新颖的多源技术，使用线性化解析将源语法合并到神经机器翻译中。这是通过对同一源句的顺序和解析版本使用单独的编码器来实现的;然后使用分层注意机制组合所得到的表示。在WMT17英语 - 德语任务中，所提出的模型在seq2seq和解析的基线上都提高了1个BLEU。进一步的分析表明，与标准的解析方法不同，我们的多源语法模型能够在没有任何解析输入的情况下成功翻译。此外，长期句子的表现不会像基线那样恶化。

##### URL
[http://arxiv.org/abs/1808.10267](http://arxiv.org/abs/1808.10267)

##### PDF
[http://arxiv.org/pdf/1808.10267](http://arxiv.org/pdf/1808.10267)

