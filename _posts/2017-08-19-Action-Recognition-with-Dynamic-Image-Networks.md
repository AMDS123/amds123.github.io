---
layout: post
title: "Action Recognition with Dynamic Image Networks"
date: 2017-08-19 20:54:07
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Recognition
author: Hakan Bilen, Basura Fernando, Efstratios Gavves, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the concept of "dynamic image", a novel compact representation of videos useful for video analysis, particularly in combination with convolutional neural networks (CNNs). A dynamic image encodes temporal data such as RGB or optical flow videos by using the concept of `rank pooling'. The idea is to learn a ranking machine that captures the temporal evolution of the data and to use the parameters of the latter as a representation. When a linear ranking machine is used, the resulting representation is in the form of an image, which we call dynamic because it summarizes the video dynamics in addition of appearance. This is a powerful idea because it allows to convert any video to an image so that existing CNN models pre-trained for the analysis of still images can be immediately extended to videos. We also present an efficient and effective approximate rank pooling operator, accelerating standard rank pooling algorithms by orders of magnitude, and formulate that as a CNN layer. This new layer allows generalizing dynamic images to dynamic feature maps. We demonstrate the power of the new representations on standard benchmarks in action recognition achieving state-of-the-art performance.

##### Abstract (translated by Google)
我们引入了“动态图像”的概念，这是一种对视频分析特别是与卷积神经网络（CNN）结合使用的视频新颖紧凑表示。动态图像通过使用“等级池”的概念对诸如RGB或光流视频的时间数据进行编码。这个想法是学习一个排序机器，捕捉数据的时间演变，并使用后者的参数作为表示。当使用线性排序机器时，所得到的表示形式为图像，我们称之为动态图像，因为它总结了除了外观之外的视频动态。这是一个强大的想法，因为它允许将任何视频转换为图像，以便现有的CNN模型预先训练用于分析静止图像，可以立即扩展到视频。我们还提出了一个高效和有效的近似等级汇集算子，将标准等级汇聚算法加速数量级，并将其作为CNN层。这个新层允许将动态图像概括为动态特征图。我们在行动识别的标准基准上展示新表征的力量，实现了最先进的性能表现。

##### URL
[https://arxiv.org/abs/1612.00738](https://arxiv.org/abs/1612.00738)

##### PDF
[https://arxiv.org/pdf/1612.00738](https://arxiv.org/pdf/1612.00738)

