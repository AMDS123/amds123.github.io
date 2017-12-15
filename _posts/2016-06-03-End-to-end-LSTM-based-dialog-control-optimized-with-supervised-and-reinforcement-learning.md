---
layout: post
title: "End-to-end LSTM-based dialog control optimized with supervised and reinforcement learning"
date: 2016-06-03 20:32:52
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning Optimization RNN
author: Jason D. Williams, Geoffrey Zweig
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a model for end-to-end learning of task-oriented dialog systems. The main component of the model is a recurrent neural network (an LSTM), which maps from raw dialog history directly to a distribution over system actions. The LSTM automatically infers a representation of dialog history, which relieves the system developer of much of the manual feature engineering of dialog state. In addition, the developer can provide software that expresses business rules and provides access to programmatic APIs, enabling the LSTM to take actions in the real world on behalf of the user. The LSTM can be optimized using supervised learning (SL), where a domain expert provides example dialogs which the LSTM should imitate; or using reinforcement learning (RL), where the system improves by interacting directly with end users. Experiments show that SL and RL are complementary: SL alone can derive a reasonable initial policy from a small number of training dialogs; and starting RL optimization with a policy trained with SL substantially accelerates the learning rate of RL.

##### Abstract (translated by Google)
本文提出了面向任务的对话系统的端到端学习模型。该模型的主要组成部分是一个循环神经网络（LSTM），它从原始对话历史直接映射到系统动作分布。 LSTM自动推断对话历史的表示，从而减轻了系统开发人员对话状态的许多手动特征工程。此外，开发人员可以提供表达业务规则的软件，并提供对程序化API的访问，使LSTM能够代表用户在现实世界中采取行动。可以使用监督学习（SL）来优化LSTM，其中领域专家提供LSTM应该模仿的示例对话;或者使用强化学习（RL），系统通过直接与最终用户交互来改进。实验表明SL和RL是相辅相成的：单独SL可以从少量的培训对话中得出一个合理的初始策略;并且用SL训练的策略开始RL优化大大加快了RL的学习速率。

##### URL
[https://arxiv.org/abs/1606.01269](https://arxiv.org/abs/1606.01269)

##### PDF
[https://arxiv.org/pdf/1606.01269](https://arxiv.org/pdf/1606.01269)

