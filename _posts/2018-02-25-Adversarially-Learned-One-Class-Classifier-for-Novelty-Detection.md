---
layout: post
title: "Adversarially Learned One-Class Classifier for Novelty Detection"
date: 2018-02-25 21:34:27
categories: arXiv_CV
tags: arXiv_CV Adversarial Object_Detection GAN Classification Detection
author: Mohammad Sabokrou, Mohammad Khalooei, Mahmood Fathy, Ehsan Adeli
mathjax: true
---

* content
{:toc}

##### Abstract
Novelty detection is the process of identifying the observation(s) that differ in some respect from the training observations (the target class). In reality, the novelty class is often absent during training, poorly sampled or not well defined. Therefore, one-class classifiers can efficiently model such problems. However, due to the unavailability of data from the novelty class, training an end-to-end deep network is a cumbersome task. In this paper, inspired by the success of generative adversarial networks for training deep models in unsupervised and semi-supervised settings, we propose an end-to-end architecture for one-class classification. Our architecture is composed of two deep networks, each of which trained by competing with each other while collaborating to understand the underlying concept in the target class, and then classify the testing samples. One network works as the novelty detector, while the other supports it by enhancing the inlier samples and distorting the outliers. The intuition is that the separability of the enhanced inliers and distorted outliers is much better than deciding on the original samples. The proposed framework applies to different related applications of anomaly and outlier detection in images and videos. The results on MNIST and Caltech-256 image datasets, along with the challenging UCSD Ped2 dataset for video anomaly detection illustrate that our proposed method learns the target class effectively and is superior to the baseline and state-of-the-art methods.

##### Abstract (translated by Google)
新颖性检测是识别在某些方面与训练观察（目标类别）不同的观察的过程。实际上，新课程在训练期间通常是缺席的，取样不好或没有明确定义。因此，一类分类器可以有效地对这些问题进行建模。但是，由于新颖类的数据不可用，因此培训一个端到端的深度网络是一项繁琐的任务。在本文中，受到在无监督和半监督环境下训练深度模型的生成对抗网络的成功启发，我们提出了一种用于一类分类的端到端体系结构。我们的架构由两个深度网络组成，每个网络通过彼此竞争而进行训练，同时协作理解目标类中的基本概念，然后对测试样本进行分类。一个网络用作新颖性检测器，另一个网络通过增强inlier样本和扭曲异常值来支持它。直觉是增强的离群点和畸变离群点的可分离性要比决定原始样本好得多。所提出的框架适用于图像和视频中的异常和异常值检测的不同相关应用。 MNIST和Caltech-256图像数据集上的结果以及具有挑战性的UCSD Ped2数据集用于视频异常检测，说明我们提出的方法有效地学习目标类别，并且优于基线和最先进的方法。

##### URL
[http://arxiv.org/abs/1802.09088](http://arxiv.org/abs/1802.09088)

##### PDF
[http://arxiv.org/pdf/1802.09088](http://arxiv.org/pdf/1802.09088)

