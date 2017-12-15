---
layout: post
title: "Ask the Right Questions: Active Question Reformulation with Reinforcement Learning"
date: 2017-07-12 12:21:14
categories: arXiv_CL
tags: arXiv_CL QA Reinforcement_Learning
author: Christian Buck, Jannis Bulian, Massimiliano Ciaramita, Wojciech Gajewski, Andrea Gesmundo, Neil Houlsby, Wei Wang
mathjax: true
---

* content
{:toc}

##### Abstract
We frame Question Answering as a Reinforcement Learning task, an approach that we call Active Question Answering. We propose an agent that sits between the user and a black box question-answering system an which learns to reformulate questions to elicit the best possible answers. The agent probes the system with, potentially many, natural language reformulations of an initial question and aggregates the returned evidence to yield the best answer. The reformulation system is trained end-to-end to maximize answer quality using policy gradient. We evaluate on SearchQA, a dataset of complex questions extracted from Jeopardy!. Our agent improves F1 by 11% over a state-of-the-art base model that uses the original question/answer pairs.

##### Abstract (translated by Google)
我们把问题解答作为一个强化学习的任务，我们称之为主动问答。我们提出了一个位于用户和黑匣子问答系统之间的代理，该系统学习重构问题以获得最佳答案。代理探查系统，可能有许多自然语言重新编写初始问题，并汇总所返回的证据以得出最佳答案。重构系统是端到端的培训，使用政策梯度来最大化答案质量。我们对SearchQA进行评估，这是从Jeopardy！提取的复杂问题的数据集。我们的代理人使用最初的问题/答案对，将先进的基础模型提高了11％。

##### URL
[https://arxiv.org/abs/1705.07830](https://arxiv.org/abs/1705.07830)

##### PDF
[https://arxiv.org/pdf/1705.07830](https://arxiv.org/pdf/1705.07830)

