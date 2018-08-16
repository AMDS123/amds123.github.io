---
layout: post
title: "Top-Down Tree Structured Text Generation"
date: 2018-08-14 19:12:44
categories: arXiv_CL
tags: arXiv_CL Text_Generation
author: Qipeng Guo, Xipeng Qiu, Xiangyang Xue, Zheng Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Text generation is a fundamental building block in natural language processing tasks. Existing sequential models performs autoregression directly over the text sequence and have difficulty generating long sentences of complex structures. This paper advocates a simple approach that treats sentence generation as a tree-generation task. By explicitly modelling syntactic structures in a constituent syntactic tree and performing top-down, breadth-first tree generation, our model fixes dependencies appropriately and performs implicit global planning. This is in contrast to transition-based depth-first generation process, which has difficulty dealing with incomplete texts when parsing and also does not incorporate future contexts in planning. Our preliminary results on two generation tasks and one parsing task demonstrate that this is an effective strategy.

##### Abstract (translated by Google)
文本生成是自然语言处理任务的基本构建块。现有的顺序模型直接在文本序列上执行自回归，并且难以生成复杂结构的长句。本文提出了一种将句子生成视为树生成任务的简单方法。通过在组成句法树中显式建模句法结构并执行自上而下，广度优先的树生成，我们的模型可以适当地修复依赖关系并执行隐式全局规划。这与基于过渡的深度优先生成过程形成对比，后者在解析时难以处理不完整的文本，并且在计划中也未包含未来的上下文。我们关于两代任务和一个解析任务的初步结果表明这是一种有效的策略。

##### URL
[http://arxiv.org/abs/1808.04865](http://arxiv.org/abs/1808.04865)

##### PDF
[http://arxiv.org/pdf/1808.04865](http://arxiv.org/pdf/1808.04865)

