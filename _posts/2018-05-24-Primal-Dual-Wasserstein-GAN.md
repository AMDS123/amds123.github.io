---
layout: post
title: "Primal-Dual Wasserstein GAN"
date: 2018-05-24 09:47:16
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Inference
author: Mevlana Gemici, Zeynep Akata, Max Welling
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Primal-Dual Wasserstein GAN, a new learning algorithm for building latent variable models of the data distribution based on the primal and the dual formulations of the optimal transport (OT) problem. We utilize the primal formulation to learn a flexible inference mechanism and to create an optimal approximate coupling between the data distribution and the generative model. In order to learn the generative model, we use the dual formulation and train the decoder adversarially through a critic network that is regularized by the approximate coupling obtained from the primal. Unlike previous methods that violate various properties of the optimal critic, we regularize the norm and the direction of the gradients of the critic function. Our model shares many of the desirable properties of auto-encoding models in terms of mode coverage and latent structure, while avoiding their undesirable averaging properties, e.g. their inability to capture sharp visual features when modeling real images. We compare our algorithm with several other generative modeling techniques that utilize Wasserstein distances on Frechet Inception Distance (FID) and Inception Scores (IS).

##### Abstract (translated by Google)
我们引入Primal-Dual Wasserstein GAN，这是一种新的学习算法，用于基于最优传输（OT）问题的原始和双重表达式构建数据分布的潜变量模型。我们利用原始公式学习灵活的推理机制，并在数据分布和生成模型之间创建最佳近似耦合。为了学习生成模型，我们使用双重公式，并通过一个评论者网络来对解码器进行对抗训练，这个评论者网络通过从原始数据中获得的近似耦合进行规则化。与先前的违反最优评论家各种特性的方法不同，我们规范了批评函数梯度的规范和方向。我们的模型在模式覆盖率和潜在结构方面分享了许多自动编码模型的理想特性，同时避免了它们不希望的平均特性，例如，在建模真实图像时无法捕捉清晰的视觉特征。我们将我们的算法与几种其他生成建模技术进行了比较，这些技术在Frechet初始距离（FID）和初始评分（IS）上利用了Wasserstein距离。

##### URL
[https://arxiv.org/abs/1805.09575](https://arxiv.org/abs/1805.09575)

##### PDF
[https://arxiv.org/pdf/1805.09575](https://arxiv.org/pdf/1805.09575)

