---
layout: post
title: "Fast Domain Adaptation for Neural Machine Translation"
date: 2016-12-20 22:07:51
categories: arXiv_CL
tags: arXiv_CL NMT
author: Markus Freitag, Yaser Al-Onaizan
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) is a new approach for automatic translation of text from one human language into another. The basic concept in NMT is to train a large Neural Network that maximizes the translation performance on a given parallel corpus. NMT is gaining popularity in the research community because it outperformed traditional SMT approaches in several translation tasks at WMT and other evaluation tasks/benchmarks at least for some language pairs. However, many of the enhancements in SMT over the years have not been incorporated into the NMT framework. In this paper, we focus on one such enhancement namely domain adaptation. We propose an approach for adapting a NMT system to a new domain. The main idea behind domain adaptation is that the availability of large out-of-domain training data and a small in-domain training data. We report significant gains with our proposed method in both automatic metrics and a human subjective evaluation metric on two language pairs. With our adaptation method, we show large improvement on the new domain while the performance of our general domain only degrades slightly. In addition, our approach is fast enough to adapt an already trained system to a new domain within few hours without the need to retrain the NMT model on the combined data which usually takes several days/weeks depending on the volume of the data.

##### Abstract (translated by Google)
神经机器翻译（NMT）是一种将文本从一种人类语言自动翻译成另一种语言的新方法。 NMT的基本概念是训练一个大的神经网络，使给定平行语料库的翻译性能最大化。 NMT在研究界越来越受欢迎，因为在WMT和其他评估任务/基准测试中，至少对于某些语言对，它在传统的SMT方法上表现优于传统的SMT方法。然而，多年来SMT中的许多改进还没有被纳入NMT框架。在本文中，我们着重于这样一个增强，即域的适应。我们提出了一个适应NMT系统到一个新的领域的方法。领域适应背后的主要思想是可以获得大量的领域外训练数据和小型的领域训练数据。我们在自动度量和两个语言对的人类主观评估度量上报告了我们提出的方法的显着收益。用我们的自适应方法，我们在新的领域表现出了很大的改进，而我们的通用领域的表现只有轻微的下降。此外，我们的方法足够快，可以在几个小时内将已经培训好的系统调整到一个新的领域，而不需要根据数据量对NMT模型重新进行组合数据的重新训练。

##### URL
[https://arxiv.org/abs/1612.06897](https://arxiv.org/abs/1612.06897)

