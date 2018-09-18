---
layout: post
title: "The Space-Efficient Core of Vadalog"
date: 2018-09-16 20:33:45
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge
author: Gerald Berger, Georg Gottlob, Andreas Pieris, Emanuel Sallinger
mathjax: true
---

* content
{:toc}

##### Abstract
Vadalog is a system for performing complex reasoning tasks such as those required in advanced knowledge graphs. The logical core of the underlying Vadalog language is the warded fragment of tuple-generating dependencies (TGDs). This formalism ensures tractable reasoning in data complexity, while a recent analysis focusing on a practical implementation led to the reasoning algorithm around which the Vadalog system is built. A fundamental question that has emerged in the context of Vadalog is the following: can we limit the recursion allowed by wardedness in order to obtain a formalism that provides a convenient syntax for expressing useful recursive statements, and at the same time achieves space-efficiency? After analyzing several real-life examples of warded sets of TGDs provided by our industrial partners, as well as recent benchmarks, we observed that recursion is often used in a restricted way: the body of a TGD contains at most one atom whose predicate is mutually recursive with a predicate in the head. We show that this type of recursion, known as piece-wise linear in the Datalog literature, is the answer to our main question. We further show that piece-wise linear recursion alone, without the wardedness condition, is not enough as it leads to the undecidability of reasoning. We finally study the relative expressiveness of the query languages based on (piece-wise linear) warded sets of TGDs.

##### Abstract (translated by Google)
Vadalog是一个用于执行复杂推理任务的系统，例如高级知识图中所需的那些。底层Vadalog语言的逻辑核心是元组生成依赖项（TGD）的受控片段。这种形式主义确保了数据复杂性的易处理性推理，而最近关注实际实现的分析导致了构建Vadalog系统的推理算法。在Vadalog环境中出现的一个基本问题如下：我们是否可以限制wardedness允许的递归，以获得一种形式化，为表达有用的递归语句提供方便的语法，同时实现空间效率？在分析了我们的工业合作伙伴提供的几组TGD的实际例子以及最近的基准测试之后，我们观察到递归通常以受限制的方式使用：TGD的主体最多包含一个原子，其谓词是相互的用头部中的谓词递归。我们证明了这种类型的递归，在Datalog文献中被称为分段线性，是我们主要问题的答案。我们进一步表明，单独的分段线性递归，没有保证条件，是不够的，因为它导致推理的不可判定性。我们最终研究了基于（分段线性）保证的TGD集的查询语言的相对表现力。

##### URL
[http://arxiv.org/abs/1809.05951](http://arxiv.org/abs/1809.05951)

##### PDF
[http://arxiv.org/pdf/1809.05951](http://arxiv.org/pdf/1809.05951)

