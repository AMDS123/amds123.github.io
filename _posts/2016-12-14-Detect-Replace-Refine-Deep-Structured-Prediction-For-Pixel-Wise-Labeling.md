---
layout: post
title: "Detect, Replace, Refine: Deep Structured Prediction For Pixel Wise Labeling"
date: 2016-12-14 18:54:33
categories: arXiv_CV
tags: arXiv_CV Prediction Quantitative Detection
author: Spyros Gidaris, Nikos Komodakis
mathjax: true
---

* content
{:toc}

##### Abstract
Pixel wise image labeling is an interesting and challenging problem with great significance in the computer vision community. In order for a dense labeling algorithm to be able to achieve accurate and precise results, it has to consider the dependencies that exist in the joint space of both the input and the output variables. An implicit approach for modeling those dependencies is by training a deep neural network that, given as input an initial estimate of the output labels and the input image, it will be able to predict a new refined estimate for the labels. In this context, our work is concerned with what is the optimal architecture for performing the label improvement task. We argue that the prior approaches of either directly predicting new label estimates or predicting residual corrections w.r.t. the initial labels with feed-forward deep network architectures are sub-optimal. Instead, we propose a generic architecture that decomposes the label improvement task to three steps: 1) detecting the initial label estimates that are incorrect, 2) replacing the incorrect labels with new ones, and finally 3) refining the renewed labels by predicting residual corrections w.r.t. them. Furthermore, we explore and compare various other alternative architectures that consist of the aforementioned Detection, Replace, and Refine components. We extensively evaluate the examined architectures in the challenging task of dense disparity estimation (stereo matching) and we report both quantitative and qualitative results on three different datasets. Finally, our dense disparity estimation network that implements the proposed generic architecture, achieves state-of-the-art results in the KITTI 2015 test surpassing prior approaches by a significant margin.

##### Abstract (translated by Google)
像素明智的图像标记是计算机视觉领域中具有重要意义的一个有趣和具有挑战性的问题。为了使稠密标记算法能够获得准确和精确的结果，必须考虑输入变量和输出变量的联合空间中存在的依赖关系。对这些依赖关系进行建模的隐式方法是训练一个深度神经网络，将输入标签和输入图像的初始估计作为输入，可以预测标签的一个新的精确估计。在这方面，我们的工作是关于什么是执行标签改进任务的最佳架构。我们认为，直接预测新标签估计或预测剩余校正的先前方法w.r.t.具有前馈深网络架构的初始标签是次优的。相反，我们提出了一个通用的架构，将标签改进任务分解为三个步骤：1）检测不正确的初始标签估计，2）用新标签替换不正确的标签，最后3）通过预测残差校正WRT他们。此外，我们还探索并比较了由上述Detection，Replace和Refine组件组成的各种其他架构。我们在密集视差估计（立体匹配）这个具有挑战性的任务中广泛地评估了所研究的架构，并且我们在三个不同的数据集上报告了定量和定性的结果。最后，我们的密集视差估计网络实现了所提出的通用架构，在KITTI 2015测试中实现了超越先前方法的最新成果。

##### URL
[https://arxiv.org/abs/1612.04770](https://arxiv.org/abs/1612.04770)

##### PDF
[https://arxiv.org/pdf/1612.04770](https://arxiv.org/pdf/1612.04770)

