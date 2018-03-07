---
layout: post
title: "Tactile Regrasp: Grasp Adjustments via Simulated Tactile Transformations"
date: 2018-03-05 21:43:16
categories: arXiv_RO
tags: arXiv_RO CNN
author: Francois R. Hogan, Maria Bauza, Oleguer Canal, Elliott Donlon, Alberto Rodriguez
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel regrasp control policy that makes use of tactile sensing to plan local grasp adjustments. Our approach determines regrasp actions by virtually searching for local transformations of tactile measurements that improve the quality of the grasp. First, we construct a tactile-based grasp quality metric using a deep convolutional neural network trained on over 2800 grasps. The quality of each grasp, a continuous value between 0 and 1, is determined experimentally by measuring its resistance to external perturbations. Second, we simulate the tactile imprints associated with robot motions relative to the initial grasp by performing rigid-body transformations of the given tactile measurements. The newly generated tactile imprints are evaluated with the learned grasp quality network and the regrasp action is chosen to maximize the grasp quality. 
 Results show that the grasp quality network can predict the outcome of grasps with an average accuracy of 85% on known objects and 75% on a cross validation set of 12 objects. The regrasp control policy improves the success rate of grasp actions by an average relative increase of 70% on a test set of 8 objects.

##### Abstract (translated by Google)
本文提出了一种新型的重新采用控制策略，利用触觉感知来计划局部调整。我们的方法通过虚拟搜索触觉测量的局部变换来确定捕捉行为，从而提高抓握质量。首先，我们使用深度卷积神经网络构建基于触觉的抓取质量度量，训练超过2800个抓握。每次抓取的质量，0和1之间的连续值，通过测量其对外部扰动的抵抗力来实验确定。其次，通过执行给定触觉测量的刚体变换，我们模拟与机器人运动相关的触觉印记相对于初始抓取。使用学习到的抓握质量网络来评估新生成的触觉印记，并且选择重拍动作来最大化抓握质量。
 结果表明，抓取质量网络可以预测抓取的结果，对已知对象的平均准确率为85％，对12个对象的交叉验证集合的平均准确率为75％。 regrasp控制策略在8个对象的测试集上平均相对增加70％，提高了抓取动作的成功率。

##### URL
[http://arxiv.org/abs/1803.01940](http://arxiv.org/abs/1803.01940)

##### PDF
[http://arxiv.org/pdf/1803.01940](http://arxiv.org/pdf/1803.01940)

