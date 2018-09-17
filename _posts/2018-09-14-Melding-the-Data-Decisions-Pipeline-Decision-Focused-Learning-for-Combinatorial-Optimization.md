---
layout: post
title: "Melding the Data-Decisions Pipeline: Decision-Focused Learning for Combinatorial Optimization"
date: 2018-09-14 17:08:04
categories: arXiv_AI
tags: arXiv_AI Optimization Deep_Learning Prediction Gradient_Descent
author: Bryan Wilder, Bistra Dilkina, Milind Tambe
mathjax: true
---

* content
{:toc}

##### Abstract
Creating impact in real-world settings requires artificial intelligence techniques to span the full pipeline from data, to predictive models, to decisions. These components are typically approached separately: a machine learning model is first trained via a measure of predictive accuracy, and then its predictions are used as input into an optimization algorithm which produces a decision. However, the loss function used to train the model may easily be misaligned with the end goal, which is to make the best decisions possible. Hand-tuning the loss function to align with optimization is a difficult and error-prone process (which is often skipped entirely). 
 We focus on combinatorial optimization problems and introduce a general framework for decision-focused learning, where the machine learning model is directly trained in conjunction with the optimization algorithm to produce high-quality decisions. Technically, our contribution is a means of integrating discrete optimization problems into deep learning or other predictive models, which are typically trained via gradient descent. The main idea is to use a continuous relaxation of the discrete problem to propagate gradients through the optimization procedure. We instantiate this framework for two broad classes of combinatorial problems: linear programs and submodular maximization. Experimental results across a variety of domains show that decision-focused learning often leads to improved optimization performance compared to traditional methods. We find that standard measures of accuracy are not a reliable proxy for a predictive model's utility in optimization, and our method's ability to specify the true goal as the model's training objective yields substantial dividends across a range of decision problems.

##### Abstract (translated by Google)
在现实环境中创建影响需要人工智能技术跨越从数据到预测模型到决策的整个流程。这些组件通常是分开处理的：首先通过预测准确度的测量来训练机器学习模型，然后将其预测用作产生决策的优化算法的输入。然而，用于训练模型的损失函数可能很容易与最终目标错位，这是为了做出最佳决策。手动调整损失函数以与优化保持一致是一个困难且容易出错的过程（通常会完全跳过）。
 我们专注于组合优化问题，并为决策重点学习引入一个通用框架，其中机器学习模型与优化算法一起直接训练，以产生高质量的决策。从技术上讲，我们的贡献是将离散优化问题集成到深度学习或其他预测模型中的方法，这些模型通常通过梯度下降进行训练。主要思想是使用离散问题的连续松弛来通过优化过程传播梯度。我们将这个框架实例化为两大类组合问题：线性程序和子模块最大化。跨越各种领域的实验结果表明，与传统方法相比，以决策为中心的学习通常可以提高优化性能。我们发现，准确度的标准度量不是预测模型在优化中的效用的可靠代理，并且我们的方法将真实目标指定为模型的训练目标的能力在一系列决策问题中产生了实质性的分红。

##### URL
[http://arxiv.org/abs/1809.05504](http://arxiv.org/abs/1809.05504)

##### PDF
[http://arxiv.org/pdf/1809.05504](http://arxiv.org/pdf/1809.05504)

