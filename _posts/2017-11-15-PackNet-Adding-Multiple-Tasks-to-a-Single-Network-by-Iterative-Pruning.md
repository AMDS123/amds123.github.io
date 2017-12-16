---
layout: post
title: "PackNet: Adding Multiple Tasks to a Single Network by Iterative Pruning"
date: 2017-11-15 19:36:51
categories: arXiv_CV
tags: arXiv_CV Classification
author: Arun Mallya, Svetlana Lazebnik
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a method for adding multiple tasks to a single deep neural network while avoiding catastrophic forgetting. Inspired by network pruning techniques, we exploit redundancies in large deep networks to free up parameters that can then be employed to learn new tasks. By performing iterative pruning and network re-training, we are able to sequentially "pack" multiple tasks into a single network while ensuring minimal drop in performance and minimal storage overhead. Unlike prior work that uses proxy losses to maintain accuracy on older tasks, we always optimize for the task at hand. We perform extensive experiments on a variety of network architectures and large-scale datasets, and observe much better robustness against catastrophic forgetting than prior work. In particular, we are able to add three fine-grained classification tasks to a single ImageNet-trained VGG-16 network and achieve accuracies close to those of separately trained networks for each task.

##### Abstract (translated by Google)
本文提出了一种将多个任务添加到单个深度神经网络同时避免灾难性遗忘的方法。受网络修剪技术的启发，我们利用大型深度网络中的冗余来释放可用于学习新任务的参数。通过执行迭代修剪和网络重新训练，我们能够将多个任务按顺序“打包”到一个网络中，同时确保最小的性能下降和最小的存储开销。与之前使用代理损失来保持较早任务的准确性的工作不同，我们总是针对当前的任务进行优化。我们在各种网络体系结构和大规模数据集上进行了大量的实验，并观察到比以前的工作更好的抵抗灾难性遗忘。特别是，我们能够将三个细粒度的分类任务添加到单个ImageNet训练的VGG-16网络，并为每个任务实现接近单独训练网络的精度。

##### URL
[https://arxiv.org/abs/1711.05769](https://arxiv.org/abs/1711.05769)

##### PDF
[https://arxiv.org/pdf/1711.05769](https://arxiv.org/pdf/1711.05769)

