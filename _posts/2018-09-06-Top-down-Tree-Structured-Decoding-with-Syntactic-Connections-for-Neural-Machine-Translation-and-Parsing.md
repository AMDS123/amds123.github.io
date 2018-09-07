---
layout: post
title: "Top-down Tree Structured Decoding with Syntactic Connections for Neural Machine Translation and Parsing"
date: 2018-09-06 07:33:48
categories: arXiv_CL
tags: arXiv_CL Attention NMT RNN
author: Jetic G&#x16b;, Hassan S. Shavarani, Anoop Sarkar
mathjax: true
---

* content
{:toc}

##### Abstract
The addition of syntax-aware decoding in Neural Machine Translation (NMT) systems requires an effective tree-structured neural network, a syntax-aware attention model and a language generation model that is sensitive to sentence structure. We exploit a top-down tree-structured model called DRNN (Doubly-Recurrent Neural Networks) first proposed by Alvarez-Melis and Jaakola (2017) to create an NMT model called Seq2DRNN that combines a sequential encoder with tree-structured decoding augmented with a syntax-aware attention model. Unlike previous approaches to syntax-based NMT which use dependency parsing models our method uses constituency parsing which we argue provides useful information for translation. In addition, we use the syntactic structure of the sentence to add new connections to the tree-structured decoder neural network (Seq2DRNN+SynC). We compare our NMT model with sequential and state of the art syntax-based NMT models and show that our model produces more fluent translations with better reordering. Since our model is capable of doing translation and constituency parsing at the same time we also compare our parsing accuracy against other neural parsing models.

##### Abstract (translated by Google)
在神经机器翻译（NMT）系统中添加语法感知解码需要有效的树形结构神经网络，语法感知注意模型和对句子结构敏感的语言生成模型。我们利用Alvarez-Melis和Jaakola（2017）首先提出的名为DRNN（双回归神经网络）的自上而下的树状结构模型来创建一个名为Seq2DRNN的NMT模型，该模型将顺序编码器与树结构解码相结合，增强了语法感知注意模型。与先前使用依赖性解析模型的基于语法的NMT的方法不同，我们的方法使用选区解析，我们认为它提供了有用的翻译信息。此外，我们使用句子的句法结构来添加到树形结构的解码器神经网络（Seq2DRNN + SynC）的新连接。我们将NMT模型与顺序和最先进的基于语法的NMT模型进行比较，并表明我们的模型可以生成更流畅的翻译，并具有更好的重新排序。由于我们的模型能够同时进行翻译和选区解析，因此我们还将解析精度与其他神经解析模型进行比较。

##### URL
[http://arxiv.org/abs/1809.01854](http://arxiv.org/abs/1809.01854)

##### PDF
[http://arxiv.org/pdf/1809.01854](http://arxiv.org/pdf/1809.01854)

