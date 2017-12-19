---
layout: post
title: "Improving Image Classification with Location Context"
date: 2015-05-14 20:13:34
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification Recognition
author: Kevin Tang, Manohar Paluri, Li Fei-Fei, Rob Fergus, Lubomir Bourdev
mathjax: true
---

* content
{:toc}

##### Abstract
With the widespread availability of cellphones and cameras that have GPS capabilities, it is common for images being uploaded to the Internet today to have GPS coordinates associated with them. In addition to research that tries to predict GPS coordinates from visual features, this also opens up the door to problems that are conditioned on the availability of GPS coordinates. In this work, we tackle the problem of performing image classification with location context, in which we are given the GPS coordinates for images in both the train and test phases. We explore different ways of encoding and extracting features from the GPS coordinates, and show how to naturally incorporate these features into a Convolutional Neural Network (CNN), the current state-of-the-art for most image classification and recognition problems. We also show how it is possible to simultaneously learn the optimal pooling radii for a subset of our features within the CNN framework. To evaluate our model and to help promote research in this area, we identify a set of location-sensitive concepts and annotate a subset of the Yahoo Flickr Creative Commons 100M dataset that has GPS coordinates with these concepts, which we make publicly available. By leveraging location context, we are able to achieve almost a 7% gain in mean average precision.

##### Abstract (translated by Google)
随着具有GPS功能的手机和相机的普及，通常今天上传到互联网的图像具有与其相关联的GPS坐标。除了试图从视觉特征预测GPS坐标的研究之外，这也打开了以GPS坐标的可用性为条件的问题的大门。在这项工作中，我们解决了使用位置上下文进行图像分类的问题，在这个问题中我们在列车和测试阶段都给出了图像的GPS坐标。我们探索了从GPS坐标编码和提取特征的不同方式，并展示了如何将这些特征自然地结合到卷积神经网络（CNN）中，这是目前大多数图像分类和识别问题的最新技术。我们还展示了如何在CNN框架内同时学习我们特征的一个子集的最优池化半径。为了评估我们的模型并帮助推动这一领域的研究，我们确定了一组位置敏感的概念，并注释了具有GPS坐标的雅虎Flickr Creative Commons 100M数据集的子集，这些概念我们公开提供。通过利用位置上下文，我们能够在均值平均精度上获得近7％的增益。

##### URL
[https://arxiv.org/abs/1505.03873](https://arxiv.org/abs/1505.03873)

##### PDF
[https://arxiv.org/pdf/1505.03873](https://arxiv.org/pdf/1505.03873)

