---
layout: post
title: "Large Pose 3D Face Reconstruction from a Single Image via Direct Volumetric CNN Regression"
date: 2017-09-08 09:10:08
categories: arXiv_CV
tags: arXiv_CV Face CNN
author: Aaron S. Jackson, Adrian Bulat, Vasileios Argyriou, Georgios Tzimiropoulos
mathjax: true
---

* content
{:toc}

##### Abstract
3D face reconstruction is a fundamental Computer Vision problem of extraordinary difficulty. Current systems often assume the availability of multiple facial images (sometimes from the same subject) as input, and must address a number of methodological challenges such as establishing dense correspondences across large facial poses, expressions, and non-uniform illumination. In general these methods require complex and inefficient pipelines for model building and fitting. In this work, we propose to address many of these limitations by training a Convolutional Neural Network (CNN) on an appropriate dataset consisting of 2D images and 3D facial models or scans. Our CNN works with just a single 2D facial image, does not require accurate alignment nor establishes dense correspondence between images, works for arbitrary facial poses and expressions, and can be used to reconstruct the whole 3D facial geometry (including the non-visible parts of the face) bypassing the construction (during training) and fitting (during testing) of a 3D Morphable Model. We achieve this via a simple CNN architecture that performs direct regression of a volumetric representation of the 3D facial geometry from a single 2D image. We also demonstrate how the related task of facial landmark localization can be incorporated into the proposed framework and help improve reconstruction quality, especially for the cases of large poses and facial expressions. Testing code will be made available online, along with pre-trained models this http URL

##### Abstract (translated by Google)
3D面部重建是一个非常困难的计算机视觉问题。目前的系统通常假定可以获得多个面部图像（有时来自同一主题）作为输入，并且必须解决许多方法上的挑战，例如建立跨大面部姿势，表情和非均匀照明的密集对应。一般而言，这些方法需要复杂和低效的管道建模和拟合。在这项工作中，我们提出通过在由2D图像和3D面部模型或扫描组成的适当数据集上训练卷积神经网络（CNN）来解决这些限制中的许多问题。我们的CNN只需要一个2D面部图像，不需要精确的对齐，也不需要在图像之间建立密集的对应关系，适用于任意的面部表情和表情，并且可以用来重建整个3D面部几何体（包括不可见部分在训练过程中）和拟合（在测试期间）3D形变模型。我们通过一个简单的CNN体​​系结构来实现这一点，该体系结构从单个2D图像执行3D面部几何体积的体积表示。我们还演示了面部标志点定位的相关任务如何被纳入到所提出的框架中，并有助于提高重建质量，特别是对于大姿势和面部表情的情况。测试代码将在网上提供，同时还有预先训练的模型这个http URL

##### URL
[https://arxiv.org/abs/1703.07834](https://arxiv.org/abs/1703.07834)

##### PDF
[https://arxiv.org/pdf/1703.07834](https://arxiv.org/pdf/1703.07834)

