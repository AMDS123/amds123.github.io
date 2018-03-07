---
layout: post
title: "Self-Attention with Relative Position Representations"
date: 2018-03-06 13:13:11
categories: arXiv_CL
tags: arXiv_CL Attention CNN Relation
author: Peter Shaw, Jakob Uszkoreit, Ashish Vaswani
mathjax: true
---

* content
{:toc}

##### Abstract
Relying entirely on an attention mechanism, the Transformer introduced by Vaswani et al. (2017) achieves state-of-the-art results for machine translation. In contrast to recurrent and convolutional neural networks, it does not explicitly model relative or absolute position information in its structure. Instead, it requires adding representations of absolute positions to its inputs. In this work we present an alternative approach, extending the self-attention mechanism to efficiently consider representations of the relative positions, or distances between sequence elements. On the WMT 2014 English-to-German and English-to-French translation tasks, this approach yields improvements of 1.3 BLEU and 0.3 BLEU over absolute position representations, respectively. Notably, we observe that combining relative and absolute position representations yields no further improvement in translation quality. We describe an efficient implementation of our method and cast it as an instance of relation-aware self-attention mechanisms that can generalize to arbitrary graph-labeled inputs.

##### Abstract (translated by Google)
Vaswani等人介绍的变压器完全依靠注意机制。 （2017年）实现了机器翻译的最新成果。与递归和卷积神经网络相比，它没有明确地为其结构中的相对或绝对位置信息建模。相反，它需要在其输入中添加绝对位置的表示。在这项工作中，我们提出了一种替代方法，扩展了自我注意机制以有效地考虑相对位置的表示或序列元素之间的距离。在WMT 2014英语 - 德语和英语 - 法语翻译任务中，此方法分别提高了1.3 BLEU和0.3 BLEU的绝对位置表示。值得注意的是，我们观察到，结合相对位置和绝对位置表示不会进一步提高翻译质量。我们描述了我们方法的高效实现，并将其作为关系感知自我注意机制的一个实例，可以推广到任意图形标记的输入。

##### URL
[http://arxiv.org/abs/1803.02155](http://arxiv.org/abs/1803.02155)

##### PDF
[http://arxiv.org/pdf/1803.02155](http://arxiv.org/pdf/1803.02155)

