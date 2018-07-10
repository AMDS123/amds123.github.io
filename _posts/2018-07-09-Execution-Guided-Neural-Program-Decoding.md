---
layout: post
title: "Execution-Guided Neural Program Decoding"
date: 2018-07-09 13:20:28
categories: arXiv_CL
tags: arXiv_CL Prediction
author: Chenglong Wang, Po-Sen Huang, Alex Polozov, Marc Brockschmidt, Rishabh Singh
mathjax: true
---

* content
{:toc}

##### Abstract
We present a neural semantic parser that translatesnatural language questions intoexecutableSQLqueries with two key ideas. First, we develop anencoder-decoder model, where the decoder usesa simple type system of SQL to constraint theoutput prediction, and propose a value-based losswhen copying from input tokens. Second, we ex-plore using the execution semantics of SQL to re-pair decoded programs that result in runtime erroror return empty result. We propose two model-agnostics repair approaches, an ensemble modeland a local program repair, and demonstrate theireffectiveness over the original model. We evalu-ate our model on the WikiSQL dataset and showthat our model achieves close to state-of-the-artresults with lesser model complexity.

##### Abstract (translated by Google)
我们提出了一个神经语义解析器，它将自然语言问题转换为具有两个关键思想的可执行SQL查询。首先，我们开发了编码器 - 解码器模型，其中解码器使用简单类型的SQL系统来约束输出预测，并在从输入令牌复制时提出基于值的损失。其次，我们使用SQL的执行语义来重新配对导致运行时错误或返回空结果的解码程序。我们提出了两种模型不可知修复方法，一种集合模式，一种本地程序修复，并展示了对原始模型的有效性。我们在WikiSQL数据集上评估我们的模型，并证明我们的模型接近最先进的结果，模型复杂度较低。

##### URL
[http://arxiv.org/abs/1807.03100](http://arxiv.org/abs/1807.03100)

##### PDF
[http://arxiv.org/pdf/1807.03100](http://arxiv.org/pdf/1807.03100)

