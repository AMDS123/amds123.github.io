---
layout: post
title: "Accurately and Efficiently Interpreting Human-Robot Instructions of Varying Granularities"
date: 2018-06-19 17:19:29
categories: arXiv_AI
tags: arXiv_AI
author: Dilip Arumugam, Siddharth Karamcheti, Nakul Gopalan, Lawson L.S. Wong, Stefanie Tellex
mathjax: true
---

* content
{:toc}

##### Abstract
Humans can ground natural language commands to tasks at both abstract and fine-grained levels of specificity. For instance, a human forklift operator can be instructed to perform a high-level action, like "grab a pallet" or a low-level action like "tilt back a little bit." While robots are also capable of grounding language commands to tasks, previous methods implicitly assume that all commands and tasks reside at a single, fixed level of abstraction. Additionally, methods that do not use multiple levels of abstraction encounter inefficient planning and execution times as they solve tasks at a single level of abstraction with large, intractable state-action spaces closely resembling real world complexity. In this work, by grounding commands to all the tasks or subtasks available in a hierarchical planning framework, we arrive at a model capable of interpreting language at multiple levels of specificity ranging from coarse to more granular. We show that the accuracy of the grounding procedure is improved when simultaneously inferring the degree of abstraction in language used to communicate the task. Leveraging hierarchy also improves efficiency: our proposed approach enables a robot to respond to a command within one second on 90% of our tasks, while baselines take over twenty seconds on half the tasks. Finally, we demonstrate that a real, physical robot can ground commands at multiple levels of abstraction allowing it to efficiently plan different subtasks within the same planning hierarchy.

##### Abstract (translated by Google)
人类可以将自然语言命令以抽象和细粒度的特定水平分解为任务。例如，可以指示人类叉车操作员执行高级别动作，如“抓取托盘”或低级别动作，如“稍微倾斜一点”。尽管机器人也能够将语言命令与任务联系起来，但以前的方法隐含地假设所有命令和任务都驻留在单一的固定抽象级别上。此外，不使用多个抽象层次的方法会遇到效率不高的规划和执行时间，因为他们在单一抽象层次上解决任务时会遇到与真实世界复杂性非常相似的大型棘手状态动作空间。在这项工作中，通过将命令与层次规划框架中的所有任务或子任务相关联，我们得出了一个模型，能够从多个特定级别（从粗到细）解释语言。我们表明，在同时推断用于沟通任务的语言的抽象程度时，接地过程的准确性得到了改善。利用层次结构还可以提高效率：我们提出的方法使机器人能够在一秒钟内对90％的任务做出响应，而对于一半的任务，基线需要超过20秒。最后，我们证明一个真实的物理机器人可以在多个抽象层次上接受命令，使其能够在相同的规划层次结构中有效地规划不同的子任务。

##### URL
[http://arxiv.org/abs/1704.06616](http://arxiv.org/abs/1704.06616)

##### PDF
[http://arxiv.org/pdf/1704.06616](http://arxiv.org/pdf/1704.06616)

