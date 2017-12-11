---
layout: post
title: "Dense Optical Flow based Change Detection Network Robust to Difference of Camera Viewpoints"
date: 2017-12-08 05:05:51
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Ken Sakurada, Weimin Wang, Nobuo Kawaguchi, Ryosuke Nakamura
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel method for detecting scene changes from a pair of images with a difference of camera viewpoints using a dense optical flow based change detection network. In the case that camera poses of input images are fixed or known, such as with surveillance and satellite cameras, the pixel correspondence between the images captured at different times can be known. Hence, it is possible to comparatively accurately detect scene changes between the images by modeling the appearance of the scene. On the other hand, in case of cameras mounted on a moving object, such as ground and aerial vehicles, we must consider the spatial correspondence between the images captured at different times. However, it can be difficult to accurately estimate the camera pose or 3D model of a scene, owing to the scene changes or lack of imagery. To solve this problem, we propose a change detection convolutional neural network utilizing dense optical flow between input images to improve the robustness to the difference between camera viewpoints. Our evaluation based on the panoramic change detection dataset shows that the proposed method outperforms state-of-the-art change detection algorithms.

##### Abstract (translated by Google)
本文提出了一种使用基于密集光流变化检测网络从具有不同相机视点的一对图像中检测场景变化的新方法。在诸如监视和卫星摄像机的固定或已知输入图像的相机姿态的情况下，可以知道在不同时间拍摄的图像之间的像素对应关系。因此，通过建模场景的外观，可以比较准确地检测图像之间的场景变化。另一方面，对于安装在移动物体如地面和飞行器上的摄像机，我们必须考虑在不同时间拍摄的图像之间的空间对应关系。然而，由于场景变化或缺乏图像，可能难以准确地估计场景的相机姿态或3D模型。为了解决这个问题，我们提出了一种改变检测卷积神经网络，利用输入图像之间的密集光流来提高对相机视点之间差异的鲁棒性。我们基于全景变化检测数据集的评估表明，所提出的方法胜过了最先进的变化检测算法。

##### URL
[http://arxiv.org/abs/1712.02941](http://arxiv.org/abs/1712.02941)

##### PDF
[http://arxiv.org/pdf/1712.02941](http://arxiv.org/pdf/1712.02941)

