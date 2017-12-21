---
layout: post
title: "Meta-Learning and Universality: Deep Representations and Gradient Descent can Approximate any Learning Algorithm"
date: 2017-12-20 01:38:51
categories: arXiv_AI
tags: arXiv_AI Prediction Gradient_Descent
author: Chelsea Finn, Sergey Levine
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to learn is a powerful paradigm for enabling models to learn from data more effectively and efficiently. A popular approach to meta-learning is to train a recurrent model to read in a training dataset as input and output the parameters of a learned model, or output predictions for new test inputs. Alternatively, a more recent approach to meta-learning aims to acquire deep representations that can be effectively fine-tuned, via standard gradient descent, to new tasks. In this paper, we consider the meta-learning problem from the perspective of universality, formalizing the notion of learning algorithm approximation and comparing the expressive power of the aforementioned recurrent models to the more recent approaches that embed gradient descent into the meta-learner. In particular, we seek to answer the following question: does deep representation combined with standard gradient descent have sufficient capacity to approximate any learning algorithm? We find that this is indeed true, and further find, in our experiments, that gradient-based meta-learning consistently leads to learning strategies that generalize more widely compared to those represented by recurrent models.

##### Abstract (translated by Google)
学习学习是使模型更有效地学习数据的强大范例。一种流行的元学习方法是训练循环模型来读取训练数据集作为输入和输出学习模型的参数，或输出新测试输入的预测。或者，更近期的元学习方法旨在获得可以通过标准梯度下降有效地微调到新任务的深度表示。在本文中，我们从普遍性的角度考虑元学习问题，形式化学习算法近似的概念，并将上述复现模型的表达能力与最近将梯度下降嵌入元学习者的方法进行比较。特别是，我们试图回答以下问题：深度表示与标准梯度下降结合是否具有足够的能力来逼近任何学习算法？我们发现这确实是事实，并且在我们的实验中进一步发现，基于渐变的元学习一贯导致学习策略相对于循环模型所代表的那些泛化更广泛的学习策略。

##### URL
[http://arxiv.org/abs/1710.11622](http://arxiv.org/abs/1710.11622)

##### PDF
[http://arxiv.org/pdf/1710.11622](http://arxiv.org/pdf/1710.11622)

