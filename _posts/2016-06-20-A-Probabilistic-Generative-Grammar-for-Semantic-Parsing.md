---
layout: post
title: "A Probabilistic Generative Grammar for Semantic Parsing"
date: 2016-06-20 23:29:55
categories: arXiv_CL
tags: arXiv_CL Knowledge Inference
author: Abulhair Saparov, Tom M. Mitchell
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework that couples the syntax and semantics of natural language sentences in a generative model, in order to develop a semantic parser that jointly infers the syntactic, morphological, and semantic representations of a given sentence under the guidance of background knowledge. To generate a sentence in our framework, a semantic statement is first sampled from a prior, such as from a set of beliefs in a knowledge base. Given this semantic statement, a grammar probabilistically generates the output sentence. A joint semantic-syntactic parser is derived that returns the $k$-best semantic and syntactic parses for a given sentence. The semantic prior is flexible, and can be used to incorporate background knowledge during parsing, in ways unlike previous semantic parsing approaches. For example, semantic statements corresponding to beliefs in a knowledge base can be given higher prior probability, type-correct statements can be given somewhat lower probability, and beliefs outside the knowledge base can be given lower probability. The construction of our grammar invokes a novel application of hierarchical Dirichlet processes (HDPs), which in turn, requires a novel and efficient inference approach. We present experimental results showing, for a simple grammar, that our parser outperforms a state-of-the-art CCG semantic parser and scales to knowledge bases with millions of beliefs.

##### Abstract (translated by Google)
我们提出了一个框架，在生成模型中耦合自然语言句子的语法和语义，以开发一个语义解析器，在背景知识的指导下联合推断给定句子的句法，形态和语义表示。为了在我们的框架中生成一个句子，一个语义陈述首先是从一个先验样本中抽取的，比如从知识库中的一组信念中抽取。给定这个语义陈述，语法概率地生成输出句子。一个联合的语义句法分析器被派生出来，它返回给定句子的$ k $ -best语义和句法分析。语义先验是灵活的，并且可以用于在解析期间并入背景知识，与以前的语义解析方法不同。例如，与知识库中的信念相对应的语义陈述可以被给予更高的先验概率，类型正确的陈述可以被给予稍低的概率，并且知识库之外的信念可以被给予更低的概率。我们的语法的构造调用了层次狄利克雷过程（HDP）的新颖应用，这又需要一种新颖且有效的推理方法。我们给出的实验结果表明，对于一个简单的语法来说，我们的解析器胜过了最先进的CCG语义解析器，并扩展到具有数百万信仰的知识库。

##### URL
[https://arxiv.org/abs/1606.06361](https://arxiv.org/abs/1606.06361)

##### PDF
[https://arxiv.org/pdf/1606.06361](https://arxiv.org/pdf/1606.06361)

