---
layout: post
title: "A Stochastic Large Deformation Model for Computational Anatomy"
date: 2016-12-16 00:45:46
categories: arXiv_CV
tags: arXiv_CV GAN
author: Alexis Arnaudon, Darryl D. Holm, Akshay Pai, Stefan Sommer
mathjax: true
---

* content
{:toc}

##### Abstract
In the study of shapes of human organs using computational anatomy, variations are found to arise from inter-subject anatomical differences, disease-specific effects, and measurement noise. This paper introduces a stochastic model for incorporating random variations into the Large Deformation Diffeomorphic Metric Mapping (LDDMM) framework. By accounting for randomness in a particular setup which is crafted to fit the geometrical properties of LDDMM, we formulate the template estimation problem for landmarks with noise and give two methods for efficiently estimating the parameters of the noise fields from a prescribed data set. One method directly approximates the time evolution of the variance of each landmark by a finite set of differential equations, and the other is based on an Expectation-Maximisation algorithm. In the second method, the evaluation of the data likelihood is achieved without registering the landmarks, by applying bridge sampling using a stochastically perturbed version of the large deformation gradient flow algorithm. The method and the estimation algorithms are experimentally validated on synthetic examples and shape data of human corpora callosa.

##### Abstract (translated by Google)
在使用计算解剖学研究人体器官的形状时，发现由主体间解剖差异，疾病特异性效应和测量噪声引起的变化。本文引入随机模型，将随机变量纳入大变形量子映射度量映射（LDDMM）框架。通过考虑特定设置中的随机性来拟合LDDMM的几何特性，我们制定了噪声地标的模板估计问题，并给出了从指定数据集有效估计噪声场参数的两种方法。一种方法通过一组有限的微分方程直接近似每个界标的方差的时间演化，另一种方法基于期望 - 最大化算法。在第二种方法中，通过使用大变形梯度流算法的随机扰动版本进行桥采样来实现数据可能性的评估而不登记地标。该方法和估计算法在人体语料库的合成实例和形状数据上进行了实验验证。

##### URL
[https://arxiv.org/abs/1612.05323](https://arxiv.org/abs/1612.05323)

##### PDF
[https://arxiv.org/pdf/1612.05323](https://arxiv.org/pdf/1612.05323)

