---
layout: post
title: "Sequence Tagging with Policy-Value Networks and Tree Search"
date: 2018-04-29 11:57:15
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning RNN Memory_Networks
author: Yadi Lao, Jun Xu, Yanyan Lan, Jiafeng Guo, Sheng Gao, Xueqi Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a novel reinforcement learning based model for sequence tagging, referred to as MM-Tag. Inspired by the success and methodology of the AlphaGo Zero, MM-Tag formalizes the problem of sequence tagging with a Monte Carlo tree search (MCTS) enhanced Markov decision process (MDP) model, in which the time steps correspond to the positions of words in a sentence from left to right, and each action corresponds to assign a tag to a word. Two long short-term memory networks (LSTM) are used to summarize the past tag assignments and words in the sentence. Based on the outputs of LSTMs, the policy for guiding the tag assignment and the value for predicting the whole tagging accuracy of the whole sentence are produced. The policy and value are then strengthened with MCTS, which takes the produced raw policy and value as inputs, simulates and evaluates the possible tag assignments at the subsequent positions, and outputs a better search policy for assigning tags. A reinforcement learning algorithm is proposed to train the model parameters. Our work is the first to apply the MCTS enhanced MDP model to the sequence tagging task. We show that MM-Tag can accurately predict the tags thanks to the exploratory decision making mechanism introduced by MCTS. Experimental results show based on a chunking benchmark showed that MM-Tag outperformed the state-of-the-art sequence tagging baselines including CRF and CRF with LSTM.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的基于强化学习的序列标记模型，称为MM-Tag。受到AlphaGo Zero的成功和方法论的启发，MM-Tag使用蒙特卡罗树搜索（MCTS）增强马尔可夫决策过程（MDP）模型来形式化序列标签问题，其中时间步长对应于字母位置从左到右的句子，每个动作对应于为单词分配标签。两个长期短期记忆网络（LSTM）用于总结句子中过去的标签分配和单词。根据LSTM的输出结果，生成指导标签分配的策略和预测整个句子整体标签准确度的值。 MCTS将策略和价值加强，MCTS将生产的原始策略和价值作为输入，模拟和评估后续位置的可能标签分配，并输出更好的分配标签的搜索策略。提出了强化学习算法来训练模型参数。我们的工作是首次将MCTS增强型MDP模型应用于序列标记任务。我们证明了由于MCTS引入的探索性决策机制，MM-Tag可以准确地预测标签。基于组块基准的实验结果显示，MM-Tag优于包括CRF和CRF的LSTM在内的最先进的序列标签基线。

##### URL
[https://arxiv.org/abs/1804.10911](https://arxiv.org/abs/1804.10911)

##### PDF
[https://arxiv.org/pdf/1804.10911](https://arxiv.org/pdf/1804.10911)

