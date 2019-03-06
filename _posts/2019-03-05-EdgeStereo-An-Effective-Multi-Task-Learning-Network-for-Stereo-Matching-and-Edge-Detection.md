---
layout: post
title: "EdgeStereo: An Effective Multi-Task Learning Network for Stereo Matching and Edge Detection"
date: 2019-03-05 07:00:40
categories: arXiv_CV
tags: arXiv_CV Regularization Embedding CNN Prediction Detection
author: Xiao Song, Xu Zhao, Liangji Fang, Hanwen Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, leveraging on the development of end-to-end convolutional neural networks, deep stereo matching networks achieve remarkable performance far exceeding traditional approaches. However, state-of-the-art stereo methods still have difficulties finding correct correspondences in texture-less regions, detailed structures, small objects and near boundaries, which could be alleviated by geometric clues such as edge contours and corresponding constraints. To improve the quality of disparity estimates in these challenging areas, we propose an effective multi-task learning network EdgeStereo composed of a disparity estimation sub-network and an edge detection sub-network, which enables end-to-end predictions of both disparity map and edge map. To effectively incorporates edge cues, we propose the edge-aware smoothness loss and edge feature embedding for inter-task interactions. It is demonstrated that based on our unified model, edge detection task and stereo matching task can promote each other. In addition, we design a compact module called residual pyramid to replace the commonly-used multi-stage cascaded structures or 3-D convolution based regularization modules in current stereo matching networks. By the time of the paper submission, EdgeStereo achieves state-of-the-art performance on the FlyingThings3D dataset, KITTI 2012 and KITTI 2015 stereo benchmarks, outperforming other published stereo matching methods by a noteworthy margin. EdgeStereo also has a better generalization capability for disparity estimation because of the incorporation of edge cues.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.01700](https://arxiv.org/abs/1903.01700)

##### PDF
[https://arxiv.org/pdf/1903.01700](https://arxiv.org/pdf/1903.01700)

