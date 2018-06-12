---
layout: post
title: "Deep Reinforcement Learning for Chinese Zero pronoun Resolution"
date: 2018-06-10 19:29:03
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning
author: Qingyu Yin, Yu Zhang, Weinan Zhang, Ting Liu, William Yang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network models for Chinese zero pronoun resolution learn semantic information for zero pronoun and candidate antecedents, but tend to be short-sighted---they often make local decisions. They typically predict coreference chains between the zero pronoun and one single candidate antecedent one link at a time, while overlooking their long-term influence on future decisions. Ideally, modeling useful information of preceding potential antecedents is critical when later predicting zero pronoun-candidate antecedent pairs. In this study, we show how to integrate local and global decision-making by exploiting deep reinforcement learning models. With the help of the reinforcement learning agent, our model learns the policy of selecting antecedents in a sequential manner, where useful information provided by earlier predicted antecedents could be utilized for making later coreference decisions. Experimental results on OntoNotes 5.0 dataset show that our technique surpasses the state-of-the-art models.

##### Abstract (translated by Google)
用于中国零代词解析的深度神经网络模型可以学习零代词和候选前因子的语义信息，但往往是短视的 - 他们经常做出本地决策。他们通常预测零代词与单个候选人之间先前的一个链接之间的共同连锁链，同时忽略他们对未来决策的长期影响。理想情况下，在后来预测零代词候选先行词对时，模拟先前潜在先行词的有用信息是至关重要的。在这项研究中，我们展示了如何利用深度强化学习模型来整合本地和全球决策。在强化学习代理的帮助下，我们的模型学习了以顺序方式选择前因的策略，其中早期预测的前因所提供的有用信息可用于做出后续的共同决定。 OntoNotes 5.0数据集上的实验结果表明，我们的技术超越了最先进的模型。

##### URL
[http://arxiv.org/abs/1806.03711](http://arxiv.org/abs/1806.03711)

##### PDF
[http://arxiv.org/pdf/1806.03711](http://arxiv.org/pdf/1806.03711)

