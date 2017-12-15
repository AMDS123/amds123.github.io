---
layout: post
title: "Question Answering and Question Generation as Dual Tasks"
date: 2017-08-04 07:25:53
categories: arXiv_CL
tags: arXiv_CL QA Relation
author: Duyu Tang, Nan Duan, Tao Qin, Zhao Yan, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of joint question answering (QA) and question generation (QG) in this paper. Our intuition is that QA and QG have intrinsic connections and these two tasks could improve each other. On one side, the QA model judges whether the generated question of a QG model is relevant to the answer. On the other side, the QG model provides the probability of generating a question given the answer, which is a useful evidence that in turn facilitates QA. In this paper we regard QA and QG as dual tasks. We propose a training framework that trains the models of QA and QG simultaneously, and explicitly leverages their probabilistic correlation to guide the training process of both models. We implement a QG model based on sequence-to-sequence learning, and a QA model based on recurrent neural network. As all the components of the QA and QG models are differentiable, all the parameters involved in these two models could be conventionally learned with back propagation. We conduct experiments on three datasets. Empirical results show that our training framework improves both QA and QG tasks. The improved QA model performs comparably with strong baseline approaches on all three datasets.

##### Abstract (translated by Google)
本文研究了联合问答（QA）和问题生成（QG）问题。我们的直觉是QA和QG有内在的联系，这两个任务可以相互促进。一方面，QA模型判断生成的QG模型的问题是否与答案相关。另一方面，QG模型提供了给出答案的问题产生的可能性，这是一个有用的证据，反过来又有利于质量保证。在本文中，我们将QA和QG视为双重任务。我们提出了一个同时训练QA和QG模型的训练框架，明确地利用概率相关性来指导两个模型的训练过程。我们实现了基于序列学习的QG模型和基于递归神经网络的QA模型。由于QA和QG模型的所有组成部分都是可微的，所以涉及这两个模型的所有参数都可以通过反向传播学习到。我们在三个数据集上进行实验。实证结果表明，我们的培训框架改善了QA和QG任务。在所有三个数据集上，改进的QA模型与强基准方法相当。

##### URL
[https://arxiv.org/abs/1706.02027](https://arxiv.org/abs/1706.02027)

##### PDF
[https://arxiv.org/pdf/1706.02027](https://arxiv.org/pdf/1706.02027)

