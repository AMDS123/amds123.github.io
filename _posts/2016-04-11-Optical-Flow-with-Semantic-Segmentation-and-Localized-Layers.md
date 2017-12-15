---
layout: post
title: "Optical Flow with Semantic Segmentation and Localized Layers"
date: 2016-04-11 13:00:13
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Laura Sevilla-Lara, Deqing Sun, Varun Jampani, Michael J. Black
mathjax: true
---

* content
{:toc}

##### Abstract
Existing optical flow methods make generic, spatially homogeneous, assumptions about the spatial structure of the flow. In reality, optical flow varies across an image depending on object class. Simply put, different objects move differently. Here we exploit recent advances in static semantic scene segmentation to segment the image into objects of different types. We define different models of image motion in these regions depending on the type of object. For example, we model the motion on roads with homographies, vegetation with spatially smooth flow, and independently moving objects like cars and planes with affine motion plus deviations. We then pose the flow estimation problem using a novel formulation of localized layers, which addresses limitations of traditional layered models for dealing with complex scene motion. Our semantic flow method achieves the lowest error of any published monocular method in the KITTI-2015 flow benchmark and produces qualitatively better flow and segmentation than recent top methods on a wide range of natural videos.

##### Abstract (translated by Google)
现有的光流方法对流的空间结构进行通用的，空间上均匀的假设。实际上，根据物体的类别，光流在整个图像上是变化的。简而言之，不同的对象移动不同。这里我们利用静态语义场景分割的最新进展将图像分割成不同类型的对象。我们根据物体的类型在这些区域定义不同的图像运动模型。例如，我们用单应性，具有空间平滑流动的植被来模拟道路上的运动，并且用仿射运动加偏差独立地运动诸如汽车和飞机的物体。然后，我们使用一种新的局部化层的公式来构造流量估计问题，这解决了传统分层模型处理复杂场景运动的局限性。我们的语义流方法在KITTI-2015流量基准测试中实现了任何已发布的单眼测试方法的最低误差，并且在广泛的自然视频上产生了比最新的顶级方法更好的流量和分割。

##### URL
[https://arxiv.org/abs/1603.03911](https://arxiv.org/abs/1603.03911)

##### PDF
[https://arxiv.org/pdf/1603.03911](https://arxiv.org/pdf/1603.03911)

