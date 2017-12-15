---
layout: post
title: "Pointer Sentinel Mixture Models"
date: 2016-09-26 04:06:13
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model Prediction
author: Stephen Merity, Caiming Xiong, James Bradbury, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Recent neural network sequence models with softmax classifiers have achieved their best language modeling performance only with very large hidden states and large vocabularies. Even then they struggle to predict rare or unseen words even if the context makes the prediction unambiguous. We introduce the pointer sentinel mixture architecture for neural sequence models which has the ability to either reproduce a word from the recent context or produce a word from a standard softmax classifier. Our pointer sentinel-LSTM model achieves state of the art language modeling performance on the Penn Treebank (70.9 perplexity) while using far fewer parameters than a standard softmax LSTM. In order to evaluate how well language models can exploit longer contexts and deal with more realistic vocabularies and larger corpora we also introduce the freely available WikiText corpus.

##### Abstract (translated by Google)
最近的使用softmax分类器的神经网络序列模型只有在非常大的隐藏状态和大的词汇表时才能达到最好的语言建模性能。即便如此，即使上下文使得预测毫不含糊，他们也难以预测难得的或看不见的单词。我们引入了神经序列模型的指针哨兵混合体系结构，它能够从最近的上下文中重现一个单词，或者从标准的softmax分类器产生一个单词。我们的指针sentinel-LSTM模型实现了Penn Treebank（70.9的困惑度）上最先进的语言建模性能，而使用的参数远远少于标准的softmax LSTM。为了评估语言模型如何更好地利用更长的上下文，处理更真实的词汇和更大的语料库，我们还引入了免费的WikiText语料库。

##### URL
[https://arxiv.org/abs/1609.07843](https://arxiv.org/abs/1609.07843)

##### PDF
[https://arxiv.org/pdf/1609.07843](https://arxiv.org/pdf/1609.07843)

