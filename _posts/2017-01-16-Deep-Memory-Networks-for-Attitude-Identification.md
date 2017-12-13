---
layout: post
title: "Deep Memory Networks for Attitude Identification"
date: 2017-01-16 06:49:01
categories: arXiv_CV
tags: arXiv_CV Sentiment Classification Deep_Learning Detection Memory_Networks
author: Cheng Li, Xiaoxiao Guo, Qiaozhu Mei
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the task of identifying attitudes towards a given set of entities from text. Conventionally, this task is decomposed into two separate subtasks: target detection that identifies whether each entity is mentioned in the text, either explicitly or implicitly, and polarity classification that classifies the exact sentiment towards an identified entity (the target) into positive, negative, or neutral. Instead, we show that attitude identification can be solved with an end-to-end machine learning architecture, in which the two subtasks are interleaved by a deep memory network. In this way, signals produced in target detection provide clues for polarity classification, and reversely, the predicted polarity provides feedback to the identification of targets. Moreover, the treatments for the set of targets also influence each other -- the learned representations may share the same semantics for some targets but vary for others. The proposed deep memory network, the AttNet, outperforms methods that do not consider the interactions between the subtasks or those among the targets, including conventional machine learning methods and the state-of-the-art deep learning models.

##### Abstract (translated by Google)
我们考虑从文本中确定对一组给定实体的态度。通常，这个任务被分解为两个独立的子任务：识别文本中每个实体是否被明确地或隐含地提及的目标检测，以及将确定的情感分类为识别的实体（目标）的极性分类为正面，负面，或中性。相反，我们表明姿态识别可以通过一个端到端的机器学习体系结构来解决，其中两个子任务由深度存储器网络交织。这样，目标检测产生的信号提供了极性分类的线索，相反，预测的极性为目标的识别提供了反馈。而且，针对这组目标的处理也相互影响 - 所学习的表示对于一些目标可以共享相同的语义，但是针对其他的目标可以是不同的。所提出的深度记忆网络AttNet胜过不考虑子任务或目标之间的相互作用的方法，包括传统的机器学习方法和最先进的深度学习模型。

##### URL
[https://arxiv.org/abs/1701.04189](https://arxiv.org/abs/1701.04189)

##### PDF
[https://arxiv.org/pdf/1701.04189](https://arxiv.org/pdf/1701.04189)

