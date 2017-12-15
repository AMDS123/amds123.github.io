---
layout: post
title: "Loss Functions for Top-k Error: Analysis and Insights"
date: 2016-04-13 15:12:01
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Maksim Lapin, Matthias Hein, Bernt Schiele
mathjax: true
---

* content
{:toc}

##### Abstract
In order to push the performance on realistic computer vision tasks, the number of classes in modern benchmark datasets has significantly increased in recent years. This increase in the number of classes comes along with increased ambiguity between the class labels, raising the question if top-1 error is the right performance measure. In this paper, we provide an extensive comparison and evaluation of established multiclass methods comparing their top-k performance both from a practical as well as from a theoretical perspective. Moreover, we introduce novel top-k loss functions as modifications of the softmax and the multiclass SVM losses and provide efficient optimization schemes for them. In the experiments, we compare on various datasets all of the proposed and established methods for top-k error optimization. An interesting insight of this paper is that the softmax loss yields competitive top-k performance for all k simultaneously. For a specific top-k error, our new top-k losses lead typically to further improvements while being faster to train than the softmax.

##### Abstract (translated by Google)
为了推动现实计算机视觉任务的表现，近年来现代基准数据集中的班级数量显着增加。类别数量的增加伴随着类别标签之间的模糊性增加，如果top-1错误是正确的性能指标，则会引发这个问题。在本文中，我们提供了一个广泛的比较和评估已建立的多类方法，从实际和理论角度比较它们的top-k性能。此外，我们引入新的top-k损失函数作为softmax和多类SVM损失的修改，并为它们提供有效的优化方案。在实验中，我们比较了各种数据集的所有提出和建立的top-k误差优化方法。本文的一个有趣的见解是softmax损失同时在所有k上产生竞争性的top-k性能。对于一个特定的top-k错误，我们新的top-k损失通常会进一步提高，同时比softmax更快。

##### URL
[https://arxiv.org/abs/1512.00486](https://arxiv.org/abs/1512.00486)

##### PDF
[https://arxiv.org/pdf/1512.00486](https://arxiv.org/pdf/1512.00486)

