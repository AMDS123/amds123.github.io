---
layout: post
title: "Deep Dyna-Q: Integrating Planning for Task-Completion Dialogue Policy Learning"
date: 2018-05-13 22:31:38
categories: arXiv_AI
tags: arXiv_AI Knowledge Reinforcement_Learning
author: Baolin Peng, Xiujun Li, Jianfeng Gao, Jingjing Liu, Kam-Fai Wong, Shang-Yu Su
mathjax: true
---

* content
{:toc}

##### Abstract
Training a task-completion dialogue agent via reinforcement learning (RL) is costly because it requires many interactions with real users. One common alternative is to use a user simulator. However, a user simulator usually lacks the language complexity of human interlocutors and the biases in its design may tend to degrade the agent. To address these issues, we present Deep Dyna-Q, which to our knowledge is the first deep RL framework that integrates planning for task-completion dialogue policy learning. We incorporate into the dialogue agent a model of the environment, referred to as the world model, to mimic real user response and generate simulated experience. During dialogue policy learning, the world model is constantly updated with real user experience to approach real user behavior, and in turn, the dialogue agent is optimized using both real experience and simulated experience. The effectiveness of our approach is demonstrated on a movie-ticket booking task in both simulated and human-in-the-loop settings.

##### Abstract (translated by Google)
通过强化学习（RL）训练任务完成对话代理是非常昂贵的，因为它需要与真实用户进行许多交互。一个常见的选择是使用用户模拟器。然而，用户模拟器通常缺乏人类对话者的语言复杂性，并且其设计中的偏差可能会使代理人退化。为了解决这些问题，我们提供Deep Dyna-Q，据我们所知，这是第一个将任务完成对话策略学习计划集成在一起的深度RL框架。我们在对话代理中加入了一种称为世界模型的环境模型，以模拟真实的用户响应并产生模拟的体验。在对话策略学习期间，世界模型不断更新，以真实的用户体验来接近真实的用户行为，反过来，对话代理使用真实体验和模拟体验进行优化。我们的方法的有效性在电影票预订任务中都有模拟和人在环设置。

##### URL
[http://arxiv.org/abs/1801.06176](http://arxiv.org/abs/1801.06176)

##### PDF
[http://arxiv.org/pdf/1801.06176](http://arxiv.org/pdf/1801.06176)

