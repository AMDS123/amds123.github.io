---
layout: post
title: "Ask the Right Questions: Active Question Reformulation with Reinforcement Learning"
date: 2018-03-02 16:02:24
categories: arXiv_AI
tags: arXiv_AI QA Reinforcement_Learning
author: Christian Buck, Jannis Bulian, Massimiliano Ciaramita, Wojciech Gajewski, Andrea Gesmundo, Neil Houlsby, Wei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We frame Question Answering (QA) as a Reinforcement Learning task, an approach that we call Active Question Answering. We propose an agent that sits between the user and a black box QA system and learns to reformulate questions to elicit the best possible answers. The agent probes the system with, potentially many, natural language reformulations of an initial question and aggregates the returned evidence to yield the best answer. The reformulation system is trained end-to-end to maximize answer quality using policy gradient. We evaluate on SearchQA, a dataset of complex questions extracted from Jeopardy!. The agent outperforms a state-of-the-art base model, playing the role of the environment, and other benchmarks. We also analyze the language that the agent has learned while interacting with the question answering system. We find that successful question reformulations look quite different from natural language paraphrases. The agent is able to discover non-trivial reformulation strategies that resemble classic information retrieval techniques such as term re-weighting (tf-idf) and stemming.

##### Abstract (translated by Google)
我们将问答（QA）框架作为强化学习任务，这种方法称为主动问答（Active Question Answering）。我们建议位于用户和黑匣子QA系统之间的代理商，并学习重新制定问题以引出最佳答案。代理人探讨系统的潜在的许多自然语言重写的初始问题，并汇总返回的证据以产生最佳答案。重构系统是端对端培训，以使用政策梯度最大化答案质量。我们对SearchQA进行评估，这是从Jeopardy！提取的复杂问题的数据集。代理的性能优于最先进的基础模型，扮演环境角色和其他基准。我们还分析了代理人在与问题回答系统交互时学到的语言。我们发现成功的问题重构看起来与自然语言解释有很大不同。该代理能够发现与传统信息检索技术相似的非平凡重构策略，如术语重新加权（tf-idf）和词干。

##### URL
[http://arxiv.org/abs/1705.07830](http://arxiv.org/abs/1705.07830)

##### PDF
[http://arxiv.org/pdf/1705.07830](http://arxiv.org/pdf/1705.07830)

