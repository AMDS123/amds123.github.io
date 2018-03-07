---
layout: post
title: "2^B3^C: 2 Box 3 Crop of Facial Image for Gender Classification with Convolutional Networks"
date: 2018-03-05 11:25:14
categories: arXiv_CV
tags: arXiv_CV Face CNN Image_Classification Classification Deep_Learning Prediction
author: Vandit Gajjar
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we tackle the classification of gender in facial images with deep learning. Our convolutional neural networks (CNN) use the VGG-16 architecture [1] and are pretrained on ImageNet for image classification. Our proposed method (2^B3^C) first detects the face in the facial image, increases the margin of a detected face by 50%, cropping the face with two boxes three crop schemes (Left, Middle, and Right crop) and extracts the CNN predictions on the cropped schemes. The CNNs of our method is fine-tuned on the Adience and LFW with gender annotations. We show the effectiveness of our method by achieving 90.8% classification on Adience and achieving competitive 95.3% classification accuracy on LFW dataset. In addition, to check the true ability of our method, our gender classification system has a frame rate of 7-10 fps (frames per seconds) on a GPU considering real-time scenarios.

##### Abstract (translated by Google)
在本文中，我们深入学习了面部图像中的性别分类问题。我们的卷积神经网络（CNN）使用VGG-16架构[1]，并在ImageNet上预训练图像分类。我们提出的方法（2 ^ B3 ^ C）首先检测面部图像中的人脸，将检测到的人脸的边缘增加50％，用两个盒子裁剪三个作物方案（左，中，右作物）和提取物CNN对裁剪方案的预测。我们方法的CNN在Adience和LFW上用性别注释进行了微调。我们通过对Adience实现90.8％的分类并在LFW数据集上实现具有竞争力的95.3％分类准确性来展示我们方法的有效性。此外，为了检查我们方法的真实能力，我们的性别分类系统在GPU上考虑实时情况下的帧速率为7-10帧/秒（帧/秒）。

##### URL
[http://arxiv.org/abs/1803.02181](http://arxiv.org/abs/1803.02181)

##### PDF
[http://arxiv.org/pdf/1803.02181](http://arxiv.org/pdf/1803.02181)

