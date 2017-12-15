---
layout: post
title: "Learning Python Code Suggestion with a Sparse Pointer Network"
date: 2016-11-24 21:01:46
categories: arXiv_CL
tags: arXiv_CL Sparse RNN Language_Model Prediction
author: Avishkar Bhoopchand, Tim Rocktäschel, Earl Barr, Sebastian Riedel
mathjax: true
---

* content
{:toc}

##### Abstract
To enhance developer productivity, all modern integrated development environments (IDEs) include code suggestion functionality that proposes likely next tokens at the cursor. While current IDEs work well for statically-typed languages, their reliance on type annotations means that they do not provide the same level of support for dynamic programming languages as for statically-typed languages. Moreover, suggestion engines in modern IDEs do not propose expressions or multi-statement idiomatic code. Recent work has shown that language models can improve code suggestion systems by learning from software repositories. This paper introduces a neural language model with a sparse pointer network aimed at capturing very long-range dependencies. We release a large-scale code suggestion corpus of 41M lines of Python code crawled from GitHub. On this corpus, we found standard neural language models to perform well at suggesting local phenomena, but struggle to refer to identifiers that are introduced many tokens in the past. By augmenting a neural language model with a pointer network specialized in referring to predefined classes of identifiers, we obtain a much lower perplexity and a 5 percentage points increase in accuracy for code suggestion compared to an LSTM baseline. In fact, this increase in code suggestion accuracy is due to a 13 times more accurate prediction of identifiers. Furthermore, a qualitative analysis shows this model indeed captures interesting long-range dependencies, like referring to a class member defined over 60 tokens in the past.

##### Abstract (translated by Google)
为了提高开发人员的工作效率，所有现代集成开发环境（IDE）都包含代码建议功能，这些功能可能会在游标处提供可能的令牌。虽然目前的IDE在静态类型语言中运行良好，但是它们对类型注释的依赖意味着它们不能像静态类型语言那样为动态编程语言提供相同级别的支持。此外，现代IDE中的建议引擎不提出表达式或多语句惯用代码。最近的工作表明，语言模型可以通过从软件库中学习来改进代码建议系统。本文介绍了一个具有稀疏指针网络的神经语言模型，旨在捕获非常长的依赖关系。我们发布了一个从GitHub爬取的41M代码的大规模代码建议语料库。在这个语料库中，我们发现标准的神经语言模型在表达当地现象方面表现良好，但是很难提及过去引入了许多标记的标识符。通过使用专门指代预定义的标识符类的指针网络来增强神经语言模型，与LSTM基线相比，我们获得了更低的困惑性和代码建议的准确度提高了5个百分点。实际上，代码建议准确度的提高是由于对标识符的预测精度提高了13倍。此外，定性分析表明，这个模型确实捕获了有趣的远程依赖关系，就像过去指定一个超过60个令牌的类成员一样。

##### URL
[https://arxiv.org/abs/1611.08307](https://arxiv.org/abs/1611.08307)

##### PDF
[https://arxiv.org/pdf/1611.08307](https://arxiv.org/pdf/1611.08307)

