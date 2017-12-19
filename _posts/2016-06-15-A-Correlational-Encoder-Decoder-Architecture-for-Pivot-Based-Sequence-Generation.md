---
layout: post
title: "A Correlational Encoder Decoder Architecture for Pivot Based Sequence Generation"
date: 2016-06-15 13:27:16
categories: arXiv_CV
tags: arXiv_CV GAN Caption Relation
author: Amrita Saha, Mitesh M. Khapra, Sarath Chandar, Janarthanan Rajendran, Kyunghyun Cho
mathjax: true
---

* content
{:toc}

##### Abstract
Interlingua based Machine Translation (MT) aims to encode multiple languages into a common linguistic representation and then decode sentences in multiple target languages from this representation. In this work we explore this idea in the context of neural encoder decoder architectures, albeit on a smaller scale and without MT as the end goal. Specifically, we consider the case of three languages or modalities X, Z and Y wherein we are interested in generating sequences in Y starting from information available in X. However, there is no parallel training data available between X and Y but, training data is available between X & Z and Z & Y (as is often the case in many real world applications). Z thus acts as a pivot/bridge. An obvious solution, which is perhaps less elegant but works very well in practice is to train a two stage model which first converts from X to Z and then from Z to Y. Instead we explore an interlingua inspired solution which jointly learns to do the following (i) encode X and Z to a common representation and (ii) decode Y from this common representation. We evaluate our model on two tasks: (i) bridge transliteration and (ii) bridge captioning. We report promising results in both these applications and believe that this is a right step towards truly interlingua inspired encoder decoder architectures.

##### Abstract (translated by Google)
基于国际语的机器翻译（Interlingua based Machine Translation，MT）旨在将多种语言编码为一种通用的语言表达，然后根据这种表示方式对多种目标语言的句子进行解码。在这项工作中，我们在神经编码器解码器架构的背景下探索这个想法，虽然规模较小，没有MT作为最终目标。具体而言，我们考虑三种语言或模态X，Z和Y的情况，其中我们感兴趣的是从X中可用的信息开始在Y中生成序列。然而，在X和Y之间没有可用的并行训练数据，但是训练数据是在X＆Z和Z＆Y之间可用（在许多现实世界的应用中通常是这种情况）。 Z因此作为枢轴/桥。一个明显的解决方案可能不那么优雅，但在实践中运作得非常好，那就是训练一个两阶段模型，先从X到Z然后从Z到Y，然后我们探索一个interlingua启发的解决方案，共同学习如下（i）将X和Z编码为公共表示，并（ii）从该公共表示中解码Y.我们评估我们的模型的两个任务：（一）桥音译和（二）桥梁字幕。我们在这两个应用程序中报告了有希望的结果，并相信这是真正意义上的interlingua编码器解码器架构的一个正确的步骤。

##### URL
[https://arxiv.org/abs/1606.04754](https://arxiv.org/abs/1606.04754)

##### PDF
[https://arxiv.org/pdf/1606.04754](https://arxiv.org/pdf/1606.04754)

