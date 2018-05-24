---
layout: post
title: "Learning how to be robust: Deep polynomial regression"
date: 2018-05-23 10:21:03
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative
author: Juan-Manuel Perez-Rua, Tomas Crivelli, Patrick Bouthemy, Patrick Perez
mathjax: true
---

* content
{:toc}

##### Abstract
Polynomial regression is a recurrent problem with a large number of applications. In computer vision it often appears in motion analysis. Whatever the application, standard methods for regression of polynomial models tend to deliver biased results when the input data is heavily contaminated by outliers. Moreover, the problem is even harder when outliers have strong structure. Departing from problem-tailored heuristics for robust estimation of parametric models, we explore deep convolutional neural networks. Our work aims to find a generic approach for training deep regression models without the explicit need of supervised annotation. We bypass the need for a tailored loss function on the regression parameters by attaching to our model a differentiable hard-wired decoder corresponding to the polynomial operation at hand. We demonstrate the value of our findings by comparing with standard robust regression methods. Furthermore, we demonstrate how to use such models for a real computer vision problem, i.e., video stabilization. The qualitative and quantitative experiments show that neural networks are able to learn robustness for general polynomial regression, with results that well overpass scores of traditional robust estimation methods.

##### Abstract (translated by Google)
多项式回归是大量应用程序经常遇到的问题。在计算机视觉中，它经常出现在运动分析中。无论什么应用，当输入数据被异常值严重污染时，用于回归多项式模型的标准方法倾向于提供偏差结果。此外，当异常值具有强大的结构时，问题更加严重。从针对参数模型的稳健估计的问题量化启发式出发，我们探索深度卷积神经网络。我们的工作旨在找到一种通用方法来训练深度回归模型，而不需要明确需要监督注释。通过在我们的模型上附加一个与当前多项式操作相对应的可微分硬连线解码器，我们绕过了对回归参数的定制损失函数的需求。我们通过与标准鲁棒回归方法进行比较来证明我们研究结果的价值。此外，我们演示了如何将这些模型用于实际的计算机视觉问题，即视频稳定。定性和定量实验表明，神经网络能够学习一般多项式回归的鲁棒性，其结果是传统鲁棒估计方法的得分超过了分数。

##### URL
[http://arxiv.org/abs/1804.06504](http://arxiv.org/abs/1804.06504)

##### PDF
[http://arxiv.org/pdf/1804.06504](http://arxiv.org/pdf/1804.06504)

