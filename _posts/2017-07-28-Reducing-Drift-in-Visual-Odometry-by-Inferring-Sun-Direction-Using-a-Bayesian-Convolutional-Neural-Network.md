---
layout: post
title: "Reducing Drift in Visual Odometry by Inferring Sun Direction Using a Bayesian Convolutional Neural Network"
date: 2017-07-28 02:45:42
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Detection
author: Valentin Peretroukhin, Lee Clement, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to incorporate global orientation information from the sun into a visual odometry pipeline using only the existing image stream, where the sun is typically not visible. We leverage recent advances in Bayesian Convolutional Neural Networks to train and implement a sun detection model that infers a three-dimensional sun direction vector from a single RGB image. Crucially, our method also computes a principled uncertainty associated with each prediction, using a Monte Carlo dropout scheme. We incorporate this uncertainty into a sliding window stereo visual odometry pipeline where accurate uncertainty estimates are critical for optimal data fusion. Our Bayesian sun detection model achieves a median error of approximately 12 degrees on the KITTI odometry benchmark training set, and yields improvements of up to 42% in translational ARMSE and 32% in rotational ARMSE compared to standard VO. An open source implementation of our Bayesian CNN sun estimator (Sun-BCNN) using Caffe is available at this https URL com/utiasSTARS/sun-bcnn-vo

##### Abstract (translated by Google)
我们提出了一种方法，将太阳全局方向信息合并到仅使用现有图像流的视觉测距管线中，而太阳通常不可见。我们利用贝叶斯卷积神经网络的最新进展来训练和实施一个太阳探测模型，该模型从单个RGB图像推断出三维太阳方向矢量。至关重要的是，我们的方法还使用蒙特卡罗（Monte Carlo）退出方案计算与每个预测相关的原理不确定性。我们将这种不确定性纳入一个滑动窗口立体视觉测距管道，其中准确的不确定性估计对于最佳数据融合至关重要我们的Bayesian太阳探测模型在KITTI odometry基准训练集中达到了约12度的中值误差，平移ARMSE和旋转ARMSE相比标准VO提高了42％。我们使用Caffe的贝叶斯CNN太阳估计器（Sun-BCNN）的开源实现可以在这个https URL获得/ utiasSTARS / sun-bcnn-vo

##### URL
[https://arxiv.org/abs/1609.05993](https://arxiv.org/abs/1609.05993)

##### PDF
[https://arxiv.org/pdf/1609.05993](https://arxiv.org/pdf/1609.05993)

