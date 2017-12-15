---
layout: post
title: "Distilling an Ensemble of Greedy Dependency Parsers into One MST Parser"
date: 2016-09-24 02:58:26
categories: arXiv_CL
tags: arXiv_CL RNN
author: Adhiguna Kuncoro, Miguel Ballesteros, Lingpeng Kong, Chris Dyer, Noah A. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce two first-order graph-based dependency parsers achieving a new state of the art. The first is a consensus parser built from an ensemble of independently trained greedy LSTM transition-based parsers with different random initializations. We cast this approach as minimum Bayes risk decoding (under the Hamming cost) and argue that weaker consensus within the ensemble is a useful signal of difficulty or ambiguity. The second parser is a "distillation" of the ensemble into a single model. We train the distillation parser using a structured hinge loss objective with a novel cost that incorporates ensemble uncertainty estimates for each possible attachment, thereby avoiding the intractable cross-entropy computations required by applying standard distillation objectives to problems with structured outputs. The first-order distillation parser matches or surpasses the state of the art on English, Chinese, and German.

##### Abstract (translated by Google)
我们介绍了两个一阶基于图的依赖关系解析器，实现了一个新的技术水平。第一个是从独立训练的贪婪的LSTM基于转换的解析器的集合中构建的具有不同随机初始化的共识解析器。我们将这种方法作为最小贝叶斯风险解码（在海明成本下），并认为集合内较弱的共识是一个困难或模糊的有用信号。第二个语法分析器是整体集成到一个模型中的“升华”。我们使用结构化的铰链损失目标来训练蒸馏分析器，其新颖的成本结合了每个可能附件的集合不确定性估计值，从而避免了将标准蒸馏目标应用于结构化输出的问题所需的难交叉熵计算。一级蒸馏分析器匹配或超过英语，中文和德语的艺术水平。

##### URL
[https://arxiv.org/abs/1609.07561](https://arxiv.org/abs/1609.07561)

##### PDF
[https://arxiv.org/pdf/1609.07561](https://arxiv.org/pdf/1609.07561)

