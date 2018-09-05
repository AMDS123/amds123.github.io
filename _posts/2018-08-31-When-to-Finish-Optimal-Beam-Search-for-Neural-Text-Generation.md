---
layout: post
title: "When to Finish? Optimal Beam Search for Neural Text Generation"
date: 2018-08-31 22:01:48
categories: arXiv_CL
tags: arXiv_CL Image_Caption Summarization Text_Generation Caption
author: Liang Huang, Kai Zhao, Mingbo Ma
mathjax: true
---

* content
{:toc}

##### Abstract
In neural text generation such as neural machine translation, summarization, and image captioning, beam search is widely used to improve the output text quality. However, in the neural generation setting, hypotheses can finish in different steps, which makes it difficult to decide when to end beam search to ensure optimality. We propose a provably optimal beam search algorithm that will always return the optimal-score complete hypothesis (modulo beam size), and finish as soon as the optimality is established (finishing no later than the baseline). To counter neural generation's tendency for shorter hypotheses, we also introduce a bounded length reward mechanism which allows a modified version of our beam search algorithm to remain optimal. Experiments on neural machine translation demonstrate that our principled beam search algorithm leads to improvement in BLEU score over previously proposed alternatives.

##### Abstract (translated by Google)
在神经文本生成（例如神经机器翻译，摘要和图像字幕）中，波束搜索被广泛用于提高输出文本质量。然而，在神经生成设置中，假设可以在不同的步骤中完成，这使得难以确定何时结束波束搜索以确保最优性。我们提出了一种可证明最优的波束搜索算法，该算法将始终返回最优分数完全假设（模数波束大小），并在最优性建立后立即完成（不迟于基线完成）。为了抵消神经生成对较短假设的倾向，我们还引入了有界长度奖励机制，该机制允许我们的波束搜索算法的修改版本保持最佳。神经机器翻译的实验表明，我们的原理波束搜索算法导致BLEU得分比先前提出的替代方案有所改善。

##### URL
[http://arxiv.org/abs/1809.00069](http://arxiv.org/abs/1809.00069)

##### PDF
[http://arxiv.org/pdf/1809.00069](http://arxiv.org/pdf/1809.00069)

