---
layout: post
title: "Unsupervised feature learning with discriminative encoder"
date: 2017-09-03 06:40:35
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Classification
author: Gaurav Pandey, Ambedkar Dukkipati
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, deep discriminative models have achieved extraordinary performance on supervised learning tasks, significantly outperforming their generative counterparts. However, their success relies on the presence of a large amount of labeled data. How can one use the same discriminative models for learning useful features in the absence of labels? We address this question in this paper, by jointly modeling the distribution of data and latent features in a manner that explicitly assigns zero probability to unobserved data. Rather than maximizing the marginal probability of observed data, we maximize the joint probability of the data and the latent features using a two step EM-like procedure. To prevent the model from overfitting to our initial selection of latent features, we use adversarial regularization. Depending on the task, we allow the latent features to be one-hot or real-valued vectors and define a suitable prior on the features. For instance, one-hot features correspond to class labels and are directly used for the unsupervised and semi-supervised classification task, whereas real-valued feature vectors are fed as input to simple classifiers for auxiliary supervised discrimination tasks. The proposed model, which we dub discriminative encoder (or DisCoder), is flexible in the type of latent features that it can capture. The proposed model achieves state-of-the-art performance on several challenging tasks.

##### Abstract (translated by Google)
近年来，深层次的判别模型在监督学习任务上取得了非凡的成绩，显着地超越了他们的创造性学习任务。然而，他们的成功依赖于大量标注数据的存在。如何在缺乏标签的情况下使用相同的判别模型来学习有用的特征？在本文中，我们通过联合建模数据和潜在特征的分布，以明确地将零概率分配给未观察的数据的方式来解决这个问题。我们不是最大化观测数据的边际概率，而是使用两步EM类程序来最大化数据和潜在特征的联合概率。为了防止模型过度拟合到我们最初选择的潜在特征，我们使用敌对正则化。根据任务，我们允许潜在特征是一个热点或实值向量，并定义一个合适的特征先验。例如，单一特征对应于类别标签，并直接用于无监督和半监督分类任务，而实值特征向量作为辅助监督区分任务的简单分类器的输入。所提出的模型，我们称之为区分编码器（或DisCoder），它可以捕获的潜在特征的类型是灵活的。所提出的模型在几个具有挑战性的任务上达到了最先进的性能。

##### URL
[https://arxiv.org/abs/1709.00672](https://arxiv.org/abs/1709.00672)

##### PDF
[https://arxiv.org/pdf/1709.00672](https://arxiv.org/pdf/1709.00672)

