---
layout: post
title: "Deep Stereo Matching with Dense CRF Priors"
date: 2017-01-24 20:08:28
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Deep_Learning
author: Ron Slossberg, Aaron Wetzler, Ron Kimmel
mathjax: true
---

* content
{:toc}

##### Abstract
Stereo reconstruction from rectified images has recently been revisited within the context of deep learning. Using a deep Convolutional Neural Network to obtain patch-wise matching cost volumes has resulted in state of the art stereo reconstruction on classic datasets like Middlebury and Kitti. By introducing this cost into a classical stereo pipeline, the final results are improved dramatically over non-learning based cost models. However these pipelines typically include hand engineered post processing steps to effectively regularize and clean the result. Here, we show that it is possible to take a more holistic approach by training a fully end-to-end network which directly includes regularization in the form of a densely connected Conditional Random Field (CRF) that acts as a prior on inter-pixel interactions. We demonstrate that our approach on both synthetic and real world datasets outperforms an alternative end-to-end network and compares favorably to more hand engineered approaches.

##### Abstract (translated by Google)
矫正图像的立体重建最近在深度学习的背景下进行了重新审视。使用深度卷积神经网络来获得贴片匹配的成本体积已经导致了像Middlebury和Kitti这样的经典数据集的最先进的立体重建。通过将这个成本引入到经典的立体声管道中，最终的结果比基于非学习的成本模型显着改善。然而，这些管道通常包括手工后处理步骤，以有效地调整和清洁结果。在这里，我们表明，可以采取更全面的方法，通过训练一个完全的端到端的网络，直接包括规则化形式的密集连接的条件随机场（CRF）的形式，作为先验的像素间互动。我们证明，我们在合成和现实世界数据集上的方法胜过了另一种端到端的网络，并且与更多的手工方法相比更有优势。

##### URL
[https://arxiv.org/abs/1612.01725](https://arxiv.org/abs/1612.01725)

##### PDF
[https://arxiv.org/pdf/1612.01725](https://arxiv.org/pdf/1612.01725)

