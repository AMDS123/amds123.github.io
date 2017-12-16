---
layout: post
title: "Efficient Version-Space Reduction for Visual Tracking"
date: 2017-04-02 14:00:48
categories: arXiv_CV
tags: arXiv_CV Tracking Classification
author: Kourosh Meshgi, Shigeyuki Oba, Shin Ishii
mathjax: true
---

* content
{:toc}

##### Abstract
Discrminative trackers, employ a classification approach to separate the target from its background. To cope with variations of the target shape and appearance, the classifier is updated online with different samples of the target and the background. Sample selection, labeling and updating the classifier is prone to various sources of errors that drift the tracker. We introduce the use of an efficient version space shrinking strategy to reduce the labeling errors and enhance its sampling strategy by measuring the uncertainty of the tracker about the samples. The proposed tracker, utilize an ensemble of classifiers that represents different hypotheses about the target, diversify them using boosting to provide a larger and more consistent coverage of the version-space and tune the classifiers' weights in voting. The proposed system adjusts the model update rate by promoting the co-training of the short-memory ensemble with a long-memory oracle. The proposed tracker outperformed state-of-the-art trackers on different sequences bearing various tracking challenges.

##### Abstract (translated by Google)
Discrminative跟踪器，采用分类方法将目标从背景中分离出来。为了应对目标形状和外观的变化，使用目标和背景的不同样本在线更新分类器。样本选择，标记和更新分类器容易出现漂移跟踪器的各种错误来源。我们介绍了使用高效的版本空间缩小策略，通过测量跟踪器关于样本的不确定性来减少标签错误并提高其采样策略。所提出的跟踪器利用代表关于目标的不同假设的分类器集合，使用提升来使它们多样化以提供对版本空间的更大和更一致的覆盖，并调整分类器在投票中的权重。所提出的系统通过促进短记忆集成与长记忆预言的协同训练来调整模型更新速率。所提出的跟踪器在不同序列上优于最新跟踪器，这些跟踪器具有各种跟踪挑战。

##### URL
[https://arxiv.org/abs/1704.00299](https://arxiv.org/abs/1704.00299)

##### PDF
[https://arxiv.org/pdf/1704.00299](https://arxiv.org/pdf/1704.00299)

