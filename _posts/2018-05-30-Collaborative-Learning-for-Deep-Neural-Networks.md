---
layout: post
title: "Collaborative Learning for Deep Neural Networks"
date: 2018-05-30 00:46:33
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge Inference
author: Guocong Song, Wei Chai
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce collaborative learning in which multiple classifier heads of the same network are simultaneously trained on the same training data to improve generalization and robustness to label noise with no extra inference cost. It acquires the strengths from auxiliary training, multi-task learning and knowledge distillation. There are two important mechanisms involved in collaborative learning. First, the consensus of multiple views from different classifier heads on the same example provides supplementary information as well as regularization to each classifier, thereby improving generalization. Second, intermediate-level representation (ILR) sharing with backpropagation rescaling aggregates the gradient flows from all heads, which not only reduces training computational complexity, but also facilitates supervision to the shared layers. The empirical results on CIFAR and ImageNet datasets demonstrate that deep neural networks learned as a group in a collaborative way significantly reduce the generalization error and increase the robustness to label noise.

##### Abstract (translated by Google)
我们引入了协作学习，其中同一网络的多个分类器头同时训练在相同的训练数据上，以改善对标签噪声的泛化和鲁棒性，而不需要额外的推理成本。它从辅助培训，多任务学习和知识蒸馏中获得优势。协作学习有两个重要的机制。首先，来自不同分类器头的多个视图对同一个例子的共识为每个分类器提供了补充信息和正则化，从而改善了泛化。其次，中间级别表示（ILR）与反向传播重新缩放共享来自所有负责人的梯度流，这不仅降低了训练计算的复杂性，而且有助于监督共享层。 CIFAR和ImageNet数据集上的实验结果表明，以协作方式学习为一组的深度神经网络显着减少了泛化误差，并提高了对标签噪声的鲁棒性。

##### URL
[https://arxiv.org/abs/1805.11761](https://arxiv.org/abs/1805.11761)

##### PDF
[https://arxiv.org/pdf/1805.11761](https://arxiv.org/pdf/1805.11761)

