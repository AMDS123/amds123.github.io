---
layout: post
title: "Dynamic Multi-Level Multi-Task Learning for Sentence Simplification"
date: 2018-06-19 15:21:37
categories: arXiv_AI
tags: arXiv_AI
author: Han Guo, Ramakanth Pasunuru, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Sentence simplification aims to improve readability and understandability, based on several operations such as splitting, deletion, and paraphrasing. However, a valid simplified sentence should also be logically entailed by its input sentence. In this work, we first present a strong pointer-copy mechanism based sequence-to-sequence sentence simplification model, and then improve its entailment and paraphrasing capabilities via multi-task learning with related auxiliary tasks of entailment and paraphrase generation. Moreover, we propose a novel 'multi-level' layered soft sharing approach where each auxiliary task shares different (higher versus lower) level layers of the sentence simplification model, depending on the task's semantic versus lexico-syntactic nature. We also introduce a novel multi-armed bandit based training approach that dynamically learns how to effectively switch across tasks during multi-task learning. Experiments on multiple popular datasets demonstrate that our model outperforms competitive simplification systems in SARI and FKGL automatic metrics, and human evaluation. Further, we present several ablation analyses on alternative layer sharing methods, soft versus hard sharing, dynamic multi-armed bandit sampling approaches, and our model's learned entailment and paraphrasing skills.

##### Abstract (translated by Google)
简化句子旨在提高可读性和可理解性，基于多项操作，如分割，删除和释义。然而，一个有效的简化句子也应该在其输入句子的逻辑上引起。在这项工作中，我们首先提出了一个强大的基于指针 - 拷贝机制的序列到序列句子简化模型，然后通过多任务学习和相关的蕴涵和释义辅助任务来提高其蕴含和释义能力。此外，我们提出了一种新的'多层次'分层软共享方法，其中每个辅助任务共享句子简化模型的不同层次（较高层次与较低层次），具体取决于任务的语义与词汇句法性质。我们还介绍了一种新型的多手臂强盗训练方法，可以动态学习如何在多任务学习期间有效切换任务。对多个流行数据集进行的实验表明，我们的模型在SARI和FKGL自动指标以及人为评估方面优于竞争简化系统。此外，我们提出了有关替代层共享方法，软对硬共享，动态多臂强盗抽样方法以及我们模型的学习蕴含和解释技巧的几项消融分析。

##### URL
[http://arxiv.org/abs/1806.07304](http://arxiv.org/abs/1806.07304)

##### PDF
[http://arxiv.org/pdf/1806.07304](http://arxiv.org/pdf/1806.07304)

