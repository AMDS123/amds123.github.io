---
layout: post
title: "Generalizing to Unseen Domains via Adversarial Data Augmentation"
date: 2018-05-30 15:03:27
categories: arXiv_CV
tags: arXiv_CV Regularization Adversarial Segmentation Semantic_Segmentation Recognition
author: Riccardo Volpi, Hongseok Namkoong, Ozan Sener, John Duchi, Vittorio Murino, Silvio Savarese
mathjax: true
---

* content
{:toc}

##### Abstract
We are concerned with learning models that generalize well to different unseen domains. We consider a worst-case formulation over data distributions that are near the source domain in the feature space. Only using training data from the source domain, we propose an iterative procedure that augments the dataset with examples from a fictitious target domain that is "hard" under the current model. We show that our iterative scheme is an adaptive data augmentation method where we append adversarial examples at each iteration. For softmax losses, we show that our method is a data-dependent regularization scheme that behaves differently from classical regularizers (e.g., ridge or lasso) that regularize towards zero. On digit recognition and semantic segmentation tasks, we empirically observe that our method learns models that improve performance across a priori unknown data distributions

##### Abstract (translated by Google)
我们关注的是能够很好地推广到不同的不可见领域的学习模型。我们考虑在特征空间中靠近源域的数据分布的最坏情况公式。只使用来自源域的训练数据，我们提出了一个迭代过程，用来自目前模型下“虚拟”的虚构目标域的例子来扩充数据集。我们表明，我们的迭代方案是一种自适应数据增强方法，我们在每次迭代中追加敌对示例。对于softmax损失，我们表明我们的方法是一个数据依赖的正则化方案，其行为不同于正规化为零的经典正规化器（例如，脊或套索）。在数字识别和语义分割任务上，我们凭经验观察到，我们的方法学习的模型可以提高跨先验未知数据分布的性能

##### URL
[https://arxiv.org/abs/1805.12018](https://arxiv.org/abs/1805.12018)

##### PDF
[https://arxiv.org/pdf/1805.12018](https://arxiv.org/pdf/1805.12018)

