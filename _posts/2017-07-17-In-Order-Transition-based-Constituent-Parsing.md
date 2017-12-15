---
layout: post
title: "In-Order Transition-based Constituent Parsing"
date: 2017-07-17 04:27:11
categories: arXiv_CL
tags: arXiv_CL RNN
author: Jiangming Liu, Yue Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Both bottom-up and top-down strategies have been used for neural transition-based constituent parsing. The parsing strategies differ in terms of the order in which they recognize productions in the derivation tree, where bottom-up strategies and top-down strategies take post-order and pre-order traversal over trees, respectively. Bottom-up parsers benefit from rich features from readily built partial parses, but lack lookahead guidance in the parsing process; top-down parsers benefit from non-local guidance for local decisions, but rely on a strong encoder over the input to predict a constituent hierarchy before its construction.To mitigate both issues, we propose a novel parsing system based on in-order traversal over syntactic trees, designing a set of transition actions to find a compromise between bottom-up constituent information and top-down lookahead information. Based on stack-LSTM, our psycholinguistically motivated constituent parsing system achieves 91.8 F1 on WSJ benchmark. Furthermore, the system achieves 93.6 F1 with supervised reranking and 94.2 F1 with semi-supervised reranking, which are the best results on the WSJ benchmark.

##### Abstract (translated by Google)
自下而上和自上而下的策略已被用于基于神经转换的成分分析。解析策略在它们识别派生树中的产品的顺序方面不同，其中自下而上策略和自顶向下策略分别在树上进行后序和前序遍历。自下而上的解析器受益于易于构建的部分解析的丰富功能，但在解析过程中缺少预见性指导;自顶向下的解析器受益于局部决策的非本地指导，但依赖于输入的强编码器来预测构成层次结构。为了减轻这两个问题，我们提出了一种基于序列遍历的新型解析系统句法树，设计一组转换动作以找到自下而上的组成信息和自顶向下的先行信息之间的折中。基于stack-LSTM，我们心理语言学动机构成的解析系统在WSJ基准上达到了91.8 F1。此外，该系统通过监督重新调整达到93.6 F1，半监督改变达到94.2 F1，这是“华尔街日报”基准测试的最佳结果。

##### URL
[https://arxiv.org/abs/1707.05000](https://arxiv.org/abs/1707.05000)

##### PDF
[https://arxiv.org/pdf/1707.05000](https://arxiv.org/pdf/1707.05000)

