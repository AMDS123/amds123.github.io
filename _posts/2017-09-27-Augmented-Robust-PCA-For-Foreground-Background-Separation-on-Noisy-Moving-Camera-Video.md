---
layout: post
title: "Augmented Robust PCA For Foreground-Background Separation on Noisy, Moving Camera Video"
date: 2017-09-27 04:17:43
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Chen Gao, Brian E. Moore, Raj Rao Nadakuditi
mathjax: true
---

* content
{:toc}

##### Abstract
This work presents a novel approach for robust PCA with total variation regularization for foreground-background separation and denoising on noisy, moving camera video. Our proposed algorithm registers the raw (possibly corrupted) frames of a video and then jointly processes the registered frames to produce a decomposition of the scene into a low-rank background component that captures the static components of the scene, a smooth foreground component that captures the dynamic components of the scene, and a sparse component that can isolate corruptions and other non-idealities. Unlike existing methods, our proposed algorithm produces a panoramic low-rank component that spans the entire field of view, automatically stitching together corrupted data from partially overlapping scenes. The low-rank portion of our robust PCA model is based on a recently discovered optimal low-rank matrix estimator (OptShrink) that requires no parameter tuning. We demonstrate the performance of our algorithm on both static and moving camera videos corrupted by noise and outliers.

##### Abstract (translated by Google)
这项工作提出了一种新颖的方法稳健PCA与前景背景分离和去噪嘈杂，移动摄像机视频总变异正则化。我们提出的算法注册视频的原始（可能是损坏的）帧，然后联合处理注册的帧，以产生场景分解成低级背景分量，捕获场景的静态分量，平滑的前景分量捕获场景的动态组件，以及可以隔离腐败和其他不理想的稀疏组件。与现有的方法不同，我们提出的算法产生一个横跨整个视野的全景低秩分量，自动地将来自部分重叠场景的损坏数据拼接在一起。我们稳健的PCA模型的低阶部分基于最近发现的最优低秩矩阵估计器（OptShrink），其不需要参数调整。我们演示了我们的算法在静态和移动摄像机视频中被噪声和异常值破坏的性能。

##### URL
[https://arxiv.org/abs/1709.09328](https://arxiv.org/abs/1709.09328)

##### PDF
[https://arxiv.org/pdf/1709.09328](https://arxiv.org/pdf/1709.09328)

