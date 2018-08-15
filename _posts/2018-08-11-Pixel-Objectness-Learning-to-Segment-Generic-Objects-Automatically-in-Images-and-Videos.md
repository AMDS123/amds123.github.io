---
layout: post
title: "Pixel Objectness: Learning to Segment Generic Objects Automatically in Images and Videos"
date: 2018-08-11 21:53:22
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Segmentation CNN Prediction
author: Bo Xiong, Suyog Dutt Jain, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an end-to-end learning framework for segmenting generic objects in both images and videos. Given a novel image or video, our approach produces a pixel-level mask for all "object-like" regions---even for object categories never seen during training. We formulate the task as a structured prediction problem of assigning an object/background label to each pixel, implemented using a deep fully convolutional network. When applied to a video, our model further incorporates a motion stream, and the network learns to combine both appearance and motion and attempts to extract all prominent objects whether they are moving or not. Beyond the core model, a second contribution of our approach is how it leverages varying strengths of training annotations. Pixel-level annotations are quite difficult to obtain, yet crucial for training a deep network approach for segmentation. Thus we propose ways to exploit weakly labeled data for learning dense foreground segmentation. For images, we show the value in mixing object category examples with image-level labels together with relatively few images with boundary-level annotations. For video, we show how to bootstrap weakly annotated videos together with the network trained for image segmentation. Through experiments on multiple challenging image and video segmentation benchmarks, our method offers consistently strong results and improves the state-of-the-art for fully automatic segmentation of generic (unseen) objects. In addition, we demonstrate how our approach benefits image retrieval and image retargeting, both of which flourish when given our high-quality foreground maps. Code, models, and videos are at:<a href="http://vision.cs.utexas.edu/projects/pixelobjectness/">this http URL</a>

##### Abstract (translated by Google)
我们提出了一种端到端的学习框架，用于分割图像和视频中的通用对象。给定一个新颖的图像或视频，我们的方法为所有“类对象”区域生成像素级掩码 - 即使是在训练期间从未见过的对象类别。我们将任务表示为向每个像素分配对象/背景标签的结构化预测问题，使用深度完全卷积网络实现。当应用于视频时，我们的模型进一步包含运动流，并且网络学习将外观和运动结合起来并尝试提取所有突出的对象，无论它们是否在移动。除了核心模型之外，我们的方法的第二个贡献是它如何利用培训注释的不同优势。像素级注释很难获得，但对于训练深度网络分割方法至关重要。因此，我们提出了利用弱标记数据来学习密集前景分割的方法。对于图像，我们展示了将对象类别示例与图像级标签混合在一起的值以及具有边界级注释的相对较少的图像。对于视频，我们将展示如何与经过训练的网络图像分割一起引导弱带注释的视频。通过对多个具有挑战性的图像和视频分割基准的实验，我们的方法提供了始终如一的强大结果，并改进了通用（看不见）对象的全自动分割的最新技术。此外，我们还展示了我们的方法如何有利于图像检索和图像重定向，当我们获得高质量的前景图时，这两种方法都会蓬勃发展。代码，模型和视频位于：<a href="http://vision.cs.utexas.edu/projects/pixelobjectness/">此http网址</a>

##### URL
[http://arxiv.org/abs/1808.04702](http://arxiv.org/abs/1808.04702)

##### PDF
[http://arxiv.org/pdf/1808.04702](http://arxiv.org/pdf/1808.04702)

