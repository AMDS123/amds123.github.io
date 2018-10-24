---
layout: post
title: "Ain't Nobody Got Time For Coding: Structure-Aware Program Synthesis From Natural Language"
date: 2018-10-23 08:29:11
categories: arXiv_AI
tags: arXiv_AI Attention Embedding RNN
author: Jakub Bednarek, Karol Piaskowski, Krzysztof Krawiec
mathjax: true
---

* content
{:toc}

##### Abstract
Program synthesis from natural language (NL) is practical for humans and, once technically feasible, would significantly facilitate software development and revolutionize end-user programming. We present SAPS, an end-to-end neural network capable of mapping relatively complex, multi-sentence NL specifications to snippets of executable code. The proposed architecture relies exclusively on neural components, and is built upon a tree2tree autoencoder trained on abstract syntax trees, combined with a pretrained word embedding and a bi-directional multi-layer LSTM for NL processing. The decoder features a doubly-recurrent LSTM with a novel signal propagation scheme and soft attention mechanism. When applied to a large dataset of problems proposed in a previous study, SAPS performs on par with or better than the method proposed there, producing correct programs in over 90% of cases. In contrast to other methods, it does not involve any non-neural components to post-process the resulting programs, and uses a fixed-dimensional latent representation as the only link between the NL analyzer and source code generator.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09717](http://arxiv.org/abs/1810.09717)

##### PDF
[http://arxiv.org/pdf/1810.09717](http://arxiv.org/pdf/1810.09717)

