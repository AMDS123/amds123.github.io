---
layout: post
title: "Number Sequence Prediction Problems and Computational Powers of Neural Network Models"
date: 2018-05-19 02:36:13
categories: arXiv_AI
tags: arXiv_AI RNN Prediction
author: Hyoungwook Nam, Segwang Kim, Kyomin Jung
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by number series tests to measure human intelligence, we suggest number sequence prediction tasks to assess neural network models' computational powers for solving algorithmic problems. We define complexity and difficulty of a number sequence prediction task with the structure of the smallest automation that can generate the sequence. We suggest two types of number sequence prediction problems: the number-level and the digit-level problems. The number-level problems format sequences as 2-dimensional grids of digits, and the digit-level problem provides a single digit input per a time step, hence solving this problem is equivalent to modeling a sequential state automation. The complexity of a number-level sequence problem can be defined with the depth of an equivalent combinatorial logic. Experimental results with CNN models suggest that they are capable of learning the compound operations of the number-level sequence generation rules but the depths of the compound operations are limited. For the digit-level problems, GRU and LSTM models can solve the problems with complexity of finite state automations, but they cannot solve the problems with complexity of pushdown automations or Turing machines. The results show that our number sequence prediction problems effectively evaluate machine learning models' computational capabilities.

##### Abstract (translated by Google)
受数字系列测试的启发以测量人类智能，我们建议数字序列预测任务，以评估神经网络模型用于解决算法问题的计算能力。我们用最小的自动化结构来定义序列预测任务的复杂性和难度，从而生成序列。我们建议两种类型的数字序列预测问题：数字级别和数字级别问题。数字级问题将序列格式化为二维数字网格，而数字级问题提供每个时间步的单个数字输入，因此解决此问题等同于对顺序状态自动化进行建模。数字级序列问题的复杂性可以用等效组合逻辑的深度来定义。 CNN模型的实验结果表明，他们能够学习数字级序列生成规则的复合操作，但复合操作的深度是有限的。对于数字级问题，GRU和LSTM模型可以解决有限状态自动化的复杂性问题，但它们不能解决下推自动化或图灵机复杂性的问题。结果表明我们的序列预测问题有效地评估了机器学习模型的计算能力。

##### URL
[https://arxiv.org/abs/1805.07494](https://arxiv.org/abs/1805.07494)

##### PDF
[https://arxiv.org/pdf/1805.07494](https://arxiv.org/pdf/1805.07494)

