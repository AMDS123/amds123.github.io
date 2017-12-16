---
layout: post
title: "Improving image generative models with human interactions"
date: 2017-09-29 15:38:42
categories: arXiv_CV
tags: arXiv_CV GAN Image_Generation
author: Andrew Kyle Lampinen, David So, Douglas Eck, Fred Bertsch
mathjax: true
---

* content
{:toc}

##### Abstract
GANs provide a framework for training generative models which mimic a data distribution. However, in many cases we wish to train these generative models to optimize some auxiliary objective function within the data it generates, such as making more aesthetically pleasing images. In some cases, these objective functions are difficult to evaluate, e.g. they may require human interaction. Here, we develop a system for efficiently improving a GAN to target an objective involving human interaction, specifically generating images that increase rates of positive user interactions. To improve the generative model, we build a model of human behavior in the targeted domain from a relatively small set of interactions, and then use this behavioral model as an auxiliary loss function to improve the generative model. We show that this system is successful at improving positive interaction rates, at least on simulated data, and characterize some of the factors that affect its performance.

##### Abstract (translated by Google)
GAN提供了一个模拟数据分布的生成模型的框架。然而，在许多情况下，我们希望培训这些生成模型，以优化其生成的数据中的一些辅助目标函数，例如制作更美观的图像。在某些情况下，这些目标函数很难评估，例如他们可能需要人际交往。在这里，我们开发了一个系统，有效地提高GAN的目标，涉及人与人之间的互动，特别是生成图像，提高积极的用户互动率。为了改善生成模型，我们从相对较小的一组相互作用中构建了目标领域中的人类行为模型，然后使用这个行为模型作为辅助损失函数来改进生成模型。我们表明，这个系统是成功的改善积极互动率，至少在模拟数据，并表征一些影响其性能的因素。

##### URL
[https://arxiv.org/abs/1709.10459](https://arxiv.org/abs/1709.10459)

##### PDF
[https://arxiv.org/pdf/1709.10459](https://arxiv.org/pdf/1709.10459)

