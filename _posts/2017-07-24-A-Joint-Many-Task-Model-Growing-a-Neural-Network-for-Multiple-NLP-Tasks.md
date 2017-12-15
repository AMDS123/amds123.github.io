---
layout: post
title: "A Joint Many-Task Model: Growing a Neural Network for Multiple NLP Tasks"
date: 2017-07-24 14:41:16
categories: arXiv_CL
tags: arXiv_CL Regularization Prediction
author: Kazuma Hashimoto, Caiming Xiong, Yoshimasa Tsuruoka, Richard Socher
mathjax: true
---

* content
{:toc}

##### Abstract
Transfer and multi-task learning have traditionally focused on either a single source-target pair or very few, similar tasks. Ideally, the linguistic levels of morphology, syntax and semantics would benefit each other by being trained in a single model. We introduce a joint many-task model together with a strategy for successively growing its depth to solve increasingly complex tasks. Higher layers include shortcut connections to lower-level task predictions to reflect linguistic hierarchies. We use a simple regularization term to allow for optimizing all model weights to improve one task's loss without exhibiting catastrophic interference of the other tasks. Our single end-to-end model obtains state-of-the-art or competitive results on five different tasks from tagging, parsing, relatedness, and entailment tasks.

##### Abstract (translated by Google)
转移和多任务学习传统上都集中在单一的源 - 目标对上，或者很少，类似的任务。理想情况下，形态，语法和语义的语言水平将通过在单一模型中进行训练而相互受益。我们引入了一个多任务联合模型和一个逐步深入的策略来解决日益复杂的任务。较高的层次包括到较低级任务预测的快捷连接，以反映语言层次结构。我们使用一个简单的正则化术语来优化所有模型权重，以改善一个任务的损失，而不会显示其他任务的灾难性干扰。我们的单一端到端模型通过标记，解析，相关性和引入任务等五个不同的任务获得了最先进或最具竞争力的结果。

##### URL
[https://arxiv.org/abs/1611.01587](https://arxiv.org/abs/1611.01587)

##### PDF
[https://arxiv.org/pdf/1611.01587](https://arxiv.org/pdf/1611.01587)

