---
layout: post
title: "Learning Discriminative Video Representations Using Adversarial Perturbations"
date: 2018-07-24 22:46:42
categories: arXiv_CV
tags: arXiv_CV Adversarial Optimization Classification Recognition
author: Jue Wang, Anoop Cherian
mathjax: true
---

* content
{:toc}

##### Abstract
Adversarial perturbations are noise-like patterns that can subtly change the data, while failing an otherwise accurate classifier. In this paper, we propose to use such perturbations for improving the robustness of video representations. To this end, given a well-trained deep model for per-frame video recognition, we first generate adversarial noise adapted to this model. Using the original data features from the full video sequence and their perturbed counterparts, as two separate bags, we develop a binary classification problem that learns a set of discriminative hyperplanes -- as a subspace -- that will separate the two bags from each other. This subspace is then used as a descriptor for the video, dubbed discriminative subspace pooling. As the perturbed features belong to data classes that are likely to be confused with the original features, the discriminative subspace will characterize parts of the feature space that are more representative of the original data, and thus may provide robust video representations. To learn such descriptors, we formulate a subspace learning objective on the Stiefel manifold and resort to Riemannian optimization methods for solving it efficiently. We provide experiments on several video datasets and demonstrate state-of-the-art results.

##### Abstract (translated by Google)
对抗性扰动是类似噪声的模式，可以巧妙地改变数据，而失败的是其他准确的分类器。在本文中，我们建议使用这种扰动来提高视频表示的稳健性。为此，给定一个训练有素的每帧视频识别深度模型，我们首先产生适合该模型的对抗性噪声。使用来自完整视频序列的原始数据特征及其扰动的对应物，作为两个单独的包，我们开发了一个二元分类问题，它学习了一组有辨别力的超平面 - 作为子空间 - 将两个袋子彼此分开。然后将该子空间用作视频的描述符，称为判别子空间池。由于扰动特征属于可能与原始特征混淆的数据类，因此辨别子空间将表征特征空间的更能代表原始数据的部分，因此可提供稳健的视频表示。为了学习这样的描述符，我们在Stiefel流形上形成子空间学习目标，并采用黎曼优化方法来有效地求解它。我们提供了几个视频数据集的实验，并展示了最先进的结果。

##### URL
[http://arxiv.org/abs/1807.09380](http://arxiv.org/abs/1807.09380)

##### PDF
[http://arxiv.org/pdf/1807.09380](http://arxiv.org/pdf/1807.09380)

