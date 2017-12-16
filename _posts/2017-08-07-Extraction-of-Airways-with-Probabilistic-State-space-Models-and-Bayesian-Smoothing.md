---
layout: post
title: "Extraction of Airways with Probabilistic State-space Models and Bayesian Smoothing"
date: 2017-08-07 12:43:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Tracking Detection
author: Raghavendra Selvan, Jens Petersen, Jesper H. Pedersen, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
Segmenting tree structures is common in several image processing applications. In medical image analysis, reliable segmentations of airways, vessels, neurons and other tree structures can enable important clinical applications. We present a framework for tracking tree structures comprising of elongated branches using probabilistic state-space models and Bayesian smoothing. Unlike most existing methods that proceed with sequential tracking of branches, we present an exploratory method, that is less sensitive to local anomalies in the data due to acquisition noise and/or interfering structures. The evolution of individual branches is modelled using a process model and the observed data is incorporated into the update step of the Bayesian smoother using a measurement model that is based on a multi-scale blob detector. Bayesian smoothing is performed using the RTS (Rauch-Tung-Striebel) smoother, which provides Gaussian density estimates of branch states at each tracking step. We select likely branch seed points automatically based on the response of the blob detection and track from all such seed points using the RTS smoother. We use covariance of the marginal posterior density estimated for each branch to discriminate false positive and true positive branches. The method is evaluated on 3D chest CT scans to track airways. We show that the presented method results in additional branches compared to a baseline method based on region growing on probability images.

##### Abstract (translated by Google)
分割树结构在多个图像处理应用中是常见的。在医学图像分析中，气道，血管，神经元和其他树结构的可靠分割可以实现重要的临床应用。我们提出了一个使用概率状态空间模型和贝叶斯平滑来跟踪包括细长分支的树结构的框架。与大多数现有的分支顺序跟踪方法不同，我们提出了一种探测方法，这种方法由于采集噪声和/或干扰结构而对数据中的局部异常较不敏感。使用过程模型对单个分支的演化进行建模，并且使用基于多尺度斑点检测器的测量模型将观测数据并入到贝叶斯平滑器的更新步骤中。使用RTS（Rauch-Tung-Striebel）平滑器进行贝叶斯平滑，其在每个跟踪步骤提供分支状态的高斯密度估计。我们根据斑点检测的响应自动选择可能的分支种子点，并使用RTS平滑器从所有这样的种子点跟踪。我们使用每个分支估计的边缘后验密度的协方差来区分假阳性和假阳性分支。该方法在3D胸部CT扫描上进行评估以追踪气道。我们表明，提出的方法导致额外的分支相比，基于概率图像区域增长的基准方法。

##### URL
[https://arxiv.org/abs/1708.02096](https://arxiv.org/abs/1708.02096)

##### PDF
[https://arxiv.org/pdf/1708.02096](https://arxiv.org/pdf/1708.02096)

