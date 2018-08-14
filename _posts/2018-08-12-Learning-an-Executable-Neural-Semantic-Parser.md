---
layout: post
title: "Learning an Executable Neural Semantic Parser"
date: 2018-08-12 12:02:45
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention RNN Prediction
author: Jianpeng Cheng, Siva Reddy, Vijay Saraswat, Mirella Lapata
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a neural semantic parser that maps natural language utterances onto logical forms which can be executed against a task-specific environment, such as a knowledge base or a database, to produce a response. The parser generates tree-structured logical forms with a transition-based approach which combines a generic tree-generation algorithm with domain-general operations defined by the logical language. The generation process is modeled by structured recurrent neural networks, which provide a rich encoding of the sentential context and generation history for making predictions. To tackle mismatches between natural language and logical form tokens, various attention mechanisms are explored. Finally, we consider different training settings for the neural semantic parser, including a fully supervised training where annotated logical forms are given, weakly-supervised training where denotations are provided, and distant supervision where only unlabeled sentences and a knowledge base are available. Experiments across a wide range of datasets demonstrate the effectiveness of our parser.

##### Abstract (translated by Google)
本文描述了一种神经语义解析器，它将自然语言话语映射到逻辑形式，这些逻辑形式可以针对任务特定环境（例如知识库或数据库）执行，以产生响应。解析器使用基于转换的方法生成树形结构的逻辑形式，该方法将通用树生成算法与逻辑语言定义的域通用操作相结合。生成过程由结构化递归神经网络建模，该网络提供句子上下文的丰富编码和用于进行预测的生成历史。为了解决自然语言和逻辑形式令牌之间的不匹配，探索了各种注意机制。最后，我们考虑神经语义分析器的不同训练设置，包括给出带注释的逻辑形式的完全监督训练，提供表示的弱监督训练，以及只有未标记的句子和知识库可用的远程监督。跨广泛数据集的实验证明了我们的解析器的有效性。

##### URL
[http://arxiv.org/abs/1711.05066](http://arxiv.org/abs/1711.05066)

##### PDF
[http://arxiv.org/pdf/1711.05066](http://arxiv.org/pdf/1711.05066)

