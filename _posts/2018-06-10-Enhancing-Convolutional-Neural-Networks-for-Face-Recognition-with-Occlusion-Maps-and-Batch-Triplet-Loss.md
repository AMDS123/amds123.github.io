---
layout: post
title: "Enhancing Convolutional Neural Networks for Face Recognition with Occlusion Maps and Batch Triplet Loss"
date: 2018-06-10 09:42:33
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN Recognition Face_Recognition
author: Daniel S&#xe1;ez Trigueros, Li Meng, Margaret Hartnett
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the recent success of convolutional neural networks for computer vision applications, unconstrained face recognition remains a challenge. In this work, we make two contributions to the field. Firstly, we consider the problem of face recognition with partial occlusions and show how current approaches might suffer significant performance degradation when dealing with this kind of face images. We propose a simple method to find out which parts of the human face are more important to achieve a high recognition rate, and use that information during training to force a convolutional neural network to learn discriminative features from all the face regions more equally, including those that typical approaches tend to pay less attention to. We test the accuracy of the proposed method when dealing with real-life occlusions using the AR face database. Secondly, we propose a novel loss function called batch triplet loss that improves the performance of the triplet loss by adding an extra term to the loss function to cause minimisation of the standard deviation of both positive and negative scores. We show consistent improvement in the Labeled Faces in the Wild (LFW) benchmark by applying both proposed adjustments to the convolutional neural network training.

##### Abstract (translated by Google)
尽管卷积神经网络最近在计算机视觉应用方面取得了成功，但无约束的人脸识别仍然是一个挑战。在这项工作中，我们对该领域做出了两项贡献。首先，我们考虑具有部分遮挡的人脸识别问题，并说明当处理这种人脸图像时，当前的方法可能会遭受显着的性能下降。我们提出了一个简单的方法来找出人脸的哪些部分对于获得高识别率更重要，并且在训练过程中使用这些信息迫使卷积神经网络更平均地学习所有脸部区域的识别特征，包括那些典型的方法往往不太注意。当使用AR人脸数据库处理现实生活中的遮挡时，我们测试所提出的方法的准确性。其次，我们提出了一种称为批量三重损失的新损失函数，它通过对损失函数增加一个额外项来改善三重损失的表现，以使正负分数的标准偏差最小化。我们通过对卷积神经网络训练应用两种提议的调整，显示了野外标记人脸（LFW）基准的持续改进。

##### URL
[http://arxiv.org/abs/1707.07923](http://arxiv.org/abs/1707.07923)

##### PDF
[http://arxiv.org/pdf/1707.07923](http://arxiv.org/pdf/1707.07923)

