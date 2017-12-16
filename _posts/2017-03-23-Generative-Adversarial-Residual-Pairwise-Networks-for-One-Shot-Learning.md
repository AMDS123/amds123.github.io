---
layout: post
title: "Generative Adversarial Residual Pairwise Networks for One Shot Learning"
date: 2017-03-23 12:19:09
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial GAN Optimization Classification
author: Akshay Mehrotra, Ambedkar Dukkipati
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks achieve unprecedented performance levels over many tasks and scale well with large quantities of data, but performance in the low-data regime and tasks like one shot learning still lags behind. While recent work suggests many hypotheses from better optimization to more complicated network structures, in this work we hypothesize that having a learnable and more expressive similarity objective is an essential missing component. Towards overcoming that, we propose a network design inspired by deep residual networks that allows the efficient computation of this more expressive pairwise similarity objective. Further, we argue that regularization is key in learning with small amounts of data, and propose an additional generator network based on the Generative Adversarial Networks where the discriminator is our residual pairwise network. This provides a strong regularizer by leveraging the generated data samples. The proposed model can generate plausible variations of exemplars over unseen classes and outperforms strong discriminative baselines for few shot classification tasks. Notably, our residual pairwise network design outperforms previous state-of-theart on the challenging mini-Imagenet dataset for one shot learning by getting over 55% accuracy for the 5-way classification task over unseen classes.

##### Abstract (translated by Google)
深度神经网络在许多任务中实现了前所未有的性能水平，并且能够大规模地处理大量的数据，但是在低数据机制和一次学习等任务中的性能仍然落后。虽然最近的工作提出了许多假设，从更好的优化到更复杂的网络结构，但在这项工作中，我们假设有一个可学习和更具表达性的相似性目标是一个重要的缺失组件。为了克服这个问题，我们提出一个受深度残留网络启发的网络设计，可以有效地计算这个更具表达性的成对相似性目标。此外，我们认为正则化是学习少量数据的关键，并提出了一个基于生成对手网络的附加生成器网络，其中鉴别器是我们的残余成对网络。通过利用生成的数据样本，这提供了强大的正规化器。所提出的模型可以产生对看不见的类的示例的合理变化，并且对于少数镜头分类任务胜过强烈的区分性基线。值得注意的是，我们的剩余成对网络设计胜过以前的迷你小型Imagenet数据集的一个镜头，通过超过55％的准确性，5分类任务看不见的类学习现状。

##### URL
[https://arxiv.org/abs/1703.08033](https://arxiv.org/abs/1703.08033)

##### PDF
[https://arxiv.org/pdf/1703.08033](https://arxiv.org/pdf/1703.08033)

