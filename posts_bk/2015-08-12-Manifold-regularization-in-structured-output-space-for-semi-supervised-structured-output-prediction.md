---
layout: post
title: "Manifold regularization in structured output space for semi-supervised structured output prediction"
date: 2015-08-12 08:44:47
categories: arXiv_CV
tags: arXiv_CV Regularization Prediction
author: Fei Jiang, Lili Jia, Xiaobao Sheng, Riley LeMieux
mathjax: true
---

* content
{:toc}

##### Abstract
Structured output prediction aims to learn a predictor to predict a structured output from a input data vector. The structured outputs include vector, tree, sequence, etc. We usually assume that we have a training set of input-output pairs to train the predictor. However, in many real-world appli- cations, it is difficult to obtain the output for a input, thus for many training input data points, the structured outputs are missing. In this paper, we dis- cuss how to learn from a training set composed of some input-output pairs, and some input data points without outputs. This problem is called semi- supervised structured output prediction. We propose a novel method for this problem by constructing a nearest neighbor graph from the input space to present the manifold structure, and using it to regularize the structured out- put space directly. We define a slack structured output for each training data point, and proposed to predict it by learning a structured output predictor. The learning of both slack structured outputs and the predictor are unified within one single minimization problem. In this problem, we propose to mini- mize the structured loss between the slack structured outputs of neighboring data points, and the prediction error measured by the structured loss. The problem is optimized by an iterative algorithm. Experiment results over three benchmark data sets show its advantage.

##### Abstract (translated by Google)
结构化输出预测旨在学习一个预测器来预测来自输入数据向量的结构化输出。结构化输出包括向量，树，序列等。我们通常假设我们有一组输入 - 输出对训练预测器。但是，在许多实际应用中，很难获得输入的输出，因此对于许多训练输入数据点，结构化的输出是丢失的。在本文中，我们讨论如何从一些输入 - 输出对组成的训练集以及一些没有输出的输入数据点学习。这个问题被称为半监督结构化输出预测。我们提出了一种新的方法来解决这个问题，从输入空间构造一个最近邻图来呈现流形结构，并用它直接调整结构输出空间。我们为每个训练数据点定义一个松散结构的输出，并提出通过学习一个结构化的输出预测器来预测它。松散结构输出和预测器的学习在一个单一的最小化问题内统一。在这个问题中，我们建议最小化相邻数据点的松散结构输出之间的结构性损失，以及由结构化损失测量的预测误差。该问题通过迭代算法进行了优化。三个基准数据集的实验结果显示了它的优势。

##### URL
[https://arxiv.org/abs/1508.02849](https://arxiv.org/abs/1508.02849)

##### PDF
[https://arxiv.org/pdf/1508.02849](https://arxiv.org/pdf/1508.02849)

