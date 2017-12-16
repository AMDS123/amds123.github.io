---
layout: post
title: "Egocentric Height Estimation"
date: 2016-10-09 20:08:17
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Object_Tracking Classification Deep_Learning Recognition
author: Jessica Finocchiaro, Aisha Urooj Khan, Ali Borji
mathjax: true
---

* content
{:toc}

##### Abstract
Egocentric, or first-person vision which became popular in recent years with an emerge in wearable technology, is different than exocentric (third-person) vision in some distinguishable ways, one of which being that the camera wearer is generally not visible in the video frames. Recent work has been done on action and object recognition in egocentric videos, as well as work on biometric extraction from first-person videos. Height estimation can be a useful feature for both soft-biometrics and object tracking. Here, we propose a method of estimating the height of an egocentric camera without any calibration or reference points. We used both traditional computer vision approaches and deep learning in order to determine the visual cues that results in best height estimation. Here, we introduce a framework inspired by two stream networks comprising of two Convolutional Neural Networks, one based on spatial information, and one based on information given by optical flow in a frame. Given an egocentric video as an input to the framework, our model yields a height estimate as an output. We also incorporate late fusion to learn a combination of temporal and spatial cues. Comparing our model with other methods we used as baselines, we achieve height estimates for videos with a Mean Average Error of 14.04 cm over a range of 103 cm of data, and classification accuracy for relative height (tall, medium or short) up to 93.75% where chance level is 33%.

##### Abstract (translated by Google)
近年来随着可穿戴技术的兴起而流行起来的以自我为中心的第一人称视角与以某些可区别的方式的外在（第三人称）视觉不同，其中之一是相机佩戴者通常在视频中不可见帧。最近在以自我为中心的视频中的行为和对象识别方面做了工作，以及从第一人称视频中提取生物特征的工作。高度估计对于软生物特征识别和对象跟踪都是有用的特征。在这里，我们提出一种估计没有任何校准或参考点的自我中心相机的高度的方法。我们使用传统的计算机视觉方法和深度学习来确定导致最佳高度估计的视觉线索。在这里，我们引入一个由两个流网络组成的框架，这两个流网络由两个卷积神经网络组成，一个基于空间信息，一个基于一个帧中的光流给出的信息。给定一个以自我为中心的视频作为框架的输入，我们的模型产生一个高度估计作为输出。我们还融入了后期融合，以学习时间和空间线索的组合。将我们的模型与其他方法作为基线进行比较，我们对103厘米数据范围内的平均误差为14.04厘米的视频进行高度估计，并将相对高度（高，中或短）的分类准确度提高到93.75机会水平是33％的％。

##### URL
[https://arxiv.org/abs/1610.02714](https://arxiv.org/abs/1610.02714)

##### PDF
[https://arxiv.org/pdf/1610.02714](https://arxiv.org/pdf/1610.02714)

