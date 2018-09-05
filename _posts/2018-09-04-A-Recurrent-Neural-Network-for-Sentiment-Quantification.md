---
layout: post
title: "A Recurrent Neural Network for Sentiment Quantification"
date: 2018-09-04 08:41:53
categories: arXiv_CL
tags: arXiv_CL Sentiment Embedding Classification Prediction
author: Andrea Esuli, Alejandro Moreo Fern&#xe1;ndez, Fabrizio Sebastiani
mathjax: true
---

* content
{:toc}

##### Abstract
Quantification is a supervised learning task that consists in predicting, given a set of classes C and a set D of unlabelled items, the prevalence (or relative frequency) p(c|D) of each class c in C. Quantification can in principle be solved by classifying all the unlabelled items and counting how many of them have been attributed to each class. However, this "classify and count" approach has been shown to yield suboptimal quantification accuracy; this has established quantification as a task of its own, and given rise to a number of methods specifically devised for it. We propose a recurrent neural network architecture for quantification (that we call QuaNet) that observes the classification predictions to learn higher-order "quantification embeddings", which are then refined by incorporating quantification predictions of simple classify-and-count-like methods. We test {QuaNet on sentiment quantification on text, showing that it substantially outperforms several state-of-the-art baselines.

##### Abstract (translated by Google)
量化是一种监督学习任务，其包括在给定一组C类和未标记项目的集合D的情况下预测C中每个类别c的普遍性（或相对频率）p（c | D）。量化原则上可以是通过对所有未标记的项目进行分类并计算其中有多少项属于每个类别来解决。然而，这种“分类和计数”方法已被证明可以产生次优的量化准确度;这已经将量化确定为其自身的任务，并产生了一些专门为其设计的方法。我们提出了一种用于量化的递归神经网络架构（我们称之为QuaNet），它遵循分类预测来学习更高阶的“量化嵌入”，然后通过结合简单的分类和计数方法的量化预测来改进。我们测试{QuaNet关于文本的情绪量化，表明它基本上优于几个最先进的基线。

##### URL
[http://arxiv.org/abs/1809.00836](http://arxiv.org/abs/1809.00836)

##### PDF
[http://arxiv.org/pdf/1809.00836](http://arxiv.org/pdf/1809.00836)

