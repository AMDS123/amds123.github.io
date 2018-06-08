---
layout: post
title: "Progressive Reasoning by Module Composition"
date: 2018-06-06 23:02:35
categories: arXiv_CV
tags: arXiv_CV Knowledge Attention VQA
author: Seung Wook Kim, Makarand Tapaswi, Sanja Fidler
mathjax: true
---

* content
{:toc}

##### Abstract
Humans learn to solve tasks of increasing complexity by building on top of previously acquired knowledge. Typically, there exists a natural progression in the tasks that we learn - most do not require completely independent solutions, but can be broken down into simpler subtasks. We propose to represent a solver for each task as a neural module that calls existing modules (solvers for simpler tasks) in a program-like manner. Lower modules are a black box to the calling module, and communicate only via a query and an output. Thus, a module for a new task learns to query existing modules and composes their outputs in order to produce its own output. Each module also contains a residual component that learns to solve aspects of the new task that lower modules cannot solve. Our model effectively combines previous skill-sets, does not suffer from forgetting, and is fully differentiable. We test our model in learning a set of visual reasoning tasks, and demonstrate state-of-the-art performance in Visual Question Answering, the highest-level task in our task set. By evaluating the reasoning process using non-expert human judges, we show that our model is more interpretable than an attention-based baseline.

##### Abstract (translated by Google)
人类学会通过建立在先前获得的知识之上来解决日益复杂的任务。通常，我们学习的任务存在自然进展 - 大多数情况下不需要完全独立的解决方案，但可以分解为更简单的子任务。我们建议将每个任务的求解器表示为一个神经模块，以类似于程序的方式调用现有模块（用于更简单任务的求解器）。较低的模块是调用模块的黑盒子，只能通过查询和输出进行通信。因此，用于新任务的模块学习查询现有模块并组合它们的输出以产生它自己的输出。每个模块还包含一个剩余组件，学习解决下层模块无法解决的新任务的各个方面。我们的模型有效地结合了以前的技能，不会遗忘，而且完全可以区分。我们在学习一组视觉推理任务时测试我们的模型，并在Visual Question Answering中展示最新的性能，这是我们任务集中的最高级任务。通过评估使用非专业人士评判的推理过程，我们发现我们的模型比基于注意力的基准更能诠释。

##### URL
[http://arxiv.org/abs/1806.02453](http://arxiv.org/abs/1806.02453)

##### PDF
[http://arxiv.org/pdf/1806.02453](http://arxiv.org/pdf/1806.02453)

