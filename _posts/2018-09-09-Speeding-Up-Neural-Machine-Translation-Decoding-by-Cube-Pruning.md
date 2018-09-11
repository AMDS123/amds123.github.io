---
layout: post
title: "Speeding Up Neural Machine Translation Decoding by Cube Pruning"
date: 2018-09-09 15:45:25
categories: arXiv_AI
tags: arXiv_AI RNN
author: Wen Zhang, Liang Huang, Yang Feng, Lei Shen, Qun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Although neural machine translation has achieved promising results, it suffers from slow translation speed. The direct consequence is that a trade-off has to be made between translation quality and speed, thus its performance can not come into full play. We apply cube pruning, a popular technique to speed up dynamic programming, into neural machine translation to speed up the translation. To construct the equivalence class, similar target hidden states are combined, leading to less RNN expansion operations on the target side and less \$\mathrm{softmax}\$ operations over the large target vocabulary. The experiments show that, at the same or even better translation quality, our method can translate faster compared with naive beam search by \$3.3\times\$ on GPUs and \$3.5\times\$ on CPUs.

##### Abstract (translated by Google)
虽然神经机器翻译已取得了可喜的成果，但它的翻译速度很慢。直接后果是必须在翻译质量和速度之间进行权衡，因此其性能无法充分发挥。我们将立方体修剪（一种用于加速动态编程的流行技术）应用于神经机器翻译以加速翻译。为了构造等价类，组合了类似的目标隐藏状态，导致目标端的RNN扩展操作更少，并且对大目标词汇表的操作更少。实验表明，在相同甚至更好的翻译质量下，与原始光束搜索相比，我们的方法可以更快地转换为GPU上的\ $ 3.3 \ times \ $和CPU上的\ $ 3.5 \ times \ $。

##### URL
[http://arxiv.org/abs/1809.02992](http://arxiv.org/abs/1809.02992)

##### PDF
[http://arxiv.org/pdf/1809.02992](http://arxiv.org/pdf/1809.02992)

