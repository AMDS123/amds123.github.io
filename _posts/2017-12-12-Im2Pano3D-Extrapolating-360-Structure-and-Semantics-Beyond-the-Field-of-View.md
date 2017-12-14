---
layout: post
title: "Im2Pano3D: Extrapolating 360 Structure and Semantics Beyond the Field of View"
date: 2017-12-12 23:47:53
categories: arXiv_CV
tags: arXiv_CV Face CNN Prediction
author: Shuran Song, Andy Zeng, Angel X. Chang, Manolis Savva, Silvio Savarese, Thomas Funkhouser
mathjax: true
---

* content
{:toc}

##### Abstract
We present Im2Pano3D, a convolutional neural network that generates a dense prediction of 3D structure and a probability distribution of semantic labels for a full 360 panoramic view of an indoor scene when given only a partial observation (&lt;= 50%) in the form of an RGB-D image. To make this possible, Im2Pano3D leverages strong contextual priors learned from large-scale synthetic and real-world indoor scenes. To ease the prediction of 3D structure, we propose to parameterize 3D surfaces with their plane equations and train the model to predict these parameters directly. To provide meaningful training supervision, we use multiple loss functions that consider both pixel level accuracy and global context consistency. Experiments demon- strate that Im2Pano3D is able to predict the semantics and 3D structure of the unobserved scene with more than 56% pixel accuracy and less than 0.52m average distance error, which is significantly better than alternative approaches.

##### Abstract (translated by Google)
我们提出了Im2Pano3D，一种卷积神经网络，当仅给出部分观察（<= 50％）的形式时，该卷积神经网络产生室内场景的完整360全景的3D结构的密集预测和语义标签的概率分布一个RGB-D图像。为了实现这一点，Im2Pano3D利用了从大规模合成和现实世界室内场景中学习的强大的前后关系。为了简化三维结构的预测，我们建议用三维曲面的平面方程参数化三维曲面，并训练模型直接预测这些参数。为了提供有意义的培训监督，我们使用考虑像素级精度和全局上下文一致性的多个损失函数。实验表明，Im2Pano3D能够预测未观测场景的语义和三维结构，像素精度高于56％，平均距离误差小于0.52m，明显优于其他方法。

##### URL
[http://arxiv.org/abs/1712.04569](http://arxiv.org/abs/1712.04569)

##### PDF
[http://arxiv.org/pdf/1712.04569](http://arxiv.org/pdf/1712.04569)

