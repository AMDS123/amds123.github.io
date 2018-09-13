---
layout: post
title: "Genetic algorithms with DNN-based trainable crossover as an example of partial specialization of general search"
date: 2018-07-18 10:14:58
categories: arXiv_AI
tags: arXiv_AI
author: Alexey Potapov, Sergey Rodionov
mathjax: true
---

* content
{:toc}

##### Abstract
Universal induction relies on some general search procedure that is doomed to be inefficient. One possibility to achieve both generality and efficiency is to specialize this procedure w.r.t. any given narrow task. However, complete specialization that implies direct mapping from the task parameters to solutions (discriminative models) without search is not always possible. In this paper, partial specialization of general search is considered in the form of genetic algorithms (GAs) with a specialized crossover operator. We perform a feasibility study of this idea implementing such an operator in the form of a deep feedforward neural network. GAs with trainable crossover operators are compared with the result of complete specialization, which is also represented as a deep neural network. Experimental results show that specialized GAs can be more efficient than both general GAs and discriminative models.

##### Abstract (translated by Google)
通用归纳依赖于一些注定效率低下的一般搜索程序。实现一般性和效率的一种可能性是专门化这个程序w.r.t.任何给定的狭窄任务。但是，完全专业化意味着从任务参数直接映射到解决方案（判别模型）而不进行搜索并不总是可行的。在本文中，一般搜索的部分专业化以遗传算法（GA）的形式与专门的交叉算子一起考虑。我们以深度前馈神经网络的形式对这种思想进行可行性研究。将具有可训练交叉算子的GA与完全专业化的结果进行比较，其也表示为深度神经网络。实验结果表明，专用的GA可以比一般的GA和判别模型更有效。

##### URL
[http://arxiv.org/abs/1809.04520](http://arxiv.org/abs/1809.04520)

##### PDF
[http://arxiv.org/pdf/1809.04520](http://arxiv.org/pdf/1809.04520)

