---
layout: post
title: "Commonsense for Generative Multi-Hop Question Answering Tasks"
date: 2018-09-17 16:24:00
categories: arXiv_AI
tags: arXiv_AI Knowledge QA Attention Prediction Relation
author: Lisa Bauer, Yicheng Wang, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Reading comprehension QA tasks have seen a recent surge in popularity, yet most works have focused on fact-finding extractive QA. We instead focus on a more challenging multi-hop generative task (NarrativeQA), which requires the model to reason, gather, and synthesize disjoint pieces of information within the context to generate an answer. This type of multi-step reasoning also often requires understanding implicit relations, which humans resolve via external, background commonsense knowledge. We first present a strong generative baseline that uses a multi-attention mechanism to perform multiple hops of reasoning and a pointer-generator decoder to synthesize the answer. This model performs substantially better than previous generative models, and is competitive with current state-of-the-art span prediction models. We next introduce a novel system for selecting grounded multi-hop relational commonsense information from ConceptNet via a pointwise mutual information and term-frequency based scoring function. Finally, we effectively use this extracted commonsense information to fill in gaps of reasoning between context hops, using a selectively-gated attention mechanism. This boosts the model's performance significantly (also verified via human evaluation), establishing a new state-of-the-art for the task. We also show that our background knowledge enhancements are generalizable and improve performance on QAngaroo-WikiHop, another multi-hop reasoning dataset.

##### Abstract (translated by Google)
阅读理解QA任务最近流行起来，但大多数作品都集中在事实调查提取QA上。相反，我们专注于更具挑战性的多跳生成任务（NarrativeQA），该任务要求模型在上下文中推理，收集和合成不相交的信息以生成答案。这种多步推理通常还需要理解隐含关系，人类通过外部的常识知识来解决隐含关系。我们首先提出一个强大的生成基线，它使用多重注意机制来执行多跳推理，并使用指针生成器解码器来合成答案。该模型比先前的生成模型表现得更好，并且与当前最先进的跨度预测模型竞争。接下来，我们将介绍一种新颖的系统，用于通过逐点互信息和基于词频的评分函数从ConceptNet中选择接地的多跳关系常识信息。最后，我们有效地使用这个提取的常识信息来填充上下文跳跃之间的推理空白，使用选择性门控注意机制。这显着提升了模型的性能（也通过人工评估验证），为任务建立了新的先进技术。我们还展示了我们的背景知识增强功能可以推广并提高QAngaroo-WikiHop（另一个多跳推理数据集）的性能。

##### URL
[http://arxiv.org/abs/1809.06309](http://arxiv.org/abs/1809.06309)

##### PDF
[http://arxiv.org/pdf/1809.06309](http://arxiv.org/pdf/1809.06309)

