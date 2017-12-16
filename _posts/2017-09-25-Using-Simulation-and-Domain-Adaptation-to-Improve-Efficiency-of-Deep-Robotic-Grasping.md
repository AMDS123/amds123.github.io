---
layout: post
title: "Using Simulation and Domain Adaptation to Improve Efficiency of Deep Robotic Grasping"
date: 2017-09-25 21:35:45
categories: arXiv_CV
tags: arXiv_CV GAN
author: Konstantinos Bousmalis, Alex Irpan, Paul Wohlhart, Yunfei Bai, Matthew Kelcey, Mrinal Kalakrishnan, Laura Downs, Julian Ibarz, Peter Pastor, Kurt Konolige, Sergey Levine, Vincent Vanhoucke
mathjax: true
---

* content
{:toc}

##### Abstract
Instrumenting and collecting annotated visual grasping datasets to train modern machine learning algorithms can be extremely time-consuming and expensive. An appealing alternative is to use off-the-shelf simulators to render synthetic data for which ground-truth annotations are generated automatically. Unfortunately, models trained purely on simulated data often fail to generalize to the real world. We study how randomized simulated environments and domain adaptation methods can be extended to train a grasping system to grasp novel objects from raw monocular RGB images. We extensively evaluate our approaches with a total of more than 25,000 physical test grasps, studying a range of simulation conditions and domain adaptation methods, including a novel extension of pixel-level domain adaptation that we term the GraspGAN. We show that, by using synthetic data and domain adaptation, we are able to reduce the number of real-world samples needed to achieve a given level of performance by up to 50 times, using only randomly generated simulated objects. We also show that by using only unlabeled real-world data and our GraspGAN methodology, we obtain real-world grasping performance without any real-world labels that is similar to that achieved with 939,777 labeled real-world samples.

##### Abstract (translated by Google)
检测和收集带注释的视觉抓取数据集以训练现代机器学习算法可能是非常耗时且昂贵的。一个有吸引力的替代方法是使用现成的模拟器来渲染合成数据，并自动生成地面真实注释。不幸的是，纯粹模拟数据训练的模型通常不能推广到现实世界。我们研究如何随机化的模拟环境和领域适应方法可以扩展到训练抓取系统从原始单眼RGB图像抓取新的对象。我们通过总共25,000多个物理测试手段，广泛评估了我们的方法，研究了一系列模拟条件和领域适应方法，包括我们称之为GraspGAN的像素级域适应的新型扩展。我们表明，通过使用合成数据和领域适应，我们能够减少真实世界的样本数量达到给定的性能水平达50倍，只使用随机生成的模拟对象。我们还表明，通过仅使用未标记的实际数据和我们的GraspGAN方法，我们获得了真实世界的抓取性能，没有任何真实世界的标签类似于用939,777个标签真实世界样本获得的标签。

##### URL
[https://arxiv.org/abs/1709.07857](https://arxiv.org/abs/1709.07857)

##### PDF
[https://arxiv.org/pdf/1709.07857](https://arxiv.org/pdf/1709.07857)

