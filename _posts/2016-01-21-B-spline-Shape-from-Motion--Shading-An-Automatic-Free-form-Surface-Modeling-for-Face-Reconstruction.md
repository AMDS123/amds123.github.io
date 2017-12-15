---
layout: post
title: "B-spline Shape from Motion & Shading: An Automatic Free-form Surface Modeling for Face Reconstruction"
date: 2016-01-21 14:11:40
categories: arXiv_CV
tags: arXiv_CV Face Optimization
author: Weilong Peng (1), Zhiyong Feng (1), Chao Xu (2) ((1) School of Computer Science, Tianjin University (2) School of Software, Tianjin University)
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, many methods have been proposed for face reconstruction from multiple images, most of which involve fundamental principles of Shape from Shading and Structure from motion. However, a majority of the methods just generate discrete surface model of face. In this paper, B-spline Shape from Motion and Shading (BsSfMS) is proposed to reconstruct continuous B-spline surface for multi-view face images, according to an assumption that shading and motion information in the images contain 1st- and 0th-order derivative of B-spline face respectively. Face surface is expressed as a B-spline surface that can be reconstructed by optimizing B-spline control points. Therefore, normals and 3D feature points computed from shading and motion of images respectively are used as the 1st- and 0th- order derivative information, to be jointly applied in optimizing the B-spline face. Additionally, an IMLS (iterative multi-least-square) algorithm is proposed to handle the difficult control point optimization. Furthermore, synthetic samples and LFW dataset are introduced and conducted to verify the proposed approach, and the experimental results demonstrate the effectiveness with different poses, illuminations, expressions etc., even with wild images.

##### Abstract (translated by Google)
近年来，人们提出了多种图像重建方法，其中大部分方法都涉及到从阴影和结构到运动的基本原理。但是，大多数方法只是生成离散的人脸表面模型。本文提出了基于运动和阴影的B样条形（BsSfMS）重构连续B样条曲面的多视图人脸图像，假设图像中的阴影和运动信息包含1阶和0阶B样条曲面的导数。面曲面表示为B样条曲面，可以通过优化B样条控制点进行重构。因此，将分别由图像的阴影和运动计算出的法线和三维特征点分别作为1阶和0阶导数信息，共同用于B样条曲面的优化。此外，还提出了IMLS（迭代多最小二乘）算法来处理困难的控制点优化问题。此外，还引入了合成样本和LFW数据集来验证所提出的方法，实验结果证明了即使在野外图像的情况下，不同的姿势，照明，表情等也是有效的。

##### URL
[https://arxiv.org/abs/1601.05644](https://arxiv.org/abs/1601.05644)

##### PDF
[https://arxiv.org/pdf/1601.05644](https://arxiv.org/pdf/1601.05644)

