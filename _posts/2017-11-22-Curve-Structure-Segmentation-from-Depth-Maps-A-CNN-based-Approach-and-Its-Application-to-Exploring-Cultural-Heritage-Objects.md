---
layout: post
title: "Curve-Structure Segmentation from Depth Maps: A CNN-based Approach and Its Application to Exploring Cultural Heritage Objects"
date: 2017-11-22 05:51:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Prediction
author: Yuhang Lu, Jun Zhou, Jing Wang, Jun Chen, Karen Smith, Colin Wilder, Song Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Motivated by the important archaeological application of exploring cultural heritage objects, in this paper we study the challenging problem of automatically segmenting curve structures that are very weakly stamped or carved on an object surface in the form of a highly noisy depth map. Different from most classical low-level image segmentation methods that are known to be very sensitive to the noise and occlusions, we propose a new supervised learning algorithm based on Convolutional Neural Network (CNN) to implicitly learn and utilize more curve geometry and pattern information for addressing this challenging problem. More specifically, we first propose a Fully Convolutional Network (FCN) to estimate the skeleton of curve structures and at each skeleton pixel, a scale value is estimated to reflect the local curve width. Then we propose a dense prediction network to refine the estimated curve skeletons. Based on the estimated scale values, we finally develop an adaptive thresholding algorithm to achieve the final segmentation of curve structures. In the experiment, we validate the performance of the proposed method on a dataset of depth images scanned from unearthed pottery sherds dating to the Woodland period of Southeastern North America.

##### Abstract (translated by Google)
受探索文化遗产的重要考古学应用的启发，本文研究了以高噪声深度图形式自动分割曲面结构的挑战性问题，这些曲线结构以非常弱的方式刻印或刻在物体表面上。与已知的对噪声和遮挡非常敏感的大多数经典的低级图像分割方法不同，我们提出了一种基于卷积神经网络（CNN）的监督学习算法，以隐式学习和利用更多的曲线几何和模式信息解决这个具有挑战性更具体地说，我们首先提出一个完全卷积网络（FCN）来估计曲线结构的骨架，并且在每个骨架像素处，估计一个比例值以反映局部曲线宽度。然后我们提出一个密集的预测网络来改进估计的曲线骨架。基于估计的尺度值，我们最终开发了一种自适应阈值算法来实现曲线结构的最终分割。在实验中，我们验证了所建议的方法在从东北美洲东南部林地时期出土的陶片上扫描的深度图像数据集上的性能。

##### URL
[https://arxiv.org/abs/1711.02718](https://arxiv.org/abs/1711.02718)

##### PDF
[https://arxiv.org/pdf/1711.02718](https://arxiv.org/pdf/1711.02718)

