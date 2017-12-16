---
layout: post
title: "Text Recognition in Scene Image and Video Frame using Color Channel Selection"
date: 2017-07-27 23:12:13
categories: arXiv_CV
tags: arXiv_CV OCR Attention Recognition
author: Ayan Kumar Bhunia, Gautam Kumar, Partha Pratim Roy, R. Balasubramanian, Umapada Pal
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, recognition of text from natural scene image and video frame has got increased attention among the researchers due to its various complexities and challenges. Because of low resolution, blurring effect, complex background, different fonts, color and variant alignment of text within images and video frames, etc., text recognition in such scenario is difficult. Most of the current approaches usually apply a binarization algorithm to convert them into binary images and next OCR is applied to get the recognition result. In this paper, we present a novel approach based on color channel selection for text recognition from scene images and video frames. In the approach, at first, a color channel is automatically selected and then selected color channel is considered for text recognition. Our text recognition framework is based on Hidden Markov Model (HMM) which uses Pyramidal Histogram of Oriented Gradient features extracted from selected color channel. From each sliding window of a color channel our color-channel selection approach analyzes the image properties from the sliding window and then a multi-label Support Vector Machine (SVM) classifier is applied to select the color channel that will provide the best recognition results in the sliding window. This color channel selection for each sliding window has been found to be more fruitful than considering a single color channel for the whole word image. Five different features have been analyzed for multi-label SVM based color channel selection where wavelet transform based feature outperforms others. Our framework has been tested on different publicly available scene/video text image datasets. For Devanagari script, we collected our own data dataset. The performances obtained from experimental results are encouraging and show the advantage of the proposed method.

##### Abstract (translated by Google)
近年来，自然景象和视频帧的文本识别由于其复杂性和挑战性而受到越来越多的关注。由于图像和视频帧中的分辨率低，模糊效果差，背景复杂，字体不同，颜色不同以及文本变体排列等原因，文本识别难度较大。目前大多数方法通常采用二值化算法将其转换为二值图像，然后应用OCR来获得识别结果。在本文中，我们提出了一种基于颜色通道选择的新方法，用于从场景图像和视频帧中进行文本识别。在该方法中，首先自动选择颜色通道，然后选择颜色通道用于文本识别。我们的文本识别框架基于隐马尔可夫模型（HMM），该模型使用从所选择的颜色通道中提取的倾斜梯度直方图特征（Pyramidal Histogram of Oriented Gradient）。从颜色通道的每个滑动窗口我们的颜色通道选择方法从滑动窗口分析图像属性，然后使用多标签支持向量机（SVM）分类器来选择将提供最佳识别结果的颜色通道滑动窗口。已经发现，对于每个滑动窗口的这个颜色通道选择比考虑整个单词图像的单个颜色通道更有成果。针对基于小波变换的特征优于其他特征的多标签支持向量机的颜色通道选择，分析了五个不同的特征。我们的框架已经在不同的公开场景/视频文本图像数据集上进行了测试。对于梵文脚本，我们收集了我们自己的数据数据集。从实验结果中获得的性能是令人鼓舞的，并且显示了所提出的方法的优点。

##### URL
[https://arxiv.org/abs/1707.06810](https://arxiv.org/abs/1707.06810)

##### PDF
[https://arxiv.org/pdf/1707.06810](https://arxiv.org/pdf/1707.06810)

