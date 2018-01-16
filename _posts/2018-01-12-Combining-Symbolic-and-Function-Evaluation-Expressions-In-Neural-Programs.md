---
layout: post
title: "Combining Symbolic and Function Evaluation Expressions In Neural Programs"
date: 2018-01-12 22:24:42
categories: arXiv_AI
tags: arXiv_AI RNN Relation
author: Forough Arabshahi, Sameer Singh, Animashree Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
Neural programming involves training neural networks to learn programs from data. Previous works have failed to achieve good generalization performance, especially on programs with high complexity or on large domains. This is because they mostly rely either on black-box function evaluations that do not capture the structure of the program, or on detailed execution traces that are expensive to obtain, and hence the training data has poor coverage of the domain under consideration. We present a novel framework that utilizes black-box function evaluations, in conjunction with symbolic expressions that integrate relationships between the given functions. We employ tree LSTMs to incorporate the structure of the symbolic expression trees. We use tree encoding for numbers present in function evaluation data, based on their decimal representation. We present an evaluation benchmark for this task to demonstrate our proposed model combines symbolic reasoning and function evaluation in a fruitful manner, obtaining high accuracies in our experiments. Our framework generalizes significantly better to expressions of higher depth and is able to fill partial equations with valid completions.

##### Abstract (translated by Google)
神经编程涉及训练神经网络从数据中学习程序。以前的作品没有达到很好的泛化性能，特别是在复杂程度高或者大的领域。这是因为它们主要依赖于不能捕获程序结构的黑盒函数评估，或者依赖于获取成本昂贵的详细执行痕迹，因此训练数据对所考虑的域的覆盖率较差。我们提出了一个新的框架，利用黑盒函数评估，结合符号表达式，整合给定函数之间的关系。我们使用树LSTM来结合符号表达式树的结构。我们使用树编码来表示函数评估数据中的数字，基于它们的十进制表示。我们提出了一个评估基准这个任务来证明我们提出的模型结合了符号推理和功能评估的卓有成效的方式，在我们的实验中获得了很高的准确性。我们的框架总体上更好地表达更高的深度，并能够用有效的完成填补部分方程。

##### URL
[https://arxiv.org/abs/1801.04342](https://arxiv.org/abs/1801.04342)

##### PDF
[https://arxiv.org/pdf/1801.04342](https://arxiv.org/pdf/1801.04342)

