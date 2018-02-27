---
layout: post
title: "Syntax-Directed Variational Autoencoder for Structured Data"
date: 2018-02-24 02:34:40
categories: arXiv_CL
tags: arXiv_CL Optimization
author: Hanjun Dai, Yingtao Tian, Bo Dai, Steven Skiena, Le Song
mathjax: true
---

* content
{:toc}

##### Abstract
Deep generative models have been enjoying success in modeling continuous data. However it remains challenging to capture the representations for discrete structures with formal grammars and semantics, e.g., computer programs and molecular structures. How to generate both syntactically and semantically correct data still remains largely an open problem. Inspired by the theory of compiler where the syntax and semantics check is done via syntax-directed translation (SDT), we propose a novel syntax-directed variational autoencoder (SD-VAE) by introducing stochastic lazy attributes. This approach converts the offline SDT check into on-the-fly generated guidance for constraining the decoder. Comparing to the state-of-the-art methods, our approach enforces constraints on the output space so that the output will be not only syntactically valid, but also semantically reasonable. We evaluate the proposed model with applications in programming language and molecules, including reconstruction and program/molecule optimization. The results demonstrate the effectiveness in incorporating syntactic and semantic constraints in discrete generative models, which is significantly better than current state-of-the-art approaches.

##### Abstract (translated by Google)
深度生成模型在连续数据建模中取得了成功。然而，捕捉具有正式语法和语义的离散结构的表示，例如计算机程序和分子结构，仍然是一个挑战。如何生成语法和语义上正确的数据仍然是一个悬而未决的问题。受语法和语义检查通过语法指导翻译（SDT）完成的编译器理论的启发，我们通过引入随机惰性属性提出了一种新的语法指导变分自动编码器（SD-VAE）。这种方法将离线的SDT检查转换为用于约束解码器的即时生成指导。与最先进的方法相比，我们的方法强制对输出空间进行约束，以便输出不仅在语法上有效，而且在语义上合理。我们用编程语言和分子的应用来评估所提出的模型，包括重建和程序/分子优化。结果表明，将离散生成模型中的句法和语义约束结合起来是有效的，这比当前最先进的方法要好得多。

##### URL
[http://arxiv.org/abs/1802.08786](http://arxiv.org/abs/1802.08786)

##### PDF
[http://arxiv.org/pdf/1802.08786](http://arxiv.org/pdf/1802.08786)

