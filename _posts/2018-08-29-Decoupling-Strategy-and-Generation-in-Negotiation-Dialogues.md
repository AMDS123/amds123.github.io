---
layout: post
title: "Decoupling Strategy and Generation in Negotiation Dialogues"
date: 2018-08-29 04:59:15
categories: arXiv_CL
tags: arXiv_CL Knowledge Reinforcement_Learning
author: He He, Derek Chen, Anusha Balakrishnan, Percy Liang
mathjax: true
---

* content
{:toc}

##### Abstract
We consider negotiation settings in which two agents use natural language to bargain on goods. Agents need to decide on both high-level strategy (e.g., proposing \$50) and the execution of that strategy (e.g., generating "The bike is brand new. Selling for just \$50."). Recent work on negotiation trains neural models, but their end-to-end nature makes it hard to control their strategy, and reinforcement learning tends to lead to degenerate solutions. In this paper, we propose a modular approach based on coarse di- alogue acts (e.g., propose(price=50)) that decouples strategy and generation. We show that we can flexibly set the strategy using supervised learning, reinforcement learning, or domain-specific knowledge without degeneracy, while our retrieval-based generation can maintain context-awareness and produce diverse utterances. We test our approach on the recently proposed DEALORNODEAL game, and we also collect a richer dataset based on real items on Craigslist. Human evaluation shows that our systems achieve higher task success rate and more human-like negotiation behavior than previous approaches.

##### Abstract (translated by Google)
我们考虑谈判设置，其中两个代理使用自然语言来讨价还价。代理商需要决定高级策略（例如，提出\ $ 50）和该策略的执行（例如，生成“自行车是全新的。仅售50美元。”）。最近关于谈判的工作训练神经模型，但它们的端到端性质使得难以控制其策略，强化学习倾向于导致退化的解决方案。在本文中，我们提出了一种基于粗略对话行为的模块化方法（例如，建议（价格= 50）），将战略和生成分离。我们表明，我们可以使用监督学习，强化学习或领域特定知识灵活地设置策略，而不会简并，而我们基于检索的生成可以保持情境意识并产生多样化的话语。我们在最近提出的DEALORNODEAL游戏中测试我们的方法，并且我们还在Craigslist上收集基于真实项目的更丰富的数据集。人体评估表明，与以前的方法相比，我们的系统实现了更高的任务成功率和更像人类的谈判行为。

##### URL
[http://arxiv.org/abs/1808.09637](http://arxiv.org/abs/1808.09637)

##### PDF
[http://arxiv.org/pdf/1808.09637](http://arxiv.org/pdf/1808.09637)

