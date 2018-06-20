---
layout: post
title: "Diffeomorphic brain shape modelling using Gauss-Newton optimisation"
date: 2018-06-19 08:52:09
categories: arXiv_CV
tags: arXiv_CV Inference
author: Ya&#xeb;l Balbastre, Mikael Brudfors, Kevin Bronik, John Ashburner
mathjax: true
---

* content
{:toc}

##### Abstract
Shape modelling describes methods aimed at capturing the natural variability of shapes and commonly relies on probabilistic interpretations of dimensionality reduction techniques such as principal component analysis. Due to their computational complexity when dealing with dense deformation models such as diffeomorphisms, previous attempts have focused on explicitly reducing their dimension, diminishing de facto their flexibility and ability to model complex shapes such as brains. In this paper, we present a generative model of shape that allows the covariance structure of deformations to be captured without squashing their domain, resulting in better normalisation. An efficient inference scheme based on Gauss-Newton optimisation is used, which enables processing of 3D neuroimaging data. We trained this algorithm on segmented brains from the OASIS database, generating physiologically meaningful deformation trajectories. To prove the model's robustness, we applied it to unseen data, which resulted in equivalent fitting scores.

##### Abstract (translated by Google)
形状建模描述旨在捕捉形状的自然变化的方法，并且通常依赖于降维技术的概率解释，例如主成分分析。由于处理稠密变形模型（如微分同胚）时的计算复杂性，以前的尝试着重于明确减小它们的尺寸，减小事实上它们的灵活性和模拟复杂形状（如大脑）的能力。在本文中，我们提出了一种形状的生成模型，该模型允许变形的协方差结构被捕获而不压缩它们的域，从而导致更好的归一化。使用基于高斯 - 牛顿优化的高效推理方案，其能够处理3D神经影像数据。我们在来自OASIS数据库的分段大脑上训练了该算法，生成了具有生理意义的变形轨迹。为了证明该模型的鲁棒性，我们将其应用于不可见的数据，这导致了相等的拟合分数。

##### URL
[http://arxiv.org/abs/1806.07109](http://arxiv.org/abs/1806.07109)

##### PDF
[http://arxiv.org/pdf/1806.07109](http://arxiv.org/pdf/1806.07109)

