---
layout: post
title: "Local System Voting Feature for Machine Translation System Combination"
date: 2017-02-10 01:27:00
categories: arXiv_SD
tags: arXiv_SD
author: Markus Freitag, Jan-Thorsten Peter, Stephan Peitz, Minwei Feng, Hermann Ney
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we enhance the traditional confusion network system combination approach with an additional model trained by a neural network. This work is motivated by the fact that the commonly used binary system voting models only assign each input system a global weight which is responsible for the global impact of each input system on all translations. This prevents individual systems with low system weights from having influence on the system combination output, although in some situations this could be helpful. Further, words which have only been seen by one or few systems rarely have a chance of being present in the combined output. We train a local system voting model by a neural network which is based on the words themselves and the combinatorial occurrences of the different system outputs. This gives system combination the option to prefer other systems at different word positions even for the same sentence.

##### Abstract (translated by Google)
在本文中，我们通过神经网络训练的附加模型来增强传统的混淆网络系统组合方法。这项工作的动机是，常用的二进制系统投票模式只为每个输入系统分配一个全球权重，这个权重对每个输入系统对全部翻译的全局影响负责。这可以防止具有较低系统权重的单个系统对系统组合输出产生影响，尽管在某些情况下这可能会有所帮助。此外，只有一个或几个系统才能看到的单词很少有机会出现在组合输出中。我们通过神经网络训练本地系统投票模型，神经网络基于单词本身和不同系统输出的组合事件。这使得系统组合可以选择不同词位置的其他系统，即使是相同的句子。

##### URL
[https://arxiv.org/abs/1702.03033](https://arxiv.org/abs/1702.03033)

##### PDF
[https://arxiv.org/pdf/1702.03033](https://arxiv.org/pdf/1702.03033)

