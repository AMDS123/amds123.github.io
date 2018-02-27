---
layout: post
title: "Discovering Representative Examples for Program Synthesis"
date: 2018-02-25 00:34:06
categories: arXiv_AI
tags: arXiv_AI
author: Yewen Pu, Zachery Miranda, Armando Solar-Lezama, Leslie Pack Kaelbling
mathjax: true
---

* content
{:toc}

##### Abstract
Program synthesis is a class of regression problems where one seeks a solution, in the form of a source-code program, mapping the inputs to their corresponding outputs exactly. Due to its precise and combinatorial nature, program synthesis is commonly formulated as a constraint satisfaction problem, where input-output examples are encoded as constraints and solved with a constraint solver. A key challenge of this formulation is scalability: while constraint solvers work well with a few well-chosen examples, a large set of examples can incur significant overhead in both time and memory. We describe a method to discover a subset of examples that is both small and representative: the subset is constructed iteratively, using a neural network to predict the probability of unchosen examples conditioned on the chosen examples in the subset, and greedily adding the least probable example. We empirically evaluate the representativeness of the subsets constructed by our method, and demonstrate such subsets can significantly improve synthesis time and stability.

##### Abstract (translated by Google)
程序综合是一类回归问题，其中一个以源代码程序的形式寻求解决方案，将输入准确地映射到其相应的输出。由于其精确和组合的性质，程序综合通常被表述为约束满足问题，其中输入 - 输出例子被编码为约束并且用约束求解器求解。这个公式的一个关键挑战是可伸缩性：虽然约束求解器可以很好地与一些精心挑选的例子一起工作，但是大量的例子会在时间和内存方面产生巨大的开销。我们描述了一种方法来发现既小又具代表性的例子子集：该子集是迭代构建的，使用神经网络来预测未选择的子例子中选择的例子的条件的概率，并贪婪地加入最不可能的例子。我们经验性地评估了我们方法构建的子集的代表性，并证明这些子集可以显着提高合成时间和稳定性。

##### URL
[http://arxiv.org/abs/1711.03243](http://arxiv.org/abs/1711.03243)

##### PDF
[http://arxiv.org/pdf/1711.03243](http://arxiv.org/pdf/1711.03243)

