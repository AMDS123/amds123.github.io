---
layout: post
title: "From Characters to Words to in Between: Do We Capture Morphology?"
date: 2017-04-26 21:10:53
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model
author: Clara Vania, Adam Lopez
mathjax: true
---

* content
{:toc}

##### Abstract
Words can be represented by composing the representations of subword units such as word segments, characters, and/or character n-grams. While such representations are effective and may capture the morphological regularities of words, they have not been systematically compared, and it is not understood how they interact with different morphological typologies. On a language modeling task, we present experiments that systematically vary (1) the basic unit of representation, (2) the composition of these representations, and (3) the morphological typology of the language modeled. Our results extend previous findings that character representations are effective across typologies, and we find that a previously unstudied combination of character trigram representations composed with bi-LSTMs outperforms most others. But we also find room for improvement: none of the character-level models match the predictive accuracy of a model with access to true morphological analyses, even when learned from an order of magnitude more data.

##### Abstract (translated by Google)
词可以通过组成诸如词段，字符和/或字符n-gram之类的子字单元的表示来表示。虽然这样的表征是有效的，可能捕捉词的形态规律性，但是它们还没有系统地进行比较，并且不了解它们是如何与不同的形态类型相互作用的。在语言建模任务上，我们提出了系统地改变（1）表示的基本单位，（2）这些表示的组成，（3）模型的语言形态类型的实验。我们的结果扩展了先前的发现，即字符表示在类型学上是有效的，并且我们发现先前没有研究的由双LSTM组成的字符三角形表示的组合优于其他大多数。但是我们也找到了改进的余地：即使从更多的数据量学习，没有一个字符级模型与模型的预测准确性相匹配，也没有获得真正的形态分析。

##### URL
[https://arxiv.org/abs/1704.08352](https://arxiv.org/abs/1704.08352)

##### PDF
[https://arxiv.org/pdf/1704.08352](https://arxiv.org/pdf/1704.08352)

