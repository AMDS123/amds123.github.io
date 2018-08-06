---
layout: post
title: "Ask, Acquire, and Attack: Data-free UAP Generation using Class Impressions"
date: 2018-08-03 11:02:26
categories: arXiv_CV
tags: arXiv_CV Adversarial Inference Deep_Learning
author: Konda Reddy Mopuri, Phani Krishna Uppala, R. Venkatesh Babu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning models are susceptible to input specific noise, called adversarial perturbations. Moreover, there exist input-agnostic noise, called Universal Adversarial Perturbations (UAP) that can affect inference of the models over most input samples. Given a model, there exist broadly two approaches to craft UAPs: (i) data-driven: that require data, and (ii) data-free: that do not require data samples. Data-driven approaches require actual samples from the underlying data distribution and craft UAPs with high success (fooling) rate. However, data-free approaches craft UAPs without utilizing any data samples and therefore result in lesser success rates. In this paper, for data-free scenarios, we propose a novel approach that emulates the effect of data samples with class impressions in order to craft UAPs using data-driven objectives. Class impression for a given pair of category and model is a generic representation (in the input space) of the samples belonging to that category. Further, we present a neural network based generative model that utilizes the acquired class impressions to learn crafting UAPs. Experimental evaluation demonstrates that the learned generative model, (i) readily crafts UAPs via simple feed-forwarding through neural network layers, and (ii) achieves state-of-the-art success rates for data-free scenario and closer to that for data-driven setting without actually utilizing any data samples.

##### Abstract (translated by Google)
深度学习模型易受输入特定噪声的影响，称为对抗性扰动。此外，存在输入不可知噪声，称为通用对抗扰动（UAP），其可以影响大多数输入样本上的模型的推断。给定一个模型，存在两种制定UAP的方法：（i）数据驱动：需要数据，（ii）无数据：不需要数据样本。数据驱动方法需要来自基础数据分布的实际样本和工艺UAP，并且成功率很高（愚弄）。然而，无数据方法在不使用任何数据样本的情况下制定UAP，因此导致较低的成功率。在本文中，对于无数据场景，我们提出了一种新方法，该方法模拟数据样本与类印象的影响，以便使用数据驱动目标来制定UAP。给定的类别和模型对的类别印象是属于该类别的样本的通用表示（在输入空间中）。此外，我们提出了一个基于神经网络的生成模型，利用获得的类印象来学习制作UAP。实验评估表明，学习的生成模型，（i）通过神经网络层通过简单的前馈方式轻松制作UAP，以及（ii）实现无数据方案的最新成功率，更接近数据的成功率驱动设置，而不实际使用任何数据样本。

##### URL
[http://arxiv.org/abs/1808.01153](http://arxiv.org/abs/1808.01153)

##### PDF
[http://arxiv.org/pdf/1808.01153](http://arxiv.org/pdf/1808.01153)

