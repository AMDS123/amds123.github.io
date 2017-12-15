---
layout: post
title: "RNN Approaches to Text Normalization: A Challenge"
date: 2017-01-24 19:51:12
categories: arXiv_CL
tags: arXiv_CL RNN
author: Richard Sproat, Navdeep Jaitly
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a challenge to the community: given a large corpus of written text aligned to its normalized spoken form, train an RNN to learn the correct normalization function. We present a data set of general text where the normalizations were generated using an existing text normalization component of a text-to-speech system. This data set will be released open-source in the near future. We also present our own experiments with this data set with a variety of different RNN architectures. While some of the architectures do in fact produce very good results when measured in terms of overall accuracy, the errors that are produced are problematic, since they would convey completely the wrong message if such a system were deployed in a speech application. On the other hand, we show that a simple FST-based filter can mitigate those errors, and achieve a level of accuracy not achievable by the RNN alone. Though our conclusions are largely negative on this point, we are actually not arguing that the text normalization problem is intractable using an pure RNN approach, merely that it is not going to be something that can be solved merely by having huge amounts of annotated text data and feeding that to a general RNN model. And when we open-source our data, we will be providing a novel data set for sequence-to-sequence modeling in the hopes that the the community can find better solutions. The data used in this work have been released and are available at: this https URL

##### Abstract (translated by Google)
本文向社区提出了一个挑战：给定一个大规模的书面文本语料库，使其与规范化的口语形式保持一致，通过训练一个RNN学习正确的规范化函数。我们提出一个通用文本数据集，其中使用文本到语音系统的现有文本规范化组件生成规范化。这个数据集将在近期公开发布。我们还用这个数据集和各种不同的RNN体系结构来展示我们自己的实验。虽然在总体准确度方面，一些体系结构确实产生了非常好的结果，但是产生的错误是有问题的，因为如果将这样的系统部署在语音应用程序中，它们将完全传达错误的信息。另一方面，我们展示了一个简单的基于FST的过滤器可以减轻这些错误，并达到RNN无法实现的精确度。尽管我们的结论在很大程度上是负面的，但是我们实际上并不认为文本规范化问题是使用纯粹的RNN方法难以解决的，而仅仅是因为拥有大量的注释文本数据并将其提供给一般的RNN模型。当我们开源数据时，我们将提供一个新的数据集，用于序列到序列的建模，希望社区能找到更好的解决方案。本工作中使用的数据已经发布，可在以下网址获得：https：

##### URL
[https://arxiv.org/abs/1611.00068](https://arxiv.org/abs/1611.00068)

##### PDF
[https://arxiv.org/pdf/1611.00068](https://arxiv.org/pdf/1611.00068)

