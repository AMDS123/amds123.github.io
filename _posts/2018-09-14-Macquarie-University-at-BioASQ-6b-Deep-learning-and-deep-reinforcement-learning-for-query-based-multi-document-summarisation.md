---
layout: post
title: "Macquarie University at BioASQ 6b: Deep learning and deep reinforcement learning for query-based multi-document summarisation"
date: 2018-09-14 07:26:31
categories: arXiv_CL
tags: arXiv_CL Reinforcement_Learning Embedding RNN Deep_Learning
author: Diego Moll&#xe1;
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes Macquarie University's contribution to the BioASQ Challenge (BioASQ 6b, Phase B). We focused on the extraction of the ideal answers, and the task was approached as an instance of query-based multi-document summarisation. In particular, this paper focuses on the experiments related to the deep learning and reinforcement learning approaches used in the submitted runs. The best run used a deep learning model under a regression-based framework. The deep learning architecture used features derived from the output of LSTM chains on word embeddings, plus features based on similarity with the query, and sentence position. The reinforcement learning approach was a proof-of-concept prototype that trained a global policy using REINFORCE. The global policy was implemented as a neural network that used $tf.idf$ features encoding the candidate sentence, question, and context.

##### Abstract (translated by Google)
本文介绍了麦格理大学对BioASQ挑战赛的贡献（BioASQ 6b，B期）。我们专注于提取理想答案，并将任务作为基于查询的多文档摘要的实例。特别是，本文重点关注与提交的运行中使用的深度学习和强化学习方法相关的实验。最好的运行在基于回归的框架下使用深度学习模型。深度学习架构使用从字嵌入的LSTM链的输出得到的特征，以及基于与查询的相似性的特征和句子位置。强化学习方法是一种概念验证原型，使用REINFORCE训练全球政策。全局策略是作为神经网络实现的，该网络使用$ tf.idf $特征编码候选句子，问题和上下文。

##### URL
[http://arxiv.org/abs/1809.05283](http://arxiv.org/abs/1809.05283)

##### PDF
[http://arxiv.org/pdf/1809.05283](http://arxiv.org/pdf/1809.05283)

