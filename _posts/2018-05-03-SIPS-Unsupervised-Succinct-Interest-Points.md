---
layout: post
title: "SIPS: Unsupervised Succinct Interest Points"
date: 2018-05-03 15:11:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation Detection SLAM
author: Titus Cieslewski, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting interest points is a key component of vision-based estimation algorithms, such as visual odometry or visual SLAM. Classically, interest point detection has been done with methods such as Harris, FAST, or DoG. Recently, better detectors have been proposed based on Neural Networks. Traditionally, interest point detectors have been designed to maximize repeatability or matching score. Instead, we pursue another metric, which we call succinctness. This metric captures the minimum amount of interest points that need to be extracted in order to achieve accurate relative pose estimation. Extracting a minimum amount of interest points is attractive for many applications, because it reduces computational load, memory, and, potentially, data transmission. We propose a novel reinforcement- and ranking-based training framework, which uses a full relative pose estimation pipeline during training. It can be trained in an unsupervised manner, without pose or 3D point ground truth. Using this training framework, we present a detector which outperforms previous interest point detectors in terms of succinctness on a variety of publicly available datasets.

##### Abstract (translated by Google)
检测兴趣点是基于视觉的估计算法（如视觉测距或视觉SLAM）的关键组件。传统上，利用Harris，FAST或DoG等方法完成兴趣点检测。最近，基于神经网络提出了更好的检测器。传统上，兴趣点检测器的设计旨在最大化重复性或匹配分数。相反，我们追求另一个度量标准，我们称之为简洁性。该度量捕获需要提取的最小兴趣点数量，以实现精确的相对姿态估计。提取最小数量的兴趣点对许多应用程序都很有吸引力，因为它可以减少计算负载，内存以及潜在的数据传输。我们提出了一种新型的基于强化和排序的训练框架，它在训练期间使用完整的相对姿势估计流水线。它可以以无监督的方式进行训练，没有姿势或3D点基础事实。使用这个训练框架，我们提出了一个检测器，它在各种公开可用数据集上的简洁性方面优于先前的兴趣点检测器。

##### URL
[http://arxiv.org/abs/1805.01358](http://arxiv.org/abs/1805.01358)

##### PDF
[http://arxiv.org/pdf/1805.01358](http://arxiv.org/pdf/1805.01358)

