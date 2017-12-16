---
layout: post
title: "A Simple, Fast and Highly-Accurate Algorithm to Recover 3D Shape from 2D Landmarks on a Single Image"
date: 2016-09-28 19:58:37
categories: arXiv_CV
tags: arXiv_CV Face
author: Ruiqi Zhao, Yan Wang, Aleix Martinez
mathjax: true
---

* content
{:toc}

##### Abstract
Three-dimensional shape reconstruction of 2D landmark points on a single image is a hallmark of human vision, but is a task that has been proven difficult for computer vision algorithms. We define a feed-forward deep neural network algorithm that can reconstruct 3D shapes from 2D landmark points almost perfectly (i.e., with extremely small reconstruction errors), even when these 2D landmarks are from a single image. Our experimental results show an improvement of up to two-fold over state-of-the-art computer vision algorithms; 3D shape reconstruction of human faces is given at a reconstruction error < .004, cars at .0022, human bodies at .022, and highly-deformable flags at an error of .0004. Our algorithm was also a top performer at the 2016 3D Face Alignment in the Wild Challenge competition (done in conjunction with the European Conference on Computer Vision, ECCV) that required the reconstruction of 3D face shape from a single image. The derived algorithm can be trained in a couple hours and testing runs at more than 1, 000 frames/s on an i7 desktop. We also present an innovative data augmentation approach that allows us to train the system efficiently with small number of samples. And the system is robust to noise (e.g., imprecise landmark points) and missing data (e.g., occluded or undetected landmark points).

##### Abstract (translated by Google)
二维地标点在单个图像上的三维形状重建是人类视觉的一个标志，但是对于计算机视觉算法已经证明是困难的任务。我们定义了一个前馈深层神经网络算法，即使当这些2D地标来自单个图像时，也可以几乎完美地（即，具有非常小的重建误差）从2D地标点重建3D形状。我们的实验结果显示比现有技术的计算机视觉算法提高了两倍;重建误差<0.004，车辆0.0022，人体0.022，高度可变形的标志错误0.0004。我们的算法在“野外挑战”比赛中的2016 3D面孔对齐（与欧洲计算机视觉会议（ECCV）一起完成）中也是表现最出色的，这需要从单个图像重建3D面部形状。派生的算法可以在几个小时内进行训练，测试在i7桌面上以超过1,000帧/秒的速度运行。我们还提出了一种创新的数据增强方法，使我们能够以少量样本高效地训练系统。并且该系统对噪声（例如，不准确的界标点）和丢失的数据（例如，被遮挡或未被检测到的界标点）是鲁棒的。

##### URL
[https://arxiv.org/abs/1609.09058](https://arxiv.org/abs/1609.09058)

##### PDF
[https://arxiv.org/pdf/1609.09058](https://arxiv.org/pdf/1609.09058)

