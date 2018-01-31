---
layout: post
title: "Riemannian Walk for Incremental Learning: Understanding Forgetting and Intransigence"
date: 2018-01-30 17:47:35
categories: arXiv_CV
tags: arXiv_CV Regularization Knowledge Classification
author: Arslan Chaudhry, Puneet K. Dokania, Thalaiyasingam Ajanthan, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
We study the incremental learning problem for the classification task, a key component in developing life-long learning systems. The main challenges while learning in an incremental manner are to preserve and update the knowledge of the model. In this work, we propose a generalization of Path Integral (Zenke et al., 2017) and EWC (Kirkpatrick et al., 2016} with a theoretically grounded KL-divergence based perspective. We show that, to preserve and update the knowledge, regularizing the model's likelihood distribution is more intuitive and provides better insights to the problem. To do so, we use KL-divergence as a measure of distance which is equivalent to computing distance in a Riemannian manifold induced by the Fisher information matrix. Furthermore, to enhance the learning flexibility, the regularization is weighted by a parameter importance score that is calculated along the entire training trajectory. Contrary to forgetting, as the algorithm progresses, the regularized loss makes the network intransigent, resulting in its inability to discriminate new tasks from the old ones. We show that this problem of intransigence can be addressed by storing a small subset of representative samples from previous datasets. In addition, in order to evaluate the performance of an incremental learning algorithm, we introduce two novel metrics to evaluate forgetting and intransigence. Experimental evaluation on incremental version of MNIST and CIFAR-100 classification datasets shows that our approach outperforms existing state-of-the-art baselines in all the evaluation metrics.

##### Abstract (translated by Google)
我们研究分类任务的增量学习问题，这是开发终身学习系统的关键组件。增量学习的主要挑战是保持和更新模型的知识。在这项工作中，我们提出了一个路径积分（Zenke et al。，2017）和EWC（Kirkpatrick et al。，2016）的概括，并且以理论为基础的基于KL-发散的观点来展示，为了保存和更新知识，规则化模型的似然分布更为直观，对问题提供了更好的见解，为此，我们用KL散度作为距离的度量，这相当于费米信息矩阵引起的黎曼流形中的计算距离，增强了学习的灵活性，正则化是通过在整个训练轨迹上计算的参数重要性分数来加权的，与遗忘相反，随着算法的进行，正则化的损失使得网络不妥协，导致它无法区分新的任务和我们表明这个不妥协的问题可以通过存储以前数据集的代表性样本的一小部分来解决。为了评估增量学习算法的性能，我们引入了两个新的度量来评估遗忘和不妥协。对MNIST和CIFAR-100分类数据集的增量版本进行的实验评估表明，我们的方法在所有评估指标中均优于现有的最新基线。

##### URL
[http://arxiv.org/abs/1801.10112](http://arxiv.org/abs/1801.10112)

##### PDF
[http://arxiv.org/pdf/1801.10112](http://arxiv.org/pdf/1801.10112)

