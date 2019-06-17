---
layout: post
title: "Learning to Forget for Meta-Learning"
date: 2019-06-13 19:03:27
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Sungyong Baik, Seokil Hong, Kyoung Mu Lee
mathjax: true
---

* content
{:toc}

##### Abstract
Few-shot learning is a challenging problem where the system is required to achieve generalization from only few examples. Meta-learning tackles the problem by learning prior knowledge shared across a distribution of tasks, which is then used to quickly adapt to unseen tasks. Model-agnostic meta-learning (MAML) algorithm formulates prior knowledge as a common initialization across tasks. However, forcibly sharing an initialization brings about conflicts between tasks and thus compromises the quality of the initialization. In this work, by observing that the extent of compromise differs among tasks and between layers of a neural network, we propose a new initialization idea that employs task-dependent layer-wise attenuation, which we call selective forgetting. The proposed attenuation scheme dynamically controls how much of prior knowledge each layer will exploit for a given task. The experimental results demonstrate that the proposed method mitigates the conflicts and provides outstanding performance as a result. We further show that the proposed method, named L2F, can be applied and improve other state-of-the-art MAML-based frameworks, illustrating its generalizability.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05895](https://arxiv.org/abs/1906.05895)

##### PDF
[https://arxiv.org/pdf/1906.05895](https://arxiv.org/pdf/1906.05895)

