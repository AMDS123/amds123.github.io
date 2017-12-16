---
layout: post
title: "Enhancing Convolutional Neural Networks for Face Recognition with Occlusion Maps and Batch Triplet Loss"
date: 2017-07-25 11:35:18
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN Recognition Face_Recognition
author: Daniel Sáez Trigueros, Li Meng, Margaret Hartnett
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the recent success of convolutional neural networks for computer vision applications, unconstrained face recognition remains a challenge. In this work, we make two contributions to the field. Firstly, we consider the problem of face recognition with partial occlusions and show how current approaches might suffer significant performance degradation when dealing with this kind of face images. We propose a simple method to find out which parts of the human face are more important to achieve a high recognition rate, and use that information during training to force a convolutional neural network to learn discriminative features from all the face regions more equally, including those that typical approaches tend to pay less attention to. We test the accuracy of the proposed method when dealing with real-life occlusions using the AR face database. Secondly, we propose a novel loss function called batch triplet loss that improves the performance of the triplet loss by adding an extra term to the loss function to cause minimisation of the standard deviation of both positive and negative scores. We show consistent improvement in the Labeled Faces in the Wild (LFW) benchmark by combining both proposed adjustments to the convolutional neural network training.

##### Abstract (translated by Google)
尽管卷积神经网络最近在计算机视觉应用方面取得了成功，但无约束的人脸识别仍然是一个挑战。在这项工作中，我们对这个领域做出了两个贡献。首先，我们考虑带有部分遮挡的人脸识别问题，并说明当前的方法在处理这种人脸图像时如何可能遭受显着的性能下降。我们提出了一个简单的方法来找出人脸的哪些部分更重要，以获得高识别率，并在训练期间使用这些信息迫使卷积神经网络更平等地学习所有脸部区域的判别特征，包括那些典型的方法往往不那么重视。当使用AR人脸数据库处理现实生活中的遮挡时，我们测试所提出的方法的准确性。其次，我们提出了一种新的损失函数，称为批量三重损失，通过对损失函数增加一个额外的项来改善三重损失的表现，使得正负分数的标准偏差最小化。我们通过结合对卷积神经网络训练的所提出的调整来显示在标记的野生面部（LFW）基准中的持续改进。

##### URL
[https://arxiv.org/abs/1707.07923](https://arxiv.org/abs/1707.07923)

##### PDF
[https://arxiv.org/pdf/1707.07923](https://arxiv.org/pdf/1707.07923)

