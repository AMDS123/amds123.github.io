---
layout: post
title: "Active Learning for Visual Question Answering: An Empirical Study"
date: 2017-11-06 05:28:38
categories: arXiv_CV
tags: arXiv_CV QA VQA
author: Xiao Lin, Devi Parikh
mathjax: true
---

* content
{:toc}

##### Abstract
We present an empirical study of active learning for Visual Question Answering, where a deep VQA model selects informative question-image pairs from a pool and queries an oracle for answers to maximally improve its performance under a limited query budget. Drawing analogies from human learning, we explore cramming (entropy), curiosity-driven (expected model change), and goal-driven (expected error reduction) active learning approaches, and propose a fast and effective goal-driven active learning scoring function to pick question-image pairs for deep VQA models under the Bayesian Neural Network framework. We find that deep VQA models need large amounts of training data before they can start asking informative questions. But once they do, all three approaches outperform the random selection baseline and achieve significant query savings. For the scenario where the model is allowed to ask generic questions about images but is evaluated only on specific questions (e.g., questions whose answer is either yes or no), our proposed goal-driven scoring function performs the best.

##### Abstract (translated by Google)
我们提出了一个关于视觉问答的主动学习的实证研究，其中深度VQA模型从池中选择信息性问题 - 图像对，并向oracle查询答案，以便在有限的查询预算下最大限度地提高其性能。从人类学习中得出类比，我们探索填塞（熵），好奇心驱动（预期模型变化）和目标驱动（预期错误减少）主动学习方法，并提出快速有效的目标驱动主动学习评分功能来挑选贝叶斯神经网络框架下深VQA模型的问题 - 图像对。我们发现深层VQA模型需要大量的培训数据才能开始提出信息性问题。但是一旦他们这样做，这三种方法都优于随机选择基线并实现显着的查询节省。对于允许模型询问关于图像的一般问题但仅针对特定问题（例如，答案为是或否的问题）进行评估的情况，我们提出的目标驱动评分函数表现最佳。

##### URL
[https://arxiv.org/abs/1711.01732](https://arxiv.org/abs/1711.01732)

##### PDF
[https://arxiv.org/pdf/1711.01732](https://arxiv.org/pdf/1711.01732)

