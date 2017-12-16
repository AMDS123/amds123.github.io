---
layout: post
title: "Deep Extreme Cut: From Extreme Points to Object Segmentation"
date: 2017-11-24 18:54:35
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Kevis-Kokitsi Maninis, Sergi Caelles, Jordi Pont-Tuset, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
This paper explores the use of extreme points in an object (left-most, right-most, top, bottom pixels) as input to obtain precise object segmentation for images and videos. We do so by adding an extra channel to the image in the input of a convolutional neural network (CNN), which contains a Gaussian centered in each of the extreme points. The CNN learns to transform this information into a segmentation of an object that matches those extreme points. We demonstrate the usefulness of this approach for guided segmentation (grabcut-style), interactive segmentation, video object segmentation, and dense segmentation annotation. We show that we obtain the most precise results to date, also with less user input, in an extensive and varied selection of benchmarks and datasets. All our models and code will be made publicly available.

##### Abstract (translated by Google)
本文探讨了在对象（最左侧，最右侧，顶部，底部像素）中使用极值点作为输入，以获得图像和视频的精确对象分割。我们这样做是通过在卷积神经网络（CNN）的输入中添加一个额外的通道给图像，该卷积神经网络包含以每个极值点为中心的高斯。 CNN学习将这些信息转换成与那些极端点相匹配的对象的分割。我们证明了这种方法在指导分割（抓取样式），交互分割，视频对象分割和密集分割注释方面的有用性。我们表明，我们获得了迄今为止最精确的结果，也是用较少的用户输入，在基准和数据集的广泛和多样的选择。我们所有的型号和代码都将公开发布。

##### URL
[https://arxiv.org/abs/1711.09081](https://arxiv.org/abs/1711.09081)

##### PDF
[https://arxiv.org/pdf/1711.09081](https://arxiv.org/pdf/1711.09081)

