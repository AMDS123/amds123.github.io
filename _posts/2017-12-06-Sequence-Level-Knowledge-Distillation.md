---
layout: post
title: 'Sequence-Level Knowledge Distillation'
date: 2017-12-06 09:36:23
categories: arXiv_CL
tags: arXiv_CL NMT
author: Yoon Kim, Alexander M. Rush
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) offers a novel alternative formulation of translation that is potentially simpler than statistical approaches. However to reach competitive performance, NMT models need to be exceedingly large. In this paper we consider applying knowledge distillation approaches (Bucila et al., 2006; Hinton et al., 2015) that have proven successful for reducing the size of neural models in other domains to the problem of NMT. We demonstrate that standard knowledge distillation applied to word-level prediction can be effective for NMT, and also introduce two novel sequence-level versions of knowledge distillation that further improve performance, and somewhat surprisingly, seem to eliminate the need for beam search (even when applied on the original teacher model). Our best student model runs 10 times faster than its state-of-the-art teacher with little loss in performance. It is also significantly better than a baseline model trained without knowledge distillation: by 4.2/1.7 BLEU with greedy decoding/beam search. Applying weight pruning on top of knowledge distillation results in a student model that has 13 times fewer parameters than the original teacher model, with a decrease of 0.4 BLEU.

##### Abstract (translated by Google)
神经机器翻译（NMT）为翻译提供了一种新颖的替代形式，比统计方法更简单。但是要达到竞争的表现，NMT模型需要非常大。在本文中，我们考虑应用知识蒸馏方法（Bucila等人，2006; Hinton等人，2015），已经证明成功地将其他领域的神经模型的规模缩小到NMT的问题。我们证明，适用于词级预测的标准知识升级对于NMT可能是有效的，并且还引入了两个新颖的序列级别的知识升级版本，进一步提高了性能，并且有些令人吃惊的是，似乎消除了对束搜索的需求应用于原来的教师模型）。我们最好的学生模式比其最先进的老师速度快10倍，而且性能损失不大。它也明显好于没有知识蒸馏训练的基线模型：通过贪婪的解码/波束搜索，达到4.2 / 1.7 BLEU。在知识蒸馏之上应用体重修剪会导致学生模型的参数比原来的教师模型少13倍，减少0.4 BLEU。

##### URL
[https://arxiv.org/abs/1606.07947](https://arxiv.org/abs/1606.07947)

