---
layout: post
title: "Feature Affinity based Pseudo Labeling for Semi-supervised Person Re-identification"
date: 2018-05-16 03:42:36
categories: arXiv_CV
tags: arXiv_CV Regularization Re-identification Adversarial Person_Re-identification Represenation_Learning Relation
author: Guodong Ding, Shanshan Zhang, Salman Khan, Zhenmin Tang, Jian Zhang, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification aims to match a person's identity across multiple camera streams. Deep neural networks have been successfully applied to the challenging person re-identification task. One remarkable bottleneck is that the existing deep models are data hungry and require large amounts of labeled training data. Acquiring manual annotations for pedestrian identity matchings in large-scale surveillance camera installations is a highly cumbersome task. Here, we propose the first semi-supervised approach that performs pseudo-labeling by considering complex relationships between unlabeled and labeled training samples in the feature space. Our approach first approximates the actual data manifold by learning a generative model via adversarial training. Given the trained model, data augmentation can be performed by generating new synthetic data samples which are unlabeled. An open research problem is how to effectively use this additional data for improved feature learning. To this end, this work proposes a novel Feature Affinity based Pseudo-Labeling (FAPL) approach with two possible label encodings under a unified setting. Our approach measures the affinity of unlabeled samples with the underlying clusters of labeled data samples using the intermediate feature representations from deep networks. FAPL trains with the joint supervision of cross-entropy loss together with a center regularization term, which not only ensures discriminative feature representation learning but also simultaneously predicts pseudo-labels for unlabeled data. Our extensive experiments on two standard large-scale datasets, Market-1501 and DukeMTMC-reID, demonstrate significant performance boosts over closely related competitors and outperforms state-of-the-art person re-identification techniques in most cases.

##### Abstract (translated by Google)
个人重新识别旨在匹配多个相机流中的个人身份。深度神经网络已成功应用于具有挑战性的人员重新识别任务。一个显着的瓶颈是现有的深层模型数据饥渴且需要大量标记的训练数据。在大型监视摄像机装置中获取手动标注行人身份匹配是非常繁琐的任务。在这里，我们提出了第一个半监督方法，通过考虑特征空间中未标记和标记训练样本之间的复杂关系来执行伪标记。我们的方法首先通过对抗训练学习生成模型来近似实际的数据流形。给定训练模型，可以通过生成未标记的新合成数据样本来执行数据增强。一个开放的研究问题是如何有效地使用这些额外的数据来改进特征学习。为此，本工作提出了一种基于特征相关性的伪标签（FAPL）方法，该方法在统一设置下具有两种可能的标签编码。我们的方法使用来自深度网络的中间特征表示来测量未标记样本与标记数据样本的基础聚类的亲和性。 FAPL训练联合监督交叉熵损失和中心正则化项，这不仅确保了有区别的特征表示学习，而且还可以同时预测未标记数据的伪标签。我们在两个标准大型数据集Market-1501和DukeMMC-reID上进行的大量实验证明，与密切相关的竞争对手相比，性能显着提升，并且在大多数情况下胜过最先进的人员重新识别技术。

##### URL
[http://arxiv.org/abs/1805.06118](http://arxiv.org/abs/1805.06118)

##### PDF
[http://arxiv.org/pdf/1805.06118](http://arxiv.org/pdf/1805.06118)

