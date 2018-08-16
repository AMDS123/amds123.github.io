---
layout: post
title: "Actor-Critic based Training Framework for Abstractive Summarization"
date: 2018-08-15 15:59:46
categories: arXiv_AI
tags: arXiv_AI Attention Summarization Reinforcement_Learning
author: Piji Li, Lidong Bing, Wai Lam
mathjax: true
---

* content
{:toc}

##### Abstract
We present a training framework for neural abstractive summarization based on actor-critic approaches from reinforcement learning. In the traditional neural network based methods, the objective is only to maximize the likelihood of the predicted summaries, no other assessment constraints are considered, which may generate low-quality summaries or even incorrect sentences. To alleviate this problem, we employ an actor-critic framework to enhance the training procedure. For the actor, we employ the typical attention based sequence-to-sequence (seq2seq) framework as the policy network for summary generation. For the critic, we combine the maximum likelihood estimator with a well designed global summary quality estimator which is a neural network based binary classifier aiming to make the generated summaries indistinguishable from the human-written ones. Policy gradient method is used to conduct the parameter learning. An alternating training strategy is proposed to conduct the joint training of the actor and critic models. Extensive experiments on some benchmark datasets in different languages show that our framework achieves improvements over the state-of-the-art methods.

##### Abstract (translated by Google)
我们提出了一种基于强化学习的演员评论方法的神经抽象概括训练框架。在传统的基于神经网络的方法中，目标仅是最大化预测摘要的可能性，不考虑其他评估约束，这可能产生低质量摘要或甚至不正确的句子。为了缓解这个问题，我们采用了一个演员评论框架来加强培训程序。对于actor，我们使用典型的基于注意的序列到序列（seq2seq）框架作为摘要生成的策略网络。对于评论家，我们将最大似然估计与精心设计的全局汇总质量估计器相结合，该估计器是基于神经网络的二元分类器，旨在使生成的汇总与人类编写的汇总无法区分。策略梯度法用于进行参数学习。提出了交替训练策略，对演员和评论家模型进行联合训练。对不同语言的一些基准数据集进行了大量实验，结果表明我们的框架实现了对最先进方法的改进。

##### URL
[http://arxiv.org/abs/1803.11070](http://arxiv.org/abs/1803.11070)

##### PDF
[http://arxiv.org/pdf/1803.11070](http://arxiv.org/pdf/1803.11070)

