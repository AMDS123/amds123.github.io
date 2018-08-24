---
layout: post
title: "Weakly-supervised Neural Semantic Parsing with a Generative Ranker"
date: 2018-08-23 04:03:58
categories: arXiv_CL
tags: arXiv_CL Knowledge
author: Jianpeng Cheng, Mirella Lapata
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly-supervised semantic parsers are trained on utterance-denotation pairs, treating logical forms as latent. The task is challenging due to the large search space and spuriousness of logical forms. In this paper we introduce a neural parser-ranker system for weakly-supervised semantic parsing. The parser generates candidate tree-structured logical forms from utterances using clues of denotations. These candidates are then ranked based on two criterion: their likelihood of executing to the correct denotation, and their agreement with the utterance semantics. We present a scheduled training procedure to balance the contribution of the two objectives. Furthermore, we propose to use a neurally encoded lexicon to inject prior domain knowledge to the model. Experiments on three Freebase datasets demonstrate the effectiveness of our semantic parser, achieving results within the state-of-the-art range.

##### Abstract (translated by Google)
弱监督的语义解析器在话语 - 表示对上训练，将逻辑形式视为潜在的。由于逻辑形式的庞大搜索空间和虚假性，任务具有挑战性。在本文中，我们介绍了一种用于弱监督语义分析的神经解析器 - 排序系统。解析器使用符号线索从话语生成候选树形结构逻辑形式。然后根据两个标准对这些候选者进行排名：它们执行正确表示的可能性，以及它们与话语语义的一致性。我们提出预定的培训程序，以平衡两个目标的贡献。此外，我们建议使用神经编码词典将先前的领域知识注入模型。三个Freebase数据集的实验证明了我们的语义分析器的有效性，在最先进的范围内实现了结果。

##### URL
[http://arxiv.org/abs/1808.07625](http://arxiv.org/abs/1808.07625)

##### PDF
[http://arxiv.org/pdf/1808.07625](http://arxiv.org/pdf/1808.07625)

