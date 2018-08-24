---
layout: post
title: "SwitchOut: an Efficient Data Augmentation Algorithm for Neural Machine Translation"
date: 2018-08-22 18:26:43
categories: arXiv_CL
tags: arXiv_CL Optimization NMT
author: Xinyi Wang, Hieu Pham, Zihang Dai, Graham Neubig
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we examine methods for data augmentation for text-based tasks such as neural machine translation (NMT). We formulate the design of a data augmentation policy with desirable properties as an optimization problem, and derive a generic analytic solution. This solution not only subsumes some existing augmentation schemes, but also leads to an extremely simple data augmentation strategy for NMT: randomly replacing words in both the source sentence and the target sentence with other random words from their corresponding vocabularies. We name this method SwitchOut. Experiments on three translation datasets of different scales show that SwitchOut yields consistent improvements of about 0.5 BLEU, achieving better or comparable performances to strong alternatives such as word dropout (Sennrich et al., 2016a). Code to implement this method is included in the appendix.

##### Abstract (translated by Google)
在这项工作中，我们研究了基于文本的任务（如神经机器翻译（NMT））的数据增强方法。我们制定了数据增强策略的设计，将期​​望的属性作为优化问题，并推导出通用的分析解决方案。该解决方案不仅包含一些现有的增强方案，而且还导致NMT的极其简单的数据增强策略：用来自相应词汇表的其他随机词随机替换源句和目标句中的单词。我们将此方法命名为SwitchOut。对不同尺度的三个翻译数据集的实验表明，SwitchOut产生约0.5 BLEU的一致改进，实现了与诸如字丢失等强选择性的更好或相当的性能（Sennrich等，2016a）。实现此方法的代码包含在附录中。

##### URL
[http://arxiv.org/abs/1808.07512](http://arxiv.org/abs/1808.07512)

##### PDF
[http://arxiv.org/pdf/1808.07512](http://arxiv.org/pdf/1808.07512)

