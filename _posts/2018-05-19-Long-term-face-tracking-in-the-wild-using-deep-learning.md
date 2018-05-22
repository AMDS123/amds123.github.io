---
layout: post
title: "Long-term face tracking in the wild using deep learning"
date: 2018-05-19 20:00:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Tracking CNN Deep_Learning Detection Face_Detection
author: Kunlei Zhang, Elaheh Rashedi, Elaheh Barati, Xue-wen Chen
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates long-term face tracking of a specific person given his/her face image in a single frame as a query in a video stream. Through taking advantage of pre-trained deep learning models on big data, a novel system is developed for accurate video face tracking in the unconstrained environments depicting various people and objects moving in and out of the frame. In the proposed system, we present a detection-verification-tracking method (dubbed as 'DVT') which accomplishes the long-term face tracking task through the collaboration of face detection, face verification, and (short-term) face tracking. An offline trained detector based on cascaded convolutional neural networks localizes all faces appeared in the frames, and an offline trained face verifier based on deep convolutional neural networks and similarity metric learning decides if any face or which face corresponds to the queried person. An online trained tracker follows the face from frame to frame. When validated on a sitcom episode and a TV show, the DVT method outperforms tracking-learning-detection (TLD) and face-TLD in terms of recall and precision. The proposed system is also tested on many other types of videos and shows very promising results.

##### Abstract (translated by Google)
本文调查了在特定人员的长时间脸部跟踪中，作为视频流中的查询，在单个帧中给予他/她的脸部图像。通过利用预先训练好的大数据深度学习模型，开发了一种新颖的系统，用于在不受限制的环境中进行准确的视频人脸跟踪，描绘了进出框架的各种人物和物体。在所提出的系统中，我们提出了一种通过人脸检测，人脸验证和（短期）人脸跟踪协作来完成长期人脸跟踪任务的检测 - 验证跟踪方法（称为“DVT”）。基于级联卷积神经网络的离线训练检测器对出现在帧中的所有面进行局部化，并且基于深度卷积神经网络和相似性度量学习的离线训练的面部检验器确定是否有任何面部或哪个面部与被查询人相对应。一个在线训练的追踪者从一帧到另一帧地追踪脸部。在情景喜剧和电视节目中进行验证后，DVT方法在回忆和精确度方面优于跟踪学习检测（TLD）和面部顶级域名（TLD）。所提出的系统也在许多其他类型的视频上进行测试，并显示出非常有希望的结果。

##### URL
[https://arxiv.org/abs/1805.07646](https://arxiv.org/abs/1805.07646)

##### PDF
[https://arxiv.org/pdf/1805.07646](https://arxiv.org/pdf/1805.07646)

