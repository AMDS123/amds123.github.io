---
layout: post
title: "3D Binary Signatures"
date: 2017-08-26 06:01:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Detection
author: Siddharth Srivastava, Brejesh Lall
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a novel binary descriptor for 3D point clouds. The proposed descriptor termed as 3D Binary Signature (3DBS) is motivated from the matching efficiency of the binary descriptors for 2D images. 3DBS describes keypoints from point clouds with a binary vector resulting in extremely fast matching. The method uses keypoints from standard keypoint detectors. The descriptor is built by constructing a Local Reference Frame and aligning a local surface patch accordingly. The local surface patch constitutes of identifying nearest neighbours based upon an angular constraint among them. The points are ordered with respect to the distance from the keypoints. The normals of the ordered pairs of these keypoints are projected on the axes and the relative magnitude is used to assign a binary digit. The vector thus constituted is used as a signature for representing the keypoints. The matching is done by using hamming distance. We show that 3DBS outperforms state of the art descriptors on various evaluation metrics.

##### Abstract (translated by Google)
在本文中，我们提出了一种新的三维点云二进制描述符。所提出的描述符被称为3D二进制签名（3DBS）是由二维图像的二进制描述符的匹配效率驱动的。 3DBS使用二元向量描述点云中的关键点，从而实现极其快速的匹配。该方法使用来自标准关键点检测器的关键点。描述符是通过构建一个局部参考帧并相应地调整一个局部曲面片来建立的。局部表面贴片是基于它们之间的角度约束来识别最近的邻居。这些点是根据距关键点的距离排序的。这些关键点的有序对的法线投影在轴上，相对大小用于分配一个二进制数字。这样构成的矢量被用作表示关键点的签名。匹配是通过使用海明距离完成的。我们表明，3DBS比各种评估指标的艺术描述符的状态好。

##### URL
[https://arxiv.org/abs/1708.07937](https://arxiv.org/abs/1708.07937)

##### PDF
[https://arxiv.org/pdf/1708.07937](https://arxiv.org/pdf/1708.07937)

