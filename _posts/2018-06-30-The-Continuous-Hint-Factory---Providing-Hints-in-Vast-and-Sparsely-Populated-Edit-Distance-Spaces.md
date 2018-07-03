---
layout: post
title: "The Continuous Hint Factory - Providing Hints in Vast and Sparsely Populated Edit Distance Spaces"
date: 2018-06-30 23:00:11
categories: arXiv_AI
tags: arXiv_AI Sparse Prediction
author: Benjamin Paa&#xdf;en, Barbara Hammer, Thomas William Price, Tiffany Barnes, Sebastian Gross, Niels Pinkwart
mathjax: true
---

* content
{:toc}

##### Abstract
Intelligent tutoring systems can support students in solving multi-step tasks by providing hints regarding what to do next. However, engineering such next-step hints manually or via an expert model becomes infeasible if the space of possible states is too large. Therefore, several approaches have emerged to infer next-step hints automatically, relying on past students' data. In particular, the Hint Factory (Barnes &amp; Stamper, 2008) recommends edits that are most likely to guide students from their current state towards a correct solution, based on what successful students in the past have done in the same situation. Still, the Hint Factory relies on student data being available for any state a student might visit while solving the task, which is not the case for some learning tasks, such as open-ended programming tasks. In this contribution we provide a mathematical framework for edit-based hint policies and, based on this theory, propose a novel hint policy to provide edit hints in vast and sparsely populated state spaces. In particular, we extend the Hint Factory by considering data of past students in all states which are similar to the student's current state and creating hints approximating the weighted average of all these reference states. Because the space of possible weighted averages is continuous, we call this approach the Continuous Hint Factory. In our experimental evaluation, we demonstrate that the Continuous Hint Factory can predict more accurately what capable students would do compared to existing prediction schemes on two learning tasks, especially in an open-ended programming task, and that the Continuous Hint Factory is comparable to existing hint policies at reproducing tutor hints on a simple UML diagram task.

##### Abstract (translated by Google)
智能辅导系统可以通过提供有关下一步操作的提示来支持学生解决多步骤任务。然而，如果可能状态的空间太大，则手动或通过专家模型设计这样的下一步提示变得不可行。因此，出现了几种自动推断下一步提示的方法，依赖于过去学生的数据。特别是，Hint Factory（Barnes＆amp; Stamper，2008）根据过去成功学生在相同情况下所做的工作，推荐最有可能引导学生从当前状态转向正确解决方案的编辑。尽管如此，提示工厂还依赖于学生在解决任务时可能访问的任何州的学生数据，而某些学习任务（例如开放式编程任务）则不然。在此贡献中，我们为基于编辑的提示策略提供了一个数学框架，并基于此理论，提出了一种新的提示策略，以在庞大且人口稀少的状态空间中提供编辑提示。特别是，我们通过考虑所有州的过去学生的数据来扩展提示工厂，这些数据与学生的当前状态相似，并创建近似于所有这些参考状态的加权平均值的提示。由于可能的加权平均值的空间是连续的，我们称这种方法为连续提示工厂。在我们的实验评估中，我们证明连续提示工厂能够更准确地预测学生在两个学习任务中与现有预测方案相比会做些什么，特别是在开放式编程任务中，并且连续提示工厂可与现有工作相媲美提示在简单的UML图任务上复制教师提示的策略。

##### URL
[http://arxiv.org/abs/1708.06564](http://arxiv.org/abs/1708.06564)

##### PDF
[http://arxiv.org/pdf/1708.06564](http://arxiv.org/pdf/1708.06564)

