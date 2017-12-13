---
layout: post
title: "ADA: A Game-Theoretic Perspective on Data Augmentation for Object Detection"
date: 2017-12-12 15:20:22
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection Detection
author: Sima Behpour, Kris M. Kitani, Brian D. Ziebart
mathjax: true
---

* content
{:toc}

##### Abstract
The use of random perturbations of ground truth data, such as random translation or scaling of bounding boxes, is a common heuristic used for data augmentation that has been shown to prevent overfitting and improve generalization. Since the design of data augmentation is largely guided by reported best practices, it is difficult to understand if those design choices are optimal. To provide a more principled perspective, we develop a game-theoretic interpretation of data augmentation in the context of object detection. We aim to find an optimal adversarial perturbations of the ground truth data (i.e., the worst case perturbations) that forces the object bounding box predictor to learn from the hardest distribution of perturbed examples for better test-time performance. We establish that the game theoretic solution, the Nash equilibrium, provides both an optimal predictor and optimal data augmentation distribution. We show that our adversarial method of training a predictor can significantly improve test time performance for the task of object detection. On the ImageNet object detection task, our adversarial approach improves performance by over 16\% compared to the best performing data augmentation method

##### Abstract (translated by Google)
使用地面真实数据的随机扰动，例如随机平移或边界框的缩放，是用于数据增强的常用启发式，已被证明可防止过度拟合并改善泛化。由于数据增强的设计在很大程度上由已报告的最佳实践指导，因此很难理解这些设计选择是否是最佳的。为了提供一个更加原则性的观点，我们在对象检测的背景下开发了数据增强的博弈论解释。我们的目标是寻找迫使对象边界框预测器从最困难的例子分布中学习以获得更好的测试时间性能的地面真实数据的最佳对抗扰动（即最坏情况扰动）。我们建立博弈论解，即纳什均衡，既提供了最优预测器，又提供了最优数据增量分布。我们表明，我们的训练预测器的对抗方法可以显着提高对象检测任务的测试时间性能。在ImageNet对象检测任务中，与最佳执行数据增强方法相比，我们的对抗方法将性能提高了16％以上

##### URL
[http://arxiv.org/abs/1710.07735](http://arxiv.org/abs/1710.07735)

##### PDF
[http://arxiv.org/pdf/1710.07735](http://arxiv.org/pdf/1710.07735)

