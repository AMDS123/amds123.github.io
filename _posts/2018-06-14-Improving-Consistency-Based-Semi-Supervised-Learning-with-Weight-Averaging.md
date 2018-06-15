---
layout: post
title: "Improving Consistency-Based Semi-Supervised Learning with Weight Averaging"
date: 2018-06-14 14:58:36
categories: arXiv_CV
tags: arXiv_CV Regularization Face
author: Ben Athiwaratkun, Marc Finzi, Pavel Izmailov, Andrew Gordon Wilson
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in deep unsupervised learning have renewed interest in semi-supervised methods, which can learn from both labeled and unlabeled data. Presently the most successful approaches to semi-supervised learning are based on consistency regularization, whereby a model is trained to be robust to small perturbations of its inputs and parameters. We show that consistency regularization leads to flatter but narrower optima. We also show that the test error surface for these methods is approximately convex in regions of weight space traversed by SGD. Inspired by these observations, we propose to train consistency based semi-supervised models with stochastic weight averaging (SWA), a recent method which averages weights along the trajectory of SGD. We also develop fast-SWA, which further accelerates convergence by averaging multiple points within each cycle of a cyclical learning rate schedule. With fast-SWA we achieve the best known semi-supervised results on CIFAR-10 and CIFAR-100 over many different numbers of observed training labels. For example, we achieve 5.0% error on CIFAR-10 with only 4000 labels, compared to 6.28% of the previous best result in the literature. We also improve the best known result from 80% accuracy to 83% for domain adaptation from CIFAR-10 to STL. Finally, we show that with fast-SWA the simple $\Pi$ model becomes state-of-the-art for large labeled settings.

##### Abstract (translated by Google)
深度无监督学习的最新进展重新引起了对半监督方法的兴趣，它们可以从标记和未标记的数据中学习。目前最成功的半监督学习方法是基于一致性正则化的，因此模型被训练成对其输入和参数的小扰动是鲁棒的。我们表明，一致性正则化导致更平坦但更窄的最优值。我们还表明，这些方法的测试误差表面在SGD所穿过的重量空间区域内近似凸起。受这些观察的启发，我们提出使用随机加权平均（SWA）来训练基于一致性的半监督模型，SWA是最近一种沿SGD的轨迹平均权重的方法。我们还开发快速SWA，通过平均周期性学习速率时间表的每个周期内的多个点来进一步加速收敛。使用快速SWA，我们在CIFAR-10和CIFAR-100上实现了许多不同数量的观察训练标签上最有名的半监督结果。例如，我们在CIFAR-10上只有4000个标签，误差为5.0％，而文献中以前的最佳结果为6.28％。我们还将从CIFAR-10到STL的领域适应从80％的准确度提高到83％的最佳结果。最后，我们展示了使用快速SWA，简单的$ \ Pi $模型成为大型标签设置的最新技术。

##### URL
[http://arxiv.org/abs/1806.05594](http://arxiv.org/abs/1806.05594)

##### PDF
[http://arxiv.org/pdf/1806.05594](http://arxiv.org/pdf/1806.05594)

