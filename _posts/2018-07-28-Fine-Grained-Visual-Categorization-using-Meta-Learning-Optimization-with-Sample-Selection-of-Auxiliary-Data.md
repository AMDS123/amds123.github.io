---
layout: post
title: "Fine-Grained Visual Categorization using Meta-Learning Optimization with Sample Selection of Auxiliary Data"
date: 2018-07-28 09:54:54
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Yabin Zhang, Hui Tang, Kui Jia
mathjax: true
---

* content
{:toc}

##### Abstract
Fine-grained visual categorization (FGVC) is challenging due in part to the fact that it is often difficult to acquire an enough number of training samples. To employ large models for FGVC without suffering from overfitting, existing methods usually adopt a strategy of pre-training the models using a rich set of auxiliary data, followed by fine-tuning on the target FGVC task. However, the objective of pre-training does not take the target task into account, and consequently such obtained models are suboptimal for fine-tuning. To address this issue, we propose in this paper a new deep FGVC model termed MetaFGNet. Training of MetaFGNet is based on a novel regularized meta-learning objective, which aims to guide the learning of network parameters so that they are optimal for adapting to the target FGVC task. Based on MetaFGNet, we also propose a simple yet effective scheme for selecting more useful samples from the auxiliary data. Experiments on benchmark FGVC datasets show the efficacy of our proposed method.

##### Abstract (translated by Google)
细粒度视觉分类（FGVC）具有挑战性，部分原因在于通常难以获得足够数量的训练样本。为了在不遭受过度拟合的情况下使用FGVC的大型模型，现有方法通常采用使用丰富的辅助数据对模型进行预训练的策略，然后对目标FGVC任务进行微调。然而，预训练的目标不是将目标任务考虑在内，因此这样获得的模型对于微调来说是次优的。为了解决这个问题，我们在本文中提出了一种新的深度FGVC模型，称为MetaFGNet。 MetaFGNet的培训基于一种新颖的正则化元学习目标，旨在指导网络参数的学习，使其最适合于适应目标FGVC任务。基于MetaFGNet，我们还提出了一种简单而有效的方案，用于从辅助数据中选择更有用的样本。基准FGVC数据集的实验显示了我们提出的方法的功效。

##### URL
[http://arxiv.org/abs/1807.10916](http://arxiv.org/abs/1807.10916)

##### PDF
[http://arxiv.org/pdf/1807.10916](http://arxiv.org/pdf/1807.10916)

