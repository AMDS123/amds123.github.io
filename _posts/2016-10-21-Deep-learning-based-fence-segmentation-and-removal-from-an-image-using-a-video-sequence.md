---
layout: post
title: "Deep learning based fence segmentation and removal from an image using a video sequence"
date: 2016-10-21 13:08:23
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Optimization Deep_Learning
author: Sankaraganesh Jonna, Krishna K. Nakka, Rajiv R. Sahay
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional approaches to image de-fencing use multiple adjacent frames for segmentation of fences in the reference image and are limited to restoring images of static scenes only. In this paper, we propose a de-fencing algorithm for images of dynamic scenes using an occlusion-aware optical flow method. We divide the problem of image de-fencing into the tasks of automated fence segmentation from a single image, motion estimation under known occlusions and fusion of data from multiple frames of a captured video of the scene. Specifically, we use a pre-trained convolutional neural network to segment fence pixels from a single image. The knowledge of spatial locations of fences is used to subsequently estimate optical flow in the occluded frames of the video for the final data fusion step. We cast the fence removal problem in an optimization framework by modeling the formation of the degraded observations. The inverse problem is solved using fast iterative shrinkage thresholding algorithm (FISTA). Experimental results show the effectiveness of proposed algorithm.

##### Abstract (translated by Google)
传统的图像防护方法使用多个相邻帧来对参考图像中的栅栏进行分割，并且仅限于仅恢复静态场景的图像。在本文中，我们提出了一种使用遮挡感知光流方法的动态场景图像去栅栏算法。我们将图像防护问题划分为单个图像的自动化篱笆分割任务，已知遮挡下的运动估计以及场景撷取视频的多帧数据融合。具体来说，我们使用预先训练的卷积神经网络来分割单个图像的围栏像素。栅栏的空间位置的知识被用于随后估计视频的遮挡帧中的光流以进行最后的数据融合步骤。我们通过对退化观测的形成进行建模，在优化框架中投射栅栏去除问题。使用快速迭代收缩阈值算法（FISTA）解决逆问题。实验结果表明了该算法的有效性。

##### URL
[https://arxiv.org/abs/1609.07727](https://arxiv.org/abs/1609.07727)

##### PDF
[https://arxiv.org/pdf/1609.07727](https://arxiv.org/pdf/1609.07727)

