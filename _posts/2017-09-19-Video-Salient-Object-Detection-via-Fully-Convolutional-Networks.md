---
layout: post
title: "Video Salient Object Detection via Fully Convolutional Networks"
date: 2017-09-19 01:45:42
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Deep_Learning Detection
author: Wenguan Wang, Jianbing Shen, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a deep learning model to efficiently detect salient regions in videos. It addresses two important issues: (1) deep video saliency model training with the absence of sufficiently large and pixel-wise annotated video data; and (2) fast video saliency training and detection. The proposed deep video saliency network consists of two modules, for capturing the spatial and temporal saliency information, respectively. The dynamic saliency model, explicitly incorporating saliency estimates from the static saliency model, directly produces spatiotemporal saliency inference without time-consuming optical flow computation. We further propose a novel data augmentation technique that simulates video training data from existing annotated image datasets, which enables our network to learn diverse saliency information and prevents overfitting with the limited number of training videos. Leveraging our synthetic video data (150K video sequences) and real videos, our deep video saliency model successfully learns both spatial and temporal saliency cues, thus producing accurate spatiotemporal saliency estimate. We advance the state-of-the-art on the DAVIS dataset (MAE of .06) and the FBMS dataset (MAE of .07), and do so with much improved speed (2fps with all steps).

##### Abstract (translated by Google)
本文提出了一个深度学习模型来有效地检测视频中的显着区域。它解决了两个重要的问题：（1）深度视频显着性模型训练，缺乏足够大的像素注释视频数据;和（2）快速的视频显着性训练和检测。所提出的深度视频显着性网络由两个模块组成，分别用于捕获空间和时间显着性信息。动态显着性模型明确地结合了来自静态显着性模型的显着性估计，直接产生时空显着性推断，而不需要耗费时间的光流计算。我们进一步提出了一种新的数据增强技术，它可以模拟来自现有注释图像数据集的视频训练数据，这使得我们的网络能够学习不同的显着性信息，并防止有限数量的训练视频过度拟合。利用我们的合成视频数据（150K视频序列）和真实视频，我们的深度视频显着性模型成功地学习了空间和时间显着性提示，从而产生精确的时空显着性估计。我们推进DAVIS数据集（.06的MAE）和FBMS数据集（.07的MAE）的最新技术，并以更快的速度（每步2fps）完成。

##### URL
[https://arxiv.org/abs/1702.00871](https://arxiv.org/abs/1702.00871)

