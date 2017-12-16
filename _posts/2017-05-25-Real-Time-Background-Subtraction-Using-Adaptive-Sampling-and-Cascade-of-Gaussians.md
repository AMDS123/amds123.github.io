---
layout: post
title: "Real-Time Background Subtraction Using Adaptive Sampling and Cascade of Gaussians"
date: 2017-05-25 19:50:45
categories: arXiv_CV
tags: arXiv_CV Classification
author: B Ravi Kiran, Senthil Yogamani
mathjax: true
---

* content
{:toc}

##### Abstract
Background-Foreground classification is a fundamental well-studied problem in computer vision. Due to the pixel-wise nature of modeling and processing in the algorithm, it is usually difficult to satisfy real-time constraints. There is a trade-off between the speed (because of model complexity) and accuracy. Inspired by the rejection cascade of Viola-Jones classifier, we decompose the Gaussian Mixture Model (GMM) into an adaptive cascade of classifiers. This way we achieve a good improvement in speed without compensating for accuracy. In the training phase, we learn multiple KDEs for different durations to be used as strong prior distribution and detect probable oscillating pixels which usually results in misclassifications. We propose a confidence measure for the classifier based on temporal consistency and the prior distribution. The confidence measure thus derived is used to adapt the learning rate and the thresholds of the model, to improve accuracy. The confidence measure is also employed to perform temporal and spatial sampling in a principled way. We demonstrate a speed-up factor of 5x to 10x and 17 percent average improvement in accuracy over several standard videos.

##### Abstract (translated by Google)
背景 - 前景分类是计算机视觉领域一个深入研究的基本问题。由于算法中建模和处理的像素特性，通常难以满足实时约束。速度（由于模型的复杂性）和准确性之间有一个折衷。受到Viola-Jones分类器拒绝级联的启发，我们将高斯混合模型（GMM）分解为分类器的自适应级联。这样，我们在不补偿精度的情况下实现了速度上的好转。在训练阶段，我们学习了不同持续时间的多个KDE，作为强的事先分配，并检测通常会导致错误分类的可能的振荡像素。我们基于时间一致性和先验分布提出了一个分类器的置信度度量。由此导出的置信度量度被用来适应学习率和模型的阈值，以提高准确度。置信度度量也被用来以原则的方式进行时间和空间抽样。我们演示了几个标准视频的5倍到10倍和17％的平均精度提高的加速因子。

##### URL
[https://arxiv.org/abs/1705.09339](https://arxiv.org/abs/1705.09339)

##### PDF
[https://arxiv.org/pdf/1705.09339](https://arxiv.org/pdf/1705.09339)

