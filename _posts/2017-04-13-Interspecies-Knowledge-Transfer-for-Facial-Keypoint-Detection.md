---
layout: post
title: "Interspecies Knowledge Transfer for Facial Keypoint Detection"
date: 2017-04-13 07:52:21
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Detection
author: Maheen Rashid, Xiuye Gu, Yong Jae Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for localizing facial keypoints on animals by transferring knowledge gained from human faces. Instead of directly finetuning a network trained to detect keypoints on human faces to animal faces (which is sub-optimal since human and animal faces can look quite different), we propose to first adapt the animal images to the pre-trained human detection network by correcting for the differences in animal and human face shape. We first find the nearest human neighbors for each animal image using an unsupervised shape matching method. We use these matches to train a thin plate spline warping network to warp each animal face to look more human-like. The warping network is then jointly finetuned with a pre-trained human facial keypoint detection network using an animal dataset. We demonstrate state-of-the-art results on both horse and sheep facial keypoint detection, and significant improvement over simple finetuning, especially when training data is scarce. Additionally, we present a new dataset with 3717 images with horse face and facial keypoint annotations.

##### Abstract (translated by Google)
我们提出了一种通过传递从人脸上获得的知识来定位动物脸部关键点的方法。我们建议首先将动物图像调整到预先训练好的人体检测网络，而不是直接对训练好的网络进行微调，以检测动物人脸上的关键点（这是次优的，因为人类和动物的人脸看起来可能完全不同）纠正动物和人脸形状的差异。我们首先使用无监督的形状匹配方法为每个动物图像找到最近的人邻居。我们使用这些匹配来训练一个薄板样条翘曲网络来扭曲每个动物的脸，使之看起来更像人。然后使用动物数据集与预先训练的人脸面部关键点检测网络共同调整变形网络。我们在马和绵羊面部关键点检测方面展示了最先进的结果，并且相对于简单的微调来说，尤其是在训练数据稀缺的情况下更是如此。此外，我们提出了一个新的数据集与3717图像与马脸和面部关键点注释。

##### URL
[https://arxiv.org/abs/1704.04023](https://arxiv.org/abs/1704.04023)

##### PDF
[https://arxiv.org/pdf/1704.04023](https://arxiv.org/pdf/1704.04023)

