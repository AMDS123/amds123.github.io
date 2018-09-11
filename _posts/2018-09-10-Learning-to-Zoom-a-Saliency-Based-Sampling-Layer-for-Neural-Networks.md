---
layout: post
title: "Learning to Zoom: a Saliency-Based Sampling Layer for Neural Networks"
date: 2018-09-10 14:36:15
categories: arXiv_CV
tags: arXiv_CV Salient CNN Image_Classification Classification
author: Adri&#xe0; Recasens, Petr Kellnhofer, Simon Stent, Wojciech Matusik, Antonio Torralba
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a saliency-based distortion layer for convolutional neural networks that helps to improve the spatial sampling of input data for a given task. Our differentiable layer can be added as a preprocessing block to existing task networks and trained altogether in an end-to-end fashion. The effect of the layer is to efficiently estimate how to sample from the original data in order to boost task performance. For example, for an image classification task in which the original data might range in size up to several megapixels, but where the desired input images to the task network are much smaller, our layer learns how best to sample from the underlying high resolution data in a manner which preserves task-relevant information better than uniform downsampling. This has the effect of creating distorted, caricature-like intermediate images, in which idiosyncratic elements of the image that improve task performance are zoomed and exaggerated. Unlike alternative approaches such as spatial transformer networks, our proposed layer is inspired by image saliency, computed efficiently from uniformly downsampled data, and degrades gracefully to a uniform sampling strategy under uncertainty. We apply our layer to improve existing networks for the tasks of human gaze estimation and fine-grained object classification. Code for our method is available in: <a href="http://github.com/recasens/Saliency-Sampler">this http URL</a>

##### Abstract (translated by Google)
我们为卷积神经网络引入了基于显着性的失真层，有助于改善给定任务的输入数据的空间采样。我们的可区分层可以作为预处理块添加到现有任务网络中，并以端到端的方式完全训练。该层的效果是有效地估计如何从原始数据中采样以提高任务性能。例如，对于图像分类任务，其中原始数据的大小可能达到几百万像素，但是到任务网络的所需输入图像要小得多，我们的图层将学习如何最好地从底层高分辨率数据中采样。一种比统一下采样更好地保留任务相关信息的方式。这具有创建扭曲的类似漫画的中间图像的效果，其中改善任务性能的图像的特殊元素被缩放和夸大。与空间变换器网络等替代方法不同，我们提出的层受图像显着性的启发，从均匀下采样数据中有效计算，并在不确定性下优雅地降级为均匀采样策略。我们应用我们的层来改进现有网络，用于人类注视估计和细粒度对象分类的任务。我们的方法代码可在以下网址获得：<a href="http://github.com/recasens/Saliency-Sampler">此http网址</a>

##### URL
[http://arxiv.org/abs/1809.03355](http://arxiv.org/abs/1809.03355)

##### PDF
[http://arxiv.org/pdf/1809.03355](http://arxiv.org/pdf/1809.03355)

