---
layout: post
title: "HP-GAN: Probabilistic 3D human motion prediction via GAN"
date: 2017-11-27 07:07:11
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Prediction
author: Emad Barsoum, John Kender, Zicheng Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Predicting and understanding human motion dynamics has many applications, such as motion synthesis, augmented reality, security, and autonomous vehicles. Due to the recent success of generative adversarial networks (GAN), there has been much interest in probabilistic estimation and synthetic data generation using deep neural network architectures and learning algorithms. We propose a novel sequence-to-sequence model for probabilistic human motion prediction, trained with a modified version of improved Wasserstein generative adversarial networks (WGAN-GP), in which we use a custom loss function designed for human motion prediction. Our model, which we call HP-GAN, learns a probability density function of future human poses conditioned on previous poses. It predicts multiple sequences of possible future human poses, each from the same input sequence but a different vector z drawn from a random distribution. Furthermore, to quantify the quality of the non-deterministic predictions, we simultaneously train a motion-quality-assessment model that learns the probability that a given skeleton sequence is a real human motion. We test our algorithm on two of the largest skeleton datasets: NTURGB-D and Human3.6M. We train our model on both single and multiple action types. Its predictive power for long-term motion estimation is demonstrated by generating multiple plausible futures of more than 30 frames from just 10 frames of input. We show that most sequences generated from the same input have more than 50\% probabilities of being judged as a real human sequence. We will release all the code used in this paper to Github.

##### Abstract (translated by Google)
预测和理解人体运动动力学有许多应用，如运动合成，增强现实，安全和自主车辆。由于最近的生成对抗网络（GAN）的成功，人们对使用深度神经网络结构和学习算法的概率估计和合成数据生成有很大兴趣。我们提出了一种新的用于概率人体运动预测的序列 - 序列模型，用改进的改进的Wasserstein生成对抗网络（WGAN-GP）进行训练，其中我们使用为人体运动预测设计的自定义损失函数。我们称之为HP-GAN的模型，学习了一个以前姿态为条件的未来人体姿态的概率密度函数。它预测未来可能的人体姿势的多个序列，每个序列来自相同的输入序列，但是从随机分布中绘制不同的向量z。此外，为了量化非确定性预测的质量，我们同时训练运动质量评估模型，其学习给定骨架序列是真实人体运动的概率。我们在两个最大的骨架数据集上测试我们的算法：NTURGB-D和Human3.6M。我们在单一和多个动作类型上训练我们的模型。其对长期运动估计的预测能力通过从10帧输入产生30多个帧的多个可能的未来来证明。我们表明，从相同的输入生成的大部分序列具有超过50％的被判断为真实人序列的概率。我们将把本文中使用的所有代码发布到Github。

##### URL
[https://arxiv.org/abs/1711.09561](https://arxiv.org/abs/1711.09561)

##### PDF
[https://arxiv.org/pdf/1711.09561](https://arxiv.org/pdf/1711.09561)

