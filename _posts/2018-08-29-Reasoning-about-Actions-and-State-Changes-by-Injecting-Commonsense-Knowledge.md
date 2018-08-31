---
layout: post
title: "Reasoning about Actions and State Changes by Injecting Commonsense Knowledge"
date: 2018-08-29 18:53:53
categories: arXiv_AI
tags: arXiv_AI Knowledge Prediction
author: Niket Tandon, Bhavana Dalvi Mishra, Joel Grus, Wen-tau Yih, Antoine Bosselut, Peter Clark
mathjax: true
---

* content
{:toc}

##### Abstract
Comprehending procedural text, e.g., a paragraph describing photosynthesis, requires modeling actions and the state changes they produce, so that questions about entities at different timepoints can be answered. Although several recent systems have shown impressive progress in this task, their predictions can be globally inconsistent or highly improbable. In this paper, we show how the predicted effects of actions in the context of a paragraph can be improved in two ways: (1) by incorporating global, commonsense constraints (e.g., a non-existent entity cannot be destroyed), and (2) by biasing reading with preferences from large-scale corpora (e.g., trees rarely move). Unlike earlier methods, we treat the problem as a neural structured prediction task, allowing hard and soft constraints to steer the model away from unlikely predictions. We show that the new model significantly outperforms earlier systems on a benchmark dataset for procedural text comprehension (+8% relative gain), and that it also avoids some of the nonsensical predictions that earlier systems make.

##### Abstract (translated by Google)
理解程序文本，例如描述光合作用的段落，需要建模动作及其产生的状态变化，以便可以回答关于不同时间点的实体的问题。虽然最近几个系统在这项任务中取得了令人瞩目的进展，但它们的预测可能是全局不一致或极不可能的。在本文中，我们展示了如何通过两种方式改进段落上下文中的行为的预测效果：（1）通过合并全局，常识约束（例如，不存在的实体不能被销毁），以及（2）通过偏向大规模语料库的偏好阅读（例如，树很少移动）。与早期方法不同，我们将问题视为神经结构预测任务，允许硬约束和软约束使模型远离不太可能的预测。我们证明新模型在基准数据集上明显优于早期系统的程序文本理解（+ 8％相对增益），并且它还避免了早期系统所做的一些无意义预测。

##### URL
[http://arxiv.org/abs/1808.10012](http://arxiv.org/abs/1808.10012)

##### PDF
[http://arxiv.org/pdf/1808.10012](http://arxiv.org/pdf/1808.10012)

