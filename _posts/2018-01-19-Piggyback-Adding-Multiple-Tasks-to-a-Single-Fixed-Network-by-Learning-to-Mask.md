---
layout: post
title: "Piggyback: Adding Multiple Tasks to a Single, Fixed Network by Learning to Mask"
date: 2018-01-19 18:25:59
categories: arXiv_CV
tags: arXiv_CV Classification
author: Arun Mallya, Svetlana Lazebnik
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a method for adding multiple tasks to a single, fixed deep neural network without affecting performance on already learned tasks. By building upon concepts from network quantization and sparsification, we learn binary masks that "piggyback", or are applied to an existing network to provide good performance on a new task. These masks are learned in an end-to-end differentiable fashion, and incur a low overhead of 1 bit per network parameter, per task. Even though the underlying network is fixed, the ability to mask certain weights allows for the learning of a large number of filters. We show improved performance on a variety of classification tasks, including those with large domain shifts from the natural images of ImageNet. Unlike prior work, we can augment the capabilities of a network without suffering from catastrophic forgetting or competition between tasks, while incurring the least overhead per added task. We demonstrate the applicability of our method to multiple architectures, and obtain accuracies comparable with individual networks trained per task.

##### Abstract (translated by Google)
这项工作提出了一种方法，将多个任务添加到单个固定的深度神经网络，而不会影响已经学习的任务的性能。通过构建网络量化和稀疏化的概念，我们学习“捎带”的二进制掩码，或者应用到现有网络上，以提供一个新任务的良好性能。这些掩码是以端到端可区分的方式学习的，并且每个任务每个网络参数产生1比特的低开销。即使底层网络是固定的，掩盖某些权重的能力也允许学习大量的过滤器。我们展示了对各种分类任务的改进性能，包括那些从ImageNet的自然图像中有大的域转移的分类任务。与以前的工作不同，我们可以增加网络的能力，而不会遭受灾难性的遗忘或任务之间的竞争，同时每增加一项任务就会产生最少的开销。我们证明了我们的方法适用于多种体系结构，并获得与每个任务训练的单个网络相当的精度。

##### URL
[http://arxiv.org/abs/1801.06519](http://arxiv.org/abs/1801.06519)

##### PDF
[http://arxiv.org/pdf/1801.06519](http://arxiv.org/pdf/1801.06519)

