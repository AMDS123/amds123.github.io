---
layout: post
title: "Hyperparameter Transfer Learning through Surrogate Alignment for Efficient Deep Neural Network Training"
date: 2016-07-31 14:09:17
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Optimization
author: Ilija Ilievski, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, several optimization methods have been successfully applied to the hyperparameter optimization of deep neural networks (DNNs). The methods work by modeling the joint distribution of hyperparameter values and corresponding error. Those methods become less practical when applied to modern DNNs whose training may take a few days and thus one cannot collect sufficient observations to accurately model the distribution. To address this challenging issue, we propose a method that learns to transfer optimal hyperparameter values for a small source dataset to hyperparameter values with comparable performance on a dataset of interest. As opposed to existing transfer learning methods, our proposed method does not use hand-designed features. Instead, it uses surrogates to model the hyperparameter-error distributions of the two datasets and trains a neural network to learn the transfer function. Extensive experiments on three CV benchmark datasets clearly demonstrate the efficiency of our method.

##### Abstract (translated by Google)
最近，几种优化方法已经成功应用于深度神经网络（DNN）的超参数优化。这些方法通过建模超参数值和相应误差的联合分布来工作。当将这些方法应用于现代的DNN时，这些方法可能会花费几天的时间，因此无法收集足够的观测资料来精确分配分布。为了解决这个具有挑战性的问题，我们提出了一种方法，学习将小的源数据集的最优超参数值转换为具有相同性能的超参数值。与现有的转移学习方法相反，我们提出的方法不使用手工设计的特征。相反，它使用代理来模拟两个数据集的超参数误差分布，并训练一个神经网络来学习传递函数。在三个CV基准数据集上的大量实验清楚地证明了我们的方法的效率。

##### URL
[https://arxiv.org/abs/1608.00218](https://arxiv.org/abs/1608.00218)

##### PDF
[https://arxiv.org/pdf/1608.00218](https://arxiv.org/pdf/1608.00218)

