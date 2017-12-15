---
layout: post
title: "Segmentation Rectification for Video Cutout via One-Class Structured Learning"
date: 2016-02-16 04:31:20
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Classification
author: Junyan Wang, Sai-kit Yeung, Jue Wang, Kun Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Recent works on interactive video object cutout mainly focus on designing dynamic foreground-background (FB) classifiers for segmentation propagation. However, the research on optimally removing errors from the FB classification is sparse, and the errors often accumulate rapidly, causing significant errors in the propagated frames. In this work, we take the initial steps to addressing this problem, and we call this new task \emph{segmentation rectification}. Our key observation is that the possibly asymmetrically distributed false positive and false negative errors were handled equally in the conventional methods. We, alternatively, propose to optimally remove these two types of errors. To this effect, we propose a novel bilayer Markov Random Field (MRF) model for this new task. We also adopt the well-established structured learning framework to learn the optimal model from data. Additionally, we propose a novel one-class structured SVM (OSSVM) which greatly speeds up the structured learning process. Our method naturally extends to RGB-D videos as well. Comprehensive experiments on both RGB and RGB-D data demonstrate that our simple and effective method significantly outperforms the segmentation propagation methods adopted in the state-of-the-art video cutout systems, and the results also suggest the potential usefulness of our method in image cutout system.

##### Abstract (translated by Google)
最近关于交互式视频对象剪切的研究主要集中在设计用于分割传播的动态前景背景（FB）分类器。然而，从FB分类中去除错误的研究是很少的，而且这些错误经常会迅速积累，造成传播帧中的重大错误。在这项工作中，我们采取了最初的步骤来解决这个问题，我们把这个新的任务叫做分段纠正。我们的主要观察结果是，在传统方法中，可能的不对称分布的假阳性和假阴性错误是同等处理的。或者，我们建议最佳地消除这两种类型的错误。为此，我们提出了一个新的双层马尔可夫随机场（MRF）模型用于这个新的任务。我们还采用完善的结构化学习框架，从数据中学习最优模型。此外，我们提出了一种新颖的一类结构化支持向量机（OSSVM），大大加快了结构化学习过程。我们的方法自然延伸到RGB-D视频。 RGB和RGB-D数据的综合实验表明，我们的简单而有效的方法明显优于最先进的视频剪切系统中采用的分割传播方法，并且结果还表明了我们的方法在图像中的潜在有用性剪切系统。

##### URL
[https://arxiv.org/abs/1602.04906](https://arxiv.org/abs/1602.04906)

##### PDF
[https://arxiv.org/pdf/1602.04906](https://arxiv.org/pdf/1602.04906)

