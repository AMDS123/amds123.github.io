---
layout: post
title: "Cross Pixel Optical Flow Similarity for Self-Supervised Learning"
date: 2018-07-15 23:48:59
categories: arXiv_CV
tags: arXiv_CV Image_Caption Segmentation Embedding CNN Image_Classification Classification Prediction Detection
author: Aravindh Mahendran, James Thewlis, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method for learning convolutional neural image representations without manual supervision. We use motion cues in the form of optical flow, to supervise representations of static images. The obvious approach of training a network to predict flow from a single image can be needlessly difficult due to intrinsic ambiguities in this prediction task. We instead propose a much simpler learning goal: embed pixels such that the similarity between their embeddings matches that between their optical flow vectors. At test time, the learned deep network can be used without access to video or flow information and transferred to tasks such as image classification, detection, and segmentation. Our method, which significantly simplifies previous attempts at using motion for self-supervision, achieves state-of-the-art results in self-supervision using motion cues, competitive results for self-supervision in general, and is overall state of the art in self-supervised pretraining for semantic image segmentation, as demonstrated on standard benchmarks.

##### Abstract (translated by Google)
我们提出了一种新的学习卷积神经图像表示的方法，无需人工监督。我们以光流的形式使用运动提示来监督静态图像的表示。由于该预测任务中的内在模糊性，训练网络来预测来自单个图像的流的显而易见的方法可能是不必要的困难。相反，我们提出了一个更简单的学习目标：嵌入像素使得它们的嵌入之间的相似性与它们的光流向量之间的相似性相匹配。在测试时，可以使用学习的深度网络而无需访问视频或流信息，并将其传送到诸如图像分类，检测和分段的任务。我们的方法显着简化了以前使用运动进行自我监督的尝试，使用运动线索实现了最先进的自我监督结果，一般的自我监督的竞争结果，并且是整体的现有技术。用于语义图像分割的自我监督预训练，如标准基准所示。

##### URL
[http://arxiv.org/abs/1807.05636](http://arxiv.org/abs/1807.05636)

##### PDF
[http://arxiv.org/pdf/1807.05636](http://arxiv.org/pdf/1807.05636)

