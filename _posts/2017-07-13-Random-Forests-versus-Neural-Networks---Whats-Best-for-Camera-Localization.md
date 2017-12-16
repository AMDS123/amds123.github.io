---
layout: post
title: "Random Forests versus Neural Networks - What's Best for Camera Localization?"
date: 2017-07-13 08:52:13
categories: arXiv_CV
tags: arXiv_CV
author: Daniela Massiceti, Alexander Krull, Eric Brachmann, Carsten Rother, Philip H.S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
This work addresses the task of camera localization in a known 3D scene given a single input RGB image. State-of-the-art approaches accomplish this in two steps: firstly, regressing for every pixel in the image its 3D scene coordinate and subsequently, using these coordinates to estimate the final 6D camera pose via RANSAC. To solve the first step, Random Forests (RFs) are typically used. On the other hand, Neural Networks (NNs) reign in many dense regression tasks, but are not test-time efficient. We ask the question: which of the two is best for camera localization? To address this, we make two method contributions: (1) a test-time efficient NN architecture which we term a ForestNet that is derived and initialized from a RF, and (2) a new fully-differentiable robust averaging technique for regression ensembles which can be trained end-to-end with a NN. Our experimental findings show that for scene coordinate regression, traditional NN architectures are superior to test-time efficient RFs and ForestNets, however, this does not translate to final 6D camera pose accuracy where RFs and ForestNets perform slightly better. To summarize, our best method, a ForestNet with a robust average, which has an equivalent fast and lightweight RF, improves over the state-of-the-art for camera localization on the 7-Scenes dataset. While this work focuses on scene coordinate regression for camera localization, our innovations may also be applied to other continuous regression tasks.

##### Abstract (translated by Google)
这项工作解决了在给定单个输入RGB图像的已知3D场景中相机定位的任务。最先进的方法分两步完成：首先，对图像中的每个像素进行3D场景坐标回归，然后使用这些坐标通过RANSAC估计最终的6D相机姿态。为了解决第一步，通常使用随机森林（RFs）。另一方面，神经网络（NN）在许多密集的回归任务中统治，但是不是测试时间有效的。我们问这个问题：哪两个最适合相机本地化？为了解决这个问题，我们做了两个方法贡献：（1）一个测试时间高效的NN架构，我们称之为一个从RF导出和初始化的ForestNet，以及（2）用于回归合奏的新的完全可微的鲁棒平均技术，可以用神经网络进行端对端的训练。我们的实验结果表明，对于场景坐标回归，传统的NN架构优于测试时间的高效射频和ForestNets，但是，这并不能转化为RFs和ForestNets略胜一筹的最终6D相机姿态精度。总而言之，我们最好的方法，具有稳健平均值的ForestNet具有等效的快速和轻量级RF，改善了7-Scenes数据集上相机定位的最新技术水平。虽然这项工作专注于相机定位的场景坐标回归，但是我们的创新也可以应用于其他的连续回归任务。

##### URL
[https://arxiv.org/abs/1609.05797](https://arxiv.org/abs/1609.05797)

##### PDF
[https://arxiv.org/pdf/1609.05797](https://arxiv.org/pdf/1609.05797)

