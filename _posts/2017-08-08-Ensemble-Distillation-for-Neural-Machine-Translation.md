---
layout: post
title: "Ensemble Distillation for Neural Machine Translation"
date: 2017-08-08 01:41:25
categories: arXiv_CL
tags: arXiv_CL NMT
author: Markus Freitag, Yaser Al-Onaizan, Baskaran Sankaran
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge distillation describes a method for training a student network to perform better by learning from a stronger teacher network. Translating a sentence with an Neural Machine Translation (NMT) engine is time expensive and having a smaller model speeds up this process. We demonstrate how to transfer the translation quality of an ensemble and an oracle BLEU teacher network into a single NMT system. Further, we present translation improvements from a teacher network that has the same architecture and dimensions of the student network. As the training of the student model is still expensive, we introduce a data filtering method based on the knowledge of the teacher model that not only speeds up the training, but also leads to better translation quality. Our techniques need no code change and can be easily reproduced with any NMT architecture to speed up the decoding process.

##### Abstract (translated by Google)
知识蒸馏描述了通过从更强大的教师网络学习来训练学生网络以更好地执行的方法。用神经机器翻译（NMT）引擎翻译一个句子是耗时的，而且有一个较小的模型可以加速这个过程。我们演示了如何将一个合奏和一个甲骨文BLEU教师网络的翻译质量转换成一个NMT系统。此外，我们从具有与学生网络相同架构和维度的教师网络展示翻译改进。由于学生模型的训练仍然很昂贵，我们引入了基于教师模型知识的数据过滤方法，不仅加快了训练速度，而且提高了翻译质量。我们的技术不需要更改代码，并且可以使用任何NMT架构轻松复制，以加速解码过程。

##### URL
[https://arxiv.org/abs/1702.01802](https://arxiv.org/abs/1702.01802)

