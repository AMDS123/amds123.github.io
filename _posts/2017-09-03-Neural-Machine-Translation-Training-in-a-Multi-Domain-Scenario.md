---
layout: post
title: "Neural Machine Translation Training in a Multi-Domain Scenario"
date: 2017-09-03 13:01:59
categories: arXiv_CL
tags: arXiv_CL
author: Hassan Sajjad, Nadir Durrani, Fahim Dalvi, Yonatan Belinkov, Stephan Vogel
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we explore alternative ways to train a neural machine translation system in a multi-domain scenario. We investigate data concatenation (with fine tuning), model stacking (multi-level fine tuning), data selection and weighted ensemble. We evaluate these methods based on three criteria: i) translation quality, ii) training time, and iii) robustness towards out-of-domain tests. Our findings on Arabic-English and German-English language pairs show that the best translation quality can be achieved by building an initial system on a concatenation of available out-of-domain data and then fine-tuning it on in-domain data. Model stacking works best when training begins with the furthest out-of-domain data and the model is incrementally fine-tuned with the next furthest domain and so on. Data selection did not give the best results, but can be considered as a decent compromise between training time and translation quality. A weighted ensemble of different individual models performed better than data selection. It is beneficial in a scenario when there is no time for fine-tuning.

##### Abstract (translated by Google)
在本文中，我们探索了在多领域情景下训练神经机器翻译系统的替代方法。我们调查数据级联（微调），模型堆积（多级微调），数据选择和加权集成。我们根据三个标准评估这些方法：i）翻译质量，ii）训练时间，以及iii）对域外测试的稳健性。我们对阿拉伯语 - 英语和德语 - 英语语言对的研究结果表明，通过在可用的域外数据串联上构建初始系统，然后在域内数据上对其进行微调，可以实现最佳的翻译质量。当训练从最远的域外数据开始进行训练时，模型堆积效果最好，并且模型以下一个最远的域进行增量微调，等等。数据选择并没有给出最好的结果，但可以认为是培训时间和翻译质量之间的一个体面的妥协。不同个体模型的加权集合表现比数据选择更好。在没有时间进行微调的情况下，这是有益的。

##### URL
[https://arxiv.org/abs/1708.08712](https://arxiv.org/abs/1708.08712)

##### PDF
[https://arxiv.org/pdf/1708.08712](https://arxiv.org/pdf/1708.08712)

