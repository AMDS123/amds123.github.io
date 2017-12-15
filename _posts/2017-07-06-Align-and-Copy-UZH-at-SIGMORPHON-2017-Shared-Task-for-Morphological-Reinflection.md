---
layout: post
title: "Align and Copy: UZH at SIGMORPHON 2017 Shared Task for Morphological Reinflection"
date: 2017-07-06 10:09:44
categories: arXiv_CL
tags: arXiv_CL Attention
author: Peter Makarov, Tatiana Ruzsics, Simon Clematide
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents the submissions by the University of Zurich to the SIGMORPHON 2017 shared task on morphological reinflection. The task is to predict the inflected form given a lemma and a set of morpho-syntactic features. We focus on neural network approaches that can tackle the task in a limited-resource setting. As the transduction of the lemma into the inflected form is dominated by copying over lemma characters, we propose two recurrent neural network architectures with hard monotonic attention that are strong at copying and, yet, substantially different in how they achieve this. The first approach is an encoder-decoder model with a copy mechanism. The second approach is a neural state-transition system over a set of explicit edit actions, including a designated COPY action. We experiment with character alignment and find that naive, greedy alignment consistently produces strong results for some languages. Our best system combination is the overall winner of the SIGMORPHON 2017 Shared Task 1 without external resources. At a setting with 100 training samples, both our approaches, as ensembles of models, outperform the next best competitor.

##### Abstract (translated by Google)
本文介绍了苏黎世大学提交的SIGMORPHON 2017形态反射共享任务。任务是根据引理和一组形态句法特征来预测变形的形式。我们专注于可以在有限的资源环境中解决任务的神经网络方法。由于引理转化为变形形式主要是通过复制引理字符，所以我们提出了两种复杂的神经网络结构，它们具有强烈的单调注意力，它们在复制时很强大，然而，它们在如何实现这一点方面有很大的不同。第一种方法是具有复制机制的编码器 - 解码器模型。第二种方法是通过一组显式编辑操作（包括指定的COPY操作）的神经状态转换系统。我们尝试了字符对齐，发现天真的贪婪对齐对于某些语言来说始终会产生很好的结果。我们最好的系统组合是SIGMORPHON 2017共享任务1的总冠军，无需外部资源。在100个训练样本的设置下，我们的两种模式都能超越下一个最好的竞争对手。

##### URL
[https://arxiv.org/abs/1707.01355](https://arxiv.org/abs/1707.01355)

##### PDF
[https://arxiv.org/pdf/1707.01355](https://arxiv.org/pdf/1707.01355)

