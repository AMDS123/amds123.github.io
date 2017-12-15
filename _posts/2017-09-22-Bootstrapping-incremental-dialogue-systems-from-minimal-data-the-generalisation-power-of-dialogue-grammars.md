---
layout: post
title: "Bootstrapping incremental dialogue systems from minimal data: the generalisation power of dialogue grammars"
date: 2017-09-22 17:24:33
categories: arXiv_CL
tags: arXiv_CL Knowledge Face Reinforcement_Learning
author: Arash Eshghi, Igor Shalyminov, Oliver Lemon
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate an end-to-end method for automatically inducing task-based dialogue systems from small amounts of unannotated dialogue data. It combines an incremental semantic grammar - Dynamic Syntax and Type Theory with Records (DS-TTR) - with Reinforcement Learning (RL), where language generation and dialogue management are a joint decision problem. The systems thus produced are incremental: dialogues are processed word-by-word, shown previously to be essential in supporting natural, spontaneous dialogue. We hypothesised that the rich linguistic knowledge within the grammar should enable a combinatorially large number of dialogue variations to be processed, even when trained on very few dialogues. Our experiments show that our model can process 74% of the Facebook AI bAbI dataset even when trained on only 0.13% of the data (5 dialogues). It can in addition process 65% of bAbI+, a corpus we created by systematically adding incremental dialogue phenomena such as restarts and self-corrections to bAbI. We compare our model with a state-of-the-art retrieval model, MemN2N. We find that, in terms of semantic accuracy, MemN2N shows very poor robustness to the bAbI+ transformations even when trained on the full bAbI dataset.

##### Abstract (translated by Google)
我们调查了一个端到端的方法，用于从少量未注释的对话数据中自动引导基于任务的对话系统。它将增量语义语法 - 动态语法和类型理论与记录（DS-TTR） - 与强化学习（RL）相结合，其中语言生成和对话管理是一个联合决策问题。这样产生的系统是渐进式的：逐字地处理对话，以前显示对于支持自然的，自发的对话是必不可少的。我们假设语法中丰富的语言知识应该能够组合大量的对话变化来处理，即使是在很少的对话上进行培训。我们的实验表明，即使只有0.13％的数据（5个对话）进行训练，我们的模型也可以处理Facebook AI bAbI数据集的74％。它还可以处理65％的bAbI +，这是一个我们通过系统地添加增量对话现象（例如重新启动和自我修正bAbI）而创建的语料库。我们将我们的模型与最先进的检索模型MemN2N进行比较。我们发现，就语义准确性而言，即使在完整的bAbI数据集上进行训练，MemN2N对bAbI +变换的鲁棒性仍然很差。

##### URL
[https://arxiv.org/abs/1709.07858](https://arxiv.org/abs/1709.07858)

##### PDF
[https://arxiv.org/pdf/1709.07858](https://arxiv.org/pdf/1709.07858)

