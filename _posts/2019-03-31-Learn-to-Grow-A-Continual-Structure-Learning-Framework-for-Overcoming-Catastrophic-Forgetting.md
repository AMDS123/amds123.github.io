---
layout: post
title: "Learn to Grow: A Continual Structure Learning Framework for Overcoming Catastrophic Forgetting"
date: 2019-03-31 00:35:36
categories: arXiv_CV
tags: arXiv_CV Optimization Deep_Learning
author: Xilai Li, Yingbo Zhou, Tianfu Wu, Richard Socher, Caiming Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Addressing catastrophic forgetting is one of the key challenges in continual learning where machine learning systems are trained with sequential or streaming tasks. Despite recent remarkable progress in state-of-the-art deep learning, deep neural networks (DNNs) are still plagued with the catastrophic forgetting problem. This paper presents a conceptually simple yet general and effective framework for handling catastrophic forgetting in continual learning with DNNs. The proposed method consists of two components: a neural structure optimization component and a parameter learning and/or fine-tuning component. The former learns the best neural structure for the current task on top of the current DNN trained with previous tasks. It learns whether to reuse or adapt building blocks in the current DNN, or to create new ones if needed under the differentiable neural architecture search framework. The latter estimates parameters for newly introduced structures, and fine-tunes the old ones if preferred. By separating the explicit neural structure learning and the parameter estimation, not only is the proposed method capable of evolving neural structures in an intuitively meaningful way, but also shows strong capabilities of alleviating catastrophic forgetting in experiments. Furthermore, the proposed method outperforms all other baselines on the permuted MNIST dataset, the split CIFAR100 dataset and the Visual Domain Decathlon dataset in continual learning setting.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00310](http://arxiv.org/abs/1904.00310)

##### PDF
[http://arxiv.org/pdf/1904.00310](http://arxiv.org/pdf/1904.00310)

