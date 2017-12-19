---
layout: post
title: "A Bayesian Model for Generative Transition-based Dependency Parsing"
date: 2015-06-28 21:18:50
categories: arXiv_CL
tags: arXiv_CL Inference Language_Model
author: Jan Buys, Phil Blunsom
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a simple, scalable, fully generative model for transition-based dependency parsing with high accuracy. The model, parameterized by Hierarchical Pitman-Yor Processes, overcomes the limitations of previous generative models by allowing fast and accurate inference. We propose an efficient decoding algorithm based on particle filtering that can adapt the beam size to the uncertainty in the model while jointly predicting POS tags and parse trees. The UAS of the parser is on par with that of a greedy discriminative baseline. As a language model, it obtains better perplexity than a n-gram model by performing semi-supervised learning over a large unlabelled corpus. We show that the model is able to generate locally and syntactically coherent sentences, opening the door to further applications in language generation.

##### Abstract (translated by Google)
我们提出一个简单的，可扩展的，完全生成的模型，用于高精度的基于转换的依赖分析。该模型通过分层Pitman-Yor过程参数化，通过允许快速和准确的推断克服了先前的生成模型的局限性。我们提出了一种基于粒子滤波的高效解码算法，该算法能够在对模型的不确定性进行光束大小调整的同时，联合预测POS标签和解析树。解析器的UAS与贪婪的判别基线相同。作为一种语言模型，通过在一个大的未标记的语料库上进行半监督学习，它比n-gram模型获得了更好的困惑。我们表明，模型能够产生本地和句法连贯的句子，打开进一步的应用程序在语言生成的大门。

##### URL
[https://arxiv.org/abs/1506.04334](https://arxiv.org/abs/1506.04334)

##### PDF
[https://arxiv.org/pdf/1506.04334](https://arxiv.org/pdf/1506.04334)

