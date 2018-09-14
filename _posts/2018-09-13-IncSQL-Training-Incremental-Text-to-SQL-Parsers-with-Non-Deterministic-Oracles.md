---
layout: post
title: "IncSQL: Training Incremental Text-to-SQL Parsers with Non-Deterministic Oracles"
date: 2018-09-13 16:42:21
categories: arXiv_CL
tags: arXiv_CL
author: Tianze Shi, Kedar Tatwawadi, Kaushik Chakrabarti, Yi Mao, Oleksandr Polozov, Weizhu Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a sequence-to-action parsing approach for the natural language to SQL task that incrementally fills the slots of a SQL query with feasible actions from a pre-defined inventory. To account for the fact that typically there are multiple correct SQL queries with the same or very similar semantics, we draw inspiration from syntactic parsing techniques and propose to train our sequence-to-action models with non-deterministic oracles. We evaluate our models on the WikiSQL dataset and achieve an execution accuracy of 83.7% on the test set, a 2.1% absolute improvement over the model trained with traditional static oracles assuming a single correct target SQL query. When further combined with the execution-guided decoding strategy, our model sets a new state-of-the-art performance at an execution accuracy of 87.1%. 
 This is a work-in-progress technical report.

##### Abstract (translated by Google)
我们提出了一种针对自然语言到SQL任务的序列到操作解析方法，该方法使用来自预定义库存的可行操作来逐步填充SQL查询的插槽。为了解释通常存在多个具有相同或非常相似语义的正确SQL查询的事实，我们从语法分析技术中汲取灵感，并建议使用非确定性的神谕来训练我们的序列到动作模型。我们在WikiSQL数据集上评估我们的模型，并在测试集上实现83.7％的执行准确性，相对于使用传统静态oracles训练的模型，假定单个正确的目标SQL查询，绝对改进2.1％。当进一步与执行引导的解码策略相结合时，我们的模型以87.1％的执行精度设置了新的最先进的性能。
 这是一份正在进行中的技术报告。

##### URL
[http://arxiv.org/abs/1809.05054](http://arxiv.org/abs/1809.05054)

##### PDF
[http://arxiv.org/pdf/1809.05054](http://arxiv.org/pdf/1809.05054)

