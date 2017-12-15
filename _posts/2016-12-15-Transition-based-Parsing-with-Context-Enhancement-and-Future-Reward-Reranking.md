---
layout: post
title: "Transition-based Parsing with Context Enhancement and Future Reward Reranking"
date: 2016-12-15 16:30:11
categories: arXiv_CL
tags: arXiv_CL RNN
author: Fugen Zhou, Fuxiang Wu, Zhengchen Zhang, Minghui Dong
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel reranking model, future reward reranking, to re-score the actions in a transition-based parser by using a global scorer. Different to conventional reranking parsing, the model searches for the best dependency tree in all feasible trees constraining by a sequence of actions to get the future reward of the sequence. The scorer is based on a first-order graph-based parser with bidirectional LSTM, which catches different parsing view compared with the transition-based parser. Besides, since context enhancement has shown substantial improvement in the arc-stand transition-based parsing over the parsing accuracy, we implement context enhancement on an arc-eager transition-base parser with stack LSTMs, the dynamic oracle and dropout supporting and achieve further improvement. With the global scorer and context enhancement, the results show that UAS of the parser increases as much as 1.20% for English and 1.66% for Chinese, and LAS increases as much as 1.32% for English and 1.63% for Chinese. Moreover, we get state-of-the-art LASs, achieving 87.58% for Chinese and 93.37% for English.

##### Abstract (translated by Google)
本文提出了一种新型的重新排序模型，未来的奖励重新排序，通过使用全球记录器重新评分基于过渡的解析器中的动作。与传统的排序分析不同，该模型通过一系列动作来约束所有可行的树中的最佳依赖树，以获得序列的未来奖励。记分器基于一个基于一阶图解的双向LSTM解析器，与基于转换的解析器相比，捕获不同的解析视图。此外，由于上下文增强在基于弧 - 站转换的解析中显着提高了解析精度，因此我们在具有堆栈LSTM的弧 - 转换 - 基础解析器上实现上下文增强，动态oracle和dropout支持并实现进一步改进。通过全球记分器和上下文的增强，结果显示解析器的UAS增加了1.20％，英文增加1.66％，英文增加1.32％，中文增加1.63％。此外，我们获得了最先进的LASs，中文为87.58％，英文为93.37％。

##### URL
[https://arxiv.org/abs/1612.05131](https://arxiv.org/abs/1612.05131)

##### PDF
[https://arxiv.org/pdf/1612.05131](https://arxiv.org/pdf/1612.05131)

