---
layout: post
title: "Visual Global Localization with a Hybrid WNN-CNN Approach"
date: 2018-05-08 17:34:31
categories: arXiv_RO
tags: arXiv_RO CNN Classification SLAM Recognition
author: Avelino Forechi, Thiago Oliveira-Santos, Claudine Badue, Alberto F. De Souza
mathjax: true
---

* content
{:toc}

##### Abstract
Currently, self-driving cars rely greatly on the Global Positioning System (GPS) infrastructure, albeit there is an increasing demand for alternative methods for GPS-denied environments. One of them is known as place recognition, which associates images of places with their corresponding positions. We previously proposed systems based on Weightless Neural Networks (WNN) to address this problem as a classification task. This encompasses solely one part of the global localization, which is not precise enough for driverless cars. Instead of just recognizing past places and outputting their poses, it is desired that a global localization system estimates the pose of current place images. In this paper, we propose to tackle this problem as follows. Firstly, given a live image, the place recognition system returns the most similar image and its pose. Then, given live and recollected images, a visual localization system outputs the relative camera pose represented by those images. To estimate the relative camera pose between the recollected and the current images, a Convolutional Neural Network (CNN) is trained with the two images as input and a relative pose vector as output. Together, these systems solve the global localization problem using the topological and metric information to approximate the current vehicle pose. The full approach is compared to a Real- Time Kinematic GPS system and a Simultaneous Localization and Mapping (SLAM) system. Experimental results show that the proposed approach correctly localizes a vehicle 90% of the time with a mean error of 1.20m compared to 1.12m of the SLAM system and 0.37m of the GPS, 89% of the time.

##### Abstract (translated by Google)
目前，自动驾驶汽车极大地依赖于全球定位系统（GPS）基础设施，尽管对GPS拒绝环境的替代方法的需求日益增加。其中之一被称为地点识别，它将地点的图像与其相应的位置相关联。我们以前提出了基于无重量神经网络（WNN）的系统来解决这个问题作为分类任务。这仅包含全球本地化的一部分，对于无人驾驶汽车来说这不够精确。我们希望全球定位系统能够估计当前位置图像的姿态，而不是仅仅识别过去的位置并输出姿态。在本文中，我们建议如下解决这个问题。首先，给定一个实时图像，场所识别系统返回最相似的图像及其姿势。然后，给定生动的和重新收集的图像，视觉定位系统输出由这些图像表示的相对姿势。为了估计再现的和当前图像之间的相对姿态，卷积神经网络（CNN）被训练为两个图像作为输入并且相对姿态向量作为输出。这些系统一起使用拓扑和度量信息来近似当前车辆姿态来解决全局定位问题。完整的方法与实时动态GPS系统和同时定位和映射（SLAM）系统相比较。实验结果表明，所提出的方法90％的时间正确定位车辆的平均误差为1.20米，而SLAM系统为1.12米，89％的时间为0.37米。

##### URL
[http://arxiv.org/abs/1805.03183](http://arxiv.org/abs/1805.03183)

##### PDF
[http://arxiv.org/pdf/1805.03183](http://arxiv.org/pdf/1805.03183)

