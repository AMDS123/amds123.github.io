---
layout: post
title: "CDVAE: Co-embedding Deep Variational Auto Encoder for Conditional Variational Generation"
date: 2017-03-28 03:21:34
categories: arXiv_CV
tags: arXiv_CV Embedding Prediction Quantitative
author: Jiajun Lu, Aditya Deshpande, David Forsyth
mathjax: true
---

* content
{:toc}

##### Abstract
Problems such as predicting a new shading field (Y) for an image (X) are ambiguous: many very distinct solutions are good. Representing this ambiguity requires building a conditional model P(Y|X) of the prediction, conditioned on the image. Such a model is difficult to train, because we do not usually have training data containing many different shadings for the same image. As a result, we need different training examples to share data to produce good models. This presents a danger we call "code space collapse" - the training procedure produces a model that has a very good loss score, but which represents the conditional distribution poorly. We demonstrate an improved method for building conditional models by exploiting a metric constraint on training data that prevents code space collapse. We demonstrate our model on two example tasks using real data: image saturation adjustment, image relighting. We describe quantitative metrics to evaluate ambiguous generation results. Our results quantitatively and qualitatively outperform different strong baselines.

##### Abstract (translated by Google)
诸如预测图像（X）的新着色场（Y）的问题是不明确的：许多非常不同的解决方案是好的。表示这种模糊性需要建立一个以图像为条件的预测条件模型P（Y | X）。这样的模型很难训练，因为我们通常没有包含许多不同阴影的训练数据用于同一图像。因此，我们需要不同的训练实例来分享数据以产生好的模型。这提出了一个危险，我们称之为“代码空间崩溃” - 训练过程产生了一个非常好的损失评分模型，但是代表了条件分布很差。我们演示了一种改进的方法，通过在训练数据上利用度量约束来构建条件模型，以防止代码空间崩溃。我们使用真实数据在两个示例任务上演示了我们的模型：图像饱和度调整，图像重新照明。我们描述量化指标来评估模糊的生成结果。我们的研究结果在数量和质量上均优于不同的强基线。

##### URL
[https://arxiv.org/abs/1612.00132](https://arxiv.org/abs/1612.00132)

##### PDF
[https://arxiv.org/pdf/1612.00132](https://arxiv.org/pdf/1612.00132)

