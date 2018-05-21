---
layout: post
title: "Approximate Model Counting by Partial Knowledge Compilation"
date: 2018-05-18 12:51:48
categories: arXiv_AI
tags: arXiv_AI Knowledge
author: Yong Lai
mathjax: true
---

* content
{:toc}

##### Abstract
Model counting is the problem of computing the number of satisfying assignments of a given propositional formula. Although exact model counters can be naturally furnished by most of the knowledge compilation (KC) methods, in practice, they fail to generate the compiled results for the exact counting of models for certain formulas due to the explosion in sizes. Decision-DNNF is an important KC language that captures most of the practical compilers. We propose a generalized Decision-DNNF (referred to as partial Decision-DNNF) via introducing a class of new leaf vertices (called unknown vertices), and then propose an algorithm called PartialKC to generate randomly partial Decision-DNNF formulas from the given formulas. An unbiased estimate of the model number can be computed via a randomly partial Decision-DNNF formula. Each calling of PartialKC consists of multiple callings of MicroKC, while each of the latter callings is a process of importance sampling equipped with KC technologies. The experimental results show that PartialKC is more accurate than both SampleSearch and SearchTreeSampler, PartialKC scales better than SearchTreeSampler, and the KC technologies can obviously accelerate sampling.

##### Abstract (translated by Google)
模型计数是计算给定命题公式的令人满意的分配数量的问题。虽然精确模型计数器可以由大多数知识编辑（KC）方法自然提供，但实际上，由于尺寸的扩大，它们无法生成编译结果以精确计算某些公式的模型。决策-DNNF是一种重要的KC语言，它捕获了大多数实用的编译器。通过引入一类新的叶顶点（称为未知顶点），我们提出了一个广义的Decision-DNNF（称为部分决策-DNNF），然后提出了一个称为PartialKC的算法来根据给定的公式生成随机部分决策DNNF公式。模型编号的无偏估计可以通过随机部分决策DNNF公式计算。 PartialKC的每个调用都由多个MicroKC调用组成，而每个后者调用都是一个重要的采样过程，配备了KC技术。实验结果表明，PartialKC比SampleSearch和SearchTreeSampler更精确，PartialKC比SearchTreeSampler更好，KC技术可以明显加速采样。

##### URL
[http://arxiv.org/abs/1805.07180](http://arxiv.org/abs/1805.07180)

##### PDF
[http://arxiv.org/pdf/1805.07180](http://arxiv.org/pdf/1805.07180)

