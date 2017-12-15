---
layout: post
title: "A Deep Structured Model with Radius-Margin Bound for 3D Human Activity Recognition"
date: 2015-12-05 09:02:02
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Classification Deep_Learning Recognition
author: Liang Lin, Keze Wang, Wangmeng Zuo, Meng Wang, Jiebo Luo, Lei Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Understanding human activity is very challenging even with the recently developed 3D/depth sensors. To solve this problem, this work investigates a novel deep structured model, which adaptively decomposes an activity instance into temporal parts using the convolutional neural networks (CNNs). Our model advances the traditional deep learning approaches in two aspects. First, { we incorporate latent temporal structure into the deep model, accounting for large temporal variations of diverse human activities. In particular, we utilize the latent variables to decompose the input activity into a number of temporally segmented sub-activities, and accordingly feed them into the parts (i.e. sub-networks) of the deep architecture}. Second, we incorporate a radius-margin bound as a regularization term into our deep model, which effectively improves the generalization performance for classification. For model training, we propose a principled learning algorithm that iteratively (i) discovers the optimal latent variables (i.e. the ways of activity decomposition) for all training instances, (ii) { updates the classifiers} based on the generated features, and (iii) updates the parameters of multi-layer neural networks. In the experiments, our approach is validated on several complex scenarios for human activity recognition and demonstrates superior performances over other state-of-the-art approaches.

##### Abstract (translated by Google)
即使使用最近开发的3D /深度传感器，了解人类活动也非常具有挑战性。为了解决这个问题，本文研究了一种新型的深层结构模型，该模型使用卷积神经网络（CNN）将一个活动实例自适应地分解为时态部分。我们的模式从两个方面推进了传统的深度学习方法。首先，我们将潜在的时间结构纳入深层模型，考虑到各种人类活动的大时间变化。特别地，我们利用潜变量将输入活动分解成多个时间分割的子活动，并相应地将它们馈送到深层结构的部分（即子网络）中。其次，我们将半径 - 边界界作为正则化项纳入到深层模型中，有效提高了分类的泛化性能。对于模型训练，我们提出了一个有原则的学习算法，该算法迭代地（i）发现所有训练实例的最优潜变量（即活动分解的方式），（ii）{基于所产生的特征来更新分类器} ）更新多层神经网络的参数。在实验中，我们的方法在人类活动识别的多个复杂场景中得到验证，并且表现出优于其他最先进方法的性能。

##### URL
[https://arxiv.org/abs/1512.01642](https://arxiv.org/abs/1512.01642)

##### PDF
[https://arxiv.org/pdf/1512.01642](https://arxiv.org/pdf/1512.01642)

