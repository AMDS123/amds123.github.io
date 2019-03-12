---
layout: post
title: "Rolling-Shutter-Aware Differential SfM and Image Rectification"
date: 2019-03-10 07:29:25
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Bingbing Zhuang, Loong-Fah Cheong, Gim Hee Lee
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we develop a modified differential Structure from Motion (SfM) algorithm that can estimate relative pose from two consecutive frames despite of Rolling Shutter (RS) artifacts. In particular, we show that under constant velocity assumption, the errors induced by the rolling shutter effect can be easily rectified by a linear scaling operation on each optical flow. We further propose a 9-point algorithm to recover the relative pose of a rolling shutter camera that undergoes constant acceleration motion. We demonstrate that the dense depth maps recovered from the relative pose of the RS camera can be used in a RS-aware warping for image rectification to recover high-quality Global Shutter (GS) images. Experiments on both synthetic and real RS images show that our RS-aware differential SfM algorithm produces more accurate results on relative pose estimation and 3D reconstruction from images distorted by RS effect compared to standard SfM algorithms that assume a GS camera model. We also demonstrate that our RS-aware warping for image rectification method outperforms state-of-the-art commercial software products, i.e. Adobe After Effects and Apple Imovie, at removing RS artifacts.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.03943](https://arxiv.org/abs/1903.03943)

##### PDF
[https://arxiv.org/pdf/1903.03943](https://arxiv.org/pdf/1903.03943)

