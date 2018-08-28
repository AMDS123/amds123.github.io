---
layout: post
title: "Dissecting Contextual Word Embeddings: Architecture and Representation"
date: 2018-08-27 17:54:29
categories: arXiv_CL
tags: arXiv_CL Attention Embedding RNN Language_Model
author: Matthew E. Peters, Mark Neumann, Luke Zettlemoyer, Wen-tau Yih
mathjax: true
---

* content
{:toc}

##### Abstract
Contextual word representations derived from pre-trained bidirectional language models (biLMs) have recently been shown to provide significant improvements to the state of the art for a wide range of NLP tasks. However, many questions remain as to how and why these models are so effective. In this paper, we present a detailed empirical study of how the choice of neural architecture (e.g. LSTM, CNN, or self attention) influences both end task accuracy and qualitative properties of the representations that are learned. We show there is a tradeoff between speed and accuracy, but all architectures learn high quality contextual representations that outperform word embeddings for four challenging NLP tasks. Additionally, all architectures learn representations that vary with network depth, from exclusively morphological based at the word embedding layer through local syntax based in the lower contextual layers to longer range semantics such coreference at the upper layers. Together, these results suggest that unsupervised biLMs, independent of architecture, are learning much more about the structure of language than previously appreciated.

##### Abstract (translated by Google)
最近已经显示从预训练的双向语言模型（biLM）导出的上下文单词表示为广泛的NLP任务提供了对现有技术的显着改进。但是，关于这些模型如何以及为何如此有效，仍然存在许多问题。在本文中，我们提出了一个详细的实证研究，探讨神经结构的选择（例如LSTM，CNN或自我关注）如何影响最终任务的准确性和所学习的表征的定性属性。我们展示了速度和准确性之间的权衡，但所有体系结构都学习了高质量的上下文表示，这些表示优于四个具有挑战性的NLP任务的字嵌入。此外，所有体系结构都学习随网络深度而变化的表示，从基于单词嵌入层的形态学到基于较低上下文层的本地语法，再到较高范围的语义，例如上层的共同参照。总之，这些结果表明，无人监督的biLM，独立于建筑，正在学习更多关于语言结构的知识。

##### URL
[http://arxiv.org/abs/1808.08949](http://arxiv.org/abs/1808.08949)

##### PDF
[http://arxiv.org/pdf/1808.08949](http://arxiv.org/pdf/1808.08949)

