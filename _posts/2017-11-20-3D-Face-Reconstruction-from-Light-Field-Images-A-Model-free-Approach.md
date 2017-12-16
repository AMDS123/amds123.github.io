---
layout: post
title: "3D Face Reconstruction from Light Field Images: A Model-free Approach"
date: 2017-11-20 01:35:09
categories: arXiv_CV
tags: arXiv_CV Face
author: Mingtao Feng, Syed Zulqarnain Gilani, Yaonan Wang, Ajmal Mian
mathjax: true
---

* content
{:toc}

##### Abstract
Reconstructing 3D facial geometry from a single RGB image has recently instigated wide research interest. However, it is still an ill-posed problem and most methods rely on prior models hence undermining the accuracy of the recovered 3D faces. In this paper, we exploit the Epipolar Plane Images (EPI) obtained from light field cameras and learn CNN models that recover horizontal and vertical 3D facial curves from the respective horizontal and vertical EPIs. Our 3D face reconstruction network (FaceLFnet) comprises a densely connected architecture to learn accurate 3D facial curves from low resolution EPIs. To train the proposed FaceLFnets from scratch, we synthesize photo-realistic light field images from 3D facial scans. The curve by curve 3D face estimation approach allows the networks to learn from only 14K images of 80 identities, which still comprises over 11 Million EPIs/curves. The estimated facial curves are merged into a single pointcloud to which a surface is fitted to get the final 3D face. Our method is model-free, requires only a few training samples to learn FaceLFnet and can reconstruct 3D faces with high accuracy from single light field images under varying poses, expressions and lighting conditions. Comparison on the BU-3DFE and BU-4DFE datasets show that our method reduces reconstruction errors by over 20% compared to recent state of the art.

##### Abstract (translated by Google)
从单个RGB图像重建3D面部几何最近引起了广泛的研究兴趣。然而，它仍然是一个不适合的问题，大多数方法依赖于先前的模型，因此破坏了恢复的3D面的准确性。在本文中，我们利用从光场摄像机获得的极线平面图像（EPI），并学习从各个水平和垂直EPI恢复水平和垂直3D面部曲线的CNN模型。我们的3D人脸重建网络（FaceLFnet）由密集连接的结构组成，可以从低分辨率的EPI学习精确的3D面部曲线。为了从头开始培训所提议的FaceLFnet，我们合成来自3D面部扫描的照片逼真的光场图像。通过曲线三维人脸估计方法的曲线允许网络仅从80个身份的14K图像中学习，其仍然包括超过1100万个EPI /曲线。估计的面部曲线合并成一个单一的点云，表面拟合得到最终的3D面部。我们的方法是无模型的，只需要几个训练样本就可以学习FaceLFnet，并且可以在不同的姿势，表情和照明条件下，从单个光场图像中高精度地重建3D人脸。 BU-3DFE和BU-4DFE数据集的比较表明，与最近的现有技术相比，我们的方法将重建误差减少了20％以上。

##### URL
[https://arxiv.org/abs/1711.05953](https://arxiv.org/abs/1711.05953)

##### PDF
[https://arxiv.org/pdf/1711.05953](https://arxiv.org/pdf/1711.05953)

