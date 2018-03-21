---
layout: post
title: "Hierarchical Metric Learning and Matching for 2D and 3D Geometric Correspondences"
date: 2018-03-20 03:11:41
categories: arXiv_CV
tags: arXiv_CV Regularization CNN
author: Mohammed E. Fathy, Quoc-Huy Tran, M. Zeeshan Zia, Paul Vernaza, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
Interest point descriptors have fueled progress on almost every problem in computer vision. Recent advances in deep neural networks have enabled task-specific learned descriptors that outperform hand-crafted descriptors on many problems. We demonstrate that commonly used metric learning approaches do not optimally leverage the feature hierarchies learned in a Convolutional Neural Network (CNN), especially when applied to the task of geometric feature matching. While a metric loss applied to the deepest layer of a CNN, is often expected to yield ideal features irrespective of the task, in fact the growing receptive field as well as striding effects cause shallower features to be better at high precision matching tasks. We leverage this insight together with explicit supervision at multiple levels of the feature hierarchy for better regularization, to learn more effective descriptors in the context of geometric matching tasks. Further, we propose to use activation maps at different layers of a CNN, as an effective and principled replacement for the multi-resolution image pyramids often used for matching tasks. We propose concrete CNN architectures employing these ideas, and evaluate them on multiple datasets for 2D and 3D geometric matching as well as optical flow, demonstrating state-of-the-art results and generalization across datasets.

##### Abstract (translated by Google)
兴趣点描述符已经推动了几乎所有计算机视觉问题的进展。深度神经网络的最新进展使特定于任务的学习描述符在许多问题上的表现优于手工描述符。我们证明常用的度量学习方法不能最优地利用卷积神经网络（CNN）中学习到的特征层次结构，特别是当应用于几何特征匹配任务时。尽管应用于CNN最深层的度量损失通常预期会产生理想的特征而与任务无关，但事实上越来越多的接受领域和跨越效应导致更浅的特征在高精度匹配任务中更好。我们利用这种洞察力与明确的监督在特征层次结构的多个层次上进行更好的正则化，以在几何匹配任务的背景下学习更有效的描述符。此外，我们建议在CNN的不同层使用激活图，作为经常用于匹配任务的多分辨率图像金字塔的有效且有原则的替代。我们提出采用这些想法的具体CNN架构，并在多个数据集上评估它们的二维和三维几何匹配以及光流，从而展示数据集中的最新结果和泛化。

##### URL
[http://arxiv.org/abs/1803.07231](http://arxiv.org/abs/1803.07231)

##### PDF
[http://arxiv.org/pdf/1803.07231](http://arxiv.org/pdf/1803.07231)

