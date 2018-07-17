---
layout: post
title: "Real-Time Shape Tracking of Facial Landmarks"
date: 2018-07-14 04:57:16
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Tracking Semantic_Segmentation Deep_Learning Detection
author: Hyungjoon Kim, Hyeonwoo Kim, Eenjun Hwang
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of facial landmarks and accurate tracking of their shape are essential in real-time virtual makeup applications, where users can see the makeups effect by moving their face in different directions. Typical face tracking techniques detect diverse facial landmarks and track them using a point tracker such as the Kanade-Lucas-Tomasi (KLT) point tracker. Typically, 5 or 64 points are used for tracking a face. Even though these points are sufficient to track the approximate locations of facial landmarks, they are not sufficient to track the exact shape of facial landmarks. In this paper, we propose a method that can track the exact shape of facial landmarks in real-time by combining a deep learning technique and a point tracker. We detect facial landmarks accurately using SegNet, which performs semantic segmentation based on deep learning. Edge points of detected landmarks are tracked using the KLT point tracker. In spite of its popularity, the KLT point tracker suffers from the point loss problem. We solve this problem by executing SegNet periodically to calculate the shape of facial landmarks. That is, by combining the two techniques, we can avoid the computational overhead of SegNet for real-time shape tracking and the point loss problem of the KLT point tracker. We performed several experiments to evaluate the performance of our method and report some of the results herein.

##### Abstract (translated by Google)
面部标志的检测和其形状的精确跟踪在实时虚拟化妆应用中是必不可少的，其中用户可以通过在不同方向上移动他们的面部来看到化妆效果。典型的面部跟踪技术使用点跟踪器（例如Kanade-Lucas-Tomasi（KLT）点跟踪器）检测不同的面部标志并跟踪它们。通常，5或64个点用于跟踪面部。尽管这些点足以跟踪面部标志的大致位置，但它们不足以跟踪面部标志的确切形状。在本文中，我们提出了一种方法，通过结合深度学习技术和点跟踪器，可以实时跟踪面部标志的确切形状。我们使用SegNet准确地检测面部地标，SegNet基于深度学习执行语义分割。使用KLT点跟踪器跟踪检测到的界标的边缘点。尽管它受欢迎，KLT点跟踪器仍然存在点丢失问题。我们通过定期执行SegNet来计算面部标志的形状来解决这个问题。也就是说，通过组合这两种技术，我们可以避免SegNet的实时形状跟踪计算开销和KLT点跟踪器的点丢失问题。我们进行了几次实验来评估我们方法的性能并报告了一些结果。

##### URL
[http://arxiv.org/abs/1807.05333](http://arxiv.org/abs/1807.05333)

##### PDF
[http://arxiv.org/pdf/1807.05333](http://arxiv.org/pdf/1807.05333)

