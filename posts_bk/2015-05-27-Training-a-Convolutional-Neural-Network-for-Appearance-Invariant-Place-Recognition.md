---
layout: post
title: "Training a Convolutional Neural Network for Appearance-Invariant Place Recognition"
date: 2015-05-27 18:21:54
categories: arXiv_CV
tags: arXiv_CV CNN SLAM Recognition
author: Ruben Gomez-Ojeda, Manuel Lopez-Antequera, Nicolai Petkov, Javier Gonzalez-Jimenez
mathjax: true
---

* content
{:toc}

##### Abstract
Place recognition is one of the most challenging problems in computer vision, and has become a key part in mobile robotics and autonomous driving applications for performing loop closure in visual SLAM systems. Moreover, the difficulty of recognizing a revisited location increases with appearance changes caused, for instance, by weather or illumination variations, which hinders the long-term application of such algorithms in real environments. In this paper we present a convolutional neural network (CNN), trained for the first time with the purpose of recognizing revisited locations under severe appearance changes, which maps images to a low dimensional space where Euclidean distances represent place dissimilarity. In order for the network to learn the desired invariances, we train it with triplets of images selected from datasets which present a challenging variability in visual appearance. The triplets are selected in such way that two samples are from the same location and the third one is taken from a different place. We validate our system through extensive experimentation, where we demonstrate better performance than state-of-art algorithms in a number of popular datasets.

##### Abstract (translated by Google)
位置识别是计算机视觉中最具挑战性的问题之一，并已成为移动机器人技术和自主驾驶应用在视觉SLAM系统中执行闭环的关键部分。此外，识别重访地点的难度随着例如天气或照明变化引起的外观变化而增加，这妨碍了这种算法在实际环境中的长期应用。在本文中，我们提出了一个第一次训练的卷积神经网络（CNN），目的是在严重的外观变化下识别重新定位的位置，将图像映射到一个低维空间，其中欧几里德距离代表位置的不相似性。为了使网络学习所需的不变性，我们使用从数据集中选择的三重图像进行训练，这在视觉外观上呈现出具有挑战性的变化。三联体的选择方式是两个样本来自同一地点，第三个样本来自不同的地方。我们通过大量的实验来验证我们的系统，在那里我们比许多流行的数据集中的最先进的算法表现出更好的性能。

##### URL
[https://arxiv.org/abs/1505.07428](https://arxiv.org/abs/1505.07428)

##### PDF
[https://arxiv.org/pdf/1505.07428](https://arxiv.org/pdf/1505.07428)

