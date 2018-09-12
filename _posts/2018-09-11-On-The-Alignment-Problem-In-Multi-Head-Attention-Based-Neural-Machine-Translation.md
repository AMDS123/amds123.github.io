---
layout: post
title: "On The Alignment Problem In Multi-Head Attention-Based Neural Machine Translation"
date: 2018-09-11 15:41:12
categories: arXiv_CL
tags: arXiv_CL Attention NMT
author: Tamer Alkhouli, Gabriel Bretschner, Hermann Ney
mathjax: true
---

* content
{:toc}

##### Abstract
This work investigates the alignment problem in state-of-the-art multi-head attention models based on the transformer architecture. We demonstrate that alignment extraction in transformer models can be improved by augmenting an additional alignment head to the multi-head source-to-target attention component. This is used to compute sharper attention weights. We describe how to use the alignment head to achieve competitive performance. To study the effect of adding the alignment head, we simulate a dictionary-guided translation task, where the user wants to guide translation using pre-defined dictionary entries. Using the proposed approach, we achieve up to $3.8$ % BLEU improvement when using the dictionary, in comparison to $2.4$ % BLEU in the baseline case. We also propose alignment pruning to speed up decoding in alignment-based neural machine translation (ANMT), which speeds up translation by a factor of $1.8$ without loss in translation performance. We carry out experiments on the shared WMT 2016 English$\to$Romanian news task and the BOLT Chinese$\to$English discussion forum task.

##### Abstract (translated by Google)
这项工作研究了基于变压器架构的最先进的多头注意模型中的对准问题。我们证明了变换器模型中的对齐提取可以通过增加额外的对齐头到多头源到目标注意组件来改进。这用于计算更清晰的注意力。我们将介绍如何使用校准头来实现竞争性能。为了研究添加对齐头的效果，我们模拟了字典引导的翻译任务，其中用户想要使用预定义的字典条目来指导翻译。使用所提出的方法，我们在使用字典时实现了高达3.8美元$ B％的BLEU改进，而基线情况下则为2.4美元％BLEU。我们还提出了对齐修剪，以加快基于对齐的神经机器翻译（ANMT）中的解码速度，从而在不降低翻译性能的情况下将翻译速度提高1.8美元。我们在共享WMT 2016英语$ \ to $ Romanian新闻任务和BOLT中文$ \ to $ English讨论论坛任务上进行实验。

##### URL
[http://arxiv.org/abs/1809.03985](http://arxiv.org/abs/1809.03985)

##### PDF
[http://arxiv.org/pdf/1809.03985](http://arxiv.org/pdf/1809.03985)

