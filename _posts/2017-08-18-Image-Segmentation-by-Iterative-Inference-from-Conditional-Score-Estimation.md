---
layout: post
title: "Image Segmentation by Iterative Inference from Conditional Score Estimation"
date: 2017-08-18 22:22:28
categories: arXiv_CV
tags: arXiv_CV Segmentation Inference
author: Adriana Romero, Michal Drozdzal, Akram Erraqabi, Simon Jégou, Yoshua Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by the combination of feedforward and iterative computations in the virtual cortex, and taking advantage of the ability of denoising autoencoders to estimate the score of a joint distribution, we propose a novel approach to iterative inference for capturing and exploiting the complex joint distribution of output variables conditioned on some input variables. This approach is applied to image pixel-wise segmentation, with the estimated conditional score used to perform gradient ascent towards a mode of the estimated conditional distribution. This extends previous work on score estimation by denoising autoencoders to the case of a conditional distribution, with a novel use of a corrupted feedforward predictor replacing Gaussian corruption. An advantage of this approach over more classical ways to perform iterative inference for structured outputs, like conditional random fields (CRFs), is that it is not any more necessary to define an explicit energy function linking the output variables. To keep computations tractable, such energy function parametrizations are typically fairly constrained, involving only a few neighbors of each of the output variables in each clique. We experimentally find that the proposed iterative inference from conditional score estimation by conditional denoising autoencoders performs better than comparable models based on CRFs or those not using any explicit modeling of the conditional joint distribution of outputs.

##### Abstract (translated by Google)
受到虚拟皮层前馈和迭代计算相结合的启发，利用自编码器去噪联合分布评分的能力，提出了一种新的迭代推理方法来捕获和利用输出的复杂联合分布以某些输入变量为条件的变量。该方法被应用于图像逐像素分割，其中估计的条件分数被用来执行梯度上升朝向估计的条件分布的模式。这扩大了先前关于分数估计的工作，通过将自动编码器去噪到条件分布的情况，使用破坏的前馈预测器代替高斯腐败。这种方法相对于更经典的方法来执行结构化输出（如条件随机场（CRF））的迭代推理的优点在于，不需要定义链接输出变量的显式能量函数。为了使计算易于处理，这样的能量函数参数化通常相当受限制，仅涉及每个团体中的每个输出变量的几个邻居。我们通过实验发现，通过条件分数估计，通过条件降噪自动编码器进行的迭代推导比基于CRF的可比较模型或不使用输出的条件联合分布的任何显式建模的模型执行得更好。

##### URL
[https://arxiv.org/abs/1705.07450](https://arxiv.org/abs/1705.07450)

##### PDF
[https://arxiv.org/pdf/1705.07450](https://arxiv.org/pdf/1705.07450)

