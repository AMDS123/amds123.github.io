---
layout: post
title: "Deep Bilevel Learning"
date: 2018-09-05 12:50:24
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization Gradient_Descent
author: Simon Jenni, Paolo Favaro
mathjax: true
---

* content
{:toc}

##### Abstract
We present a novel regularization approach to train neural networks that enjoys better generalization and test error than standard stochastic gradient descent. Our approach is based on the principles of cross-validation, where a validation set is used to limit the model overfitting. We formulate such principles as a bilevel optimization problem. This formulation allows us to define the optimization of a cost on the validation set subject to another optimization on the training set. The overfitting is controlled by introducing weights on each mini-batch in the training set and by choosing their values so that they minimize the error on the validation set. In practice, these weights define mini-batch learning rates in a gradient descent update equation that favor gradients with better generalization capabilities. Because of its simplicity, this approach can be integrated with other regularization methods and training schemes. We evaluate extensively our proposed algorithm on several neural network architectures and datasets, and find that it consistently improves the generalization of the model, especially when labels are noisy.

##### Abstract (translated by Google)
我们提出了一种新的正则化方法来训练神经网络，该方法比标准随机梯度下降具有更好的泛化和测试误差。我们的方法基于交叉验证原则，其中验证集用于限制模型过度拟合。我们制定了诸如双层优化问题的原则。该公式允许我们根据训练集上的另一个优化来定义验证集上的成本优化。通过在训练集中的每个小批量上引入权重并通过选择它们的值来控制过度拟合，以便它们最小化验证集上的误差。在实践中，这些权重定义了梯度下降更新方程中的小批量学习速率，该方程有利于具有更好泛化能力的梯度。由于其简单性，这种方法可以与其他正则化方法和培训方案集成。我们在几个神经网络架构和数据集上广泛评估了我们提出的算法，发现它一直在改进模型的泛化，特别是当标签有噪声时。

##### URL
[http://arxiv.org/abs/1809.01465](http://arxiv.org/abs/1809.01465)

##### PDF
[http://arxiv.org/pdf/1809.01465](http://arxiv.org/pdf/1809.01465)

