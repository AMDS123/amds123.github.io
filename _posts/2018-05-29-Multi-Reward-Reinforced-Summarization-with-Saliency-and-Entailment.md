---
layout: post
title: "Multi-Reward Reinforced Summarization with Saliency and Entailment"
date: 2018-05-29 14:45:28
categories: arXiv_AI
tags: arXiv_AI Salient Summarization Reinforcement_Learning
author: Ramakanth Pasunuru, Mohit Bansal
mathjax: true
---

* content
{:toc}

##### Abstract
Abstractive text summarization is the task of compressing and rewriting a long document into a short summary while maintaining saliency, directed logical entailment, and non-redundancy. In this work, we address these three important aspects of a good summary via a reinforcement learning approach with two novel reward functions: ROUGESal and Entail, on top of a coverage-based baseline. The ROUGESal reward modifies the ROUGE metric by up-weighting the salient phrases/words detected via a keyphrase classifier. The Entail reward gives high (length-normalized) scores to logically-entailed summaries using an entailment classifier. Further, we show superior performance improvement when these rewards are combined with traditional metric (ROUGE) based rewards, via our novel and effective multi-reward approach of optimizing multiple rewards simultaneously in alternate mini-batches. Our method achieves the new state-of-the-art results (including human evaluation) on the CNN/Daily Mail dataset as well as strong improvements in a test-only transfer setup on DUC-2002.

##### Abstract (translated by Google)
抽象文本摘要是在保持显着性，定向逻辑含义和非冗余性的同时将长文档压缩并重写为简短摘要的任务。在这项工作中，我们通过强化学习方法和两个新颖的奖励函数来解决好这个重要方面的三个重要方面：ROUGESal和Entail，在基于覆盖的基线之上。 ROUGESal奖励通过增加通过关键词分类器检测到的重要短语/单词来修改ROUGE度量。 Entail奖励使用包含分类器为逻辑上需要的摘要提供高（长度标准化）分数。此外，当这些奖励与传统指标（ROUGE）基础奖励相结合时，我们通过我们新颖且有效的多奖励方法在多个小批次中同时优化多个奖励，显示出卓越的绩效提升。我们的方法在CNN /每日邮报数据集上实现了最新的最新成果（包括人体评估），并在DUC-2002的仅测试转移设置方面取得了重大进展。

##### URL
[http://arxiv.org/abs/1804.06451](http://arxiv.org/abs/1804.06451)

##### PDF
[http://arxiv.org/pdf/1804.06451](http://arxiv.org/pdf/1804.06451)

