---
layout: post
title: "A Greedy Search Tree Heuristic for Symbolic Regression"
date: 2018-01-04 18:30:38
categories: arXiv_AI
tags: arXiv_AI Relation
author: Fabricio Olivetti de Franca
mathjax: true
---

* content
{:toc}

##### Abstract
Symbolic Regression tries to find a mathematical expression that describes the relationship of a set of explanatory variables to a measured variable. The main objective is to find a model that minimizes the error and, optionally, that also minimizes the expression size. A smaller expression can be seen as an interpretable model considered a reliable decision model. This is often performed with Genetic Programming which represents their solution as expression trees. The shortcoming of this algorithm lies on this representation that defines a rugged search space and contains expressions of any size and difficulty. These pose as a challenge to find the optimal solution under computational constraints. This paper introduces a new data structure, called Interaction-Transformation (IT), that constrains the search space in order to exclude a region of larger and more complicated expressions. In order to test this data structure, it was also introduced an heuristic called SymTree. The obtained results show evidence that SymTree are capable of obtaining the optimal solution whenever the target function is within the search space of the IT data structure and competitive results when it is not. Overall, the algorithm found a good compromise between accuracy and simplicity for all the generated models.

##### Abstract (translated by Google)
符号回归试图找出描述一组解释变量与测量变量的关系的数学表达式。主要目标是找到一个最小化错误的模型，并且可选地，还将表达式大小最小化。一个较小的表达式可以被看作是一个被认为是可靠决策模型的可解释模型。这通常是用遗传编程来完成的，它将它们的解决方案表示为表达式树。这个算法的缺点在于这个表示定义了一个坚固的搜索空间，并且包含任何大小和难度的表达式。这些在计算约束下寻找最佳解决方案是一个挑战。本文介绍了一种新的数据结构，称为交互转换（IT），它约束搜索空间，以排除一个更大，更复杂表达式的区域。为了测试这个数据结构，还引入了一个名为SymTree的启发式。得到的结果表明SymTree能够在目标函数处于IT数据结构的搜索空间内时获得最优解，而当目标函数处于IT数据结构的搜索空间内时，能够获得最优解。总体而言，该算法找到了所有生成模型的准确性和简单性之间的良好折衷。

##### URL
[http://arxiv.org/abs/1801.01807](http://arxiv.org/abs/1801.01807)

##### PDF
[http://arxiv.org/pdf/1801.01807](http://arxiv.org/pdf/1801.01807)

