---
layout: post
title: "Beam Search Strategies for Neural Machine Translation"
date: 2017-06-14 01:00:18
categories: arXiv_CL
tags: arXiv_CL NMT
author: Markus Freitag, Yaser Al-Onaizan
mathjax: true
---

* content
{:toc}

##### Abstract
The basic concept in Neural Machine Translation (NMT) is to train a large Neural Network that maximizes the translation performance on a given parallel corpus. NMT is then using a simple left-to-right beam-search decoder to generate new translations that approximately maximize the trained conditional probability. The current beam search strategy generates the target sentence word by word from left-to- right while keeping a fixed amount of active candidates at each time step. First, this simple search is less adaptive as it also expands candidates whose scores are much worse than the current best. Secondly, it does not expand hypotheses if they are not within the best scoring candidates, even if their scores are close to the best one. The latter one can be avoided by increasing the beam size until no performance improvement can be observed. While you can reach better performance, this has the draw- back of a slower decoding speed. In this paper, we concentrate on speeding up the decoder by applying a more flexible beam search strategy whose candidate size may vary at each time step depending on the candidate scores. We speed up the original decoder by up to 43% for the two language pairs German-English and Chinese-English without losing any translation quality.

##### Abstract (translated by Google)
神经机器翻译（NMT）的基本概念是训练一个大的神经网络，使给定平行语料库的翻译性能最大化。然后，NMT使用简单的从左到右的波束搜索解码器来生成新的翻译，其近似地最大化训练的条件概率。目前的波束搜索策略在每个时间步长保持固定的活动候选数量的同时，逐字地从左到右地生成目标句子。首先，这个简单的搜索不够灵活，因为它也扩大了分数比当前最差的候选者。其次，如果它们不在最好的得分候选者范围内，即使他们的得分接近最佳，也不会扩大假设。后者可以通过增加光束直径来避免，直到没有观察到性能改善。虽然可以达到更好的性能，但是这会降低解码速度。在本文中，我们专注于通过应用更灵活的波束搜索策略来加速解码器，其候选大小可以在每个时间步长取决于候选分数而变化。我们将原有的解码器的速度提高了43％，而德语，英语和汉英两种语言的翻译质量没有下降。

##### URL
[https://arxiv.org/abs/1702.01806](https://arxiv.org/abs/1702.01806)

