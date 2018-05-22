---
layout: post
title: "Learning to Multitask"
date: 2018-05-19 08:07:30
categories: arXiv_AI
tags: arXiv_AI GAN Embedding
author: Yu Zhang, Ying Wei, Qiang Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Multitask learning has shown promising performance in many applications and many multitask models have been proposed. In order to identify an effective multitask model for a given multitask problem, we propose a learning framework called learning to multitask (L2MT). To achieve the goal, L2MT exploits historical multitask experience which is organized as a training set consists of several tuples, each of which contains a multitask problem with multiple tasks, a multitask model, and the relative test error. Based on such training set, L2MT first uses a proposed layerwise graph neural network to learn task embeddings for all the tasks in a multitask problem and then learns an estimation function to estimate the relative test error based on task embeddings and the representation of the multitask model based on a unified formulation. Given a new multitask problem, the estimation function is used to identify a suitable multitask model. Experiments on benchmark datasets show the effectiveness of the proposed L2MT framework.

##### Abstract (translated by Google)
多任务学习已经在许多应用中表现出有希望的性能，并且已经提出了许多多任务模型。为了确定一个给定多任务问题的有效多任务模型，我们提出了一个学习框架，叫做多任务学习（L2MT）。为了实现这个目标，L2MT利用历史多任务体验，该体验被组织为由几个元组组成的训练集，其中每个元组包含多任务多任务问题，多任务模型和相对测试错误。基于这样的训练集，L2MT首先使用提出的分层图形神经网络来学习多任务问题中的所有任务的任务嵌入，然后学习估计函数以基于任务嵌入和多任务模型的表示来估计相对测试误差基于统一的表述。给定一个新的多任务问题，估计函数用于确定合适的多任务模型。基准数据集上的实验显示了所提出的L2MT框架的有效性。

##### URL
[https://arxiv.org/abs/1805.07541](https://arxiv.org/abs/1805.07541)

##### PDF
[https://arxiv.org/pdf/1805.07541](https://arxiv.org/pdf/1805.07541)

