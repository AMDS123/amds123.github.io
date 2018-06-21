---
layout: post
title: "Weighted Hausdorff Distance: A Loss Function For Object Localization"
date: 2018-06-20 05:57:26
categories: arXiv_CV
tags: arXiv_CV CNN
author: Javier Ribera, David G&#xfc;era, Yuhao Chen, Edward Delp
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in Convolutional Neural Networks (CNN) have achieved remarkable results in localizing objects in images. In these networks, the training procedure usually requires providing bounding boxes or the maximum number of expected objects. In this paper, we address the task of estimating object locations without annotated bounding boxes, which are typically hand-drawn and time consuming to label. We propose a loss function that can be used in any Fully Convolutional Network (FCN) to estimate object locations. This loss function is a modification of the Average Hausdorff Distance between two unordered sets of points. The proposed method does not require one to "guess" the maximum number of objects in the image, and has no notion of bounding boxes, region proposals, or sliding windows. We evaluate our method with three datasets designed to locate people's heads, pupil centers and plant centers. We report an average precision and recall of 94% for the three datasets, and an average location error of 6 pixels in 256x256 images.

##### Abstract (translated by Google)
卷积神经网络（CNN）的最新进展在图像中定位物体方面取得了显着的成果。在这些网络中，训练过程通常需要提供边界框或期望对象的最大数量。在本文中，我们解决了估算物体位置的任务，没有带注释的边界框，这些边界框通常是手绘的且耗时的标注。我们提出了一个可用于任何完全卷积网络（FCN）来估计物体位置的损失函数。该损失函数是两个无序点集之间的平均Hausdorff距离的修改。所提出的方法不需要“猜测”图像中的最大数量的对象，并且不具有边界框，区域提议或滑动窗口的概念。我们使用三个数据集来评估我们的方法，这些数据集旨在查找人员头部，学生中心和工厂中心。我们报告三个数据集的平均精确度和召回率为94％，256x256图像的平均位置误差为6个像素。

##### URL
[http://arxiv.org/abs/1806.07564](http://arxiv.org/abs/1806.07564)

##### PDF
[http://arxiv.org/pdf/1806.07564](http://arxiv.org/pdf/1806.07564)

