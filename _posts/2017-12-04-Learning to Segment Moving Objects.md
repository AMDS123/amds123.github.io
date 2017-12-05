---
layout: post
title:  Learning to Segment Moving Objects
date:   2017-12-05 18:20:05
categories: CV
tags: CV
author: Pavel Tokmakov, Cordelia Schmid, Karteek Alahari
---

* content
{:toc}

##### Abstract
We study the problem of segmenting moving objects in unconstrained videos. Given a video, the task is to segment all the objects that exhibit independent motion in at least one frame. We formulate this as a learning problem and design our framework with three cues: (i) independent object motion between a pair of frames, which complements object recognition, (ii) object appearance, which helps to correct errors in motion estimation, and (iii) temporal consistency, which imposes additional constraints on the segmentation. The framework is a two-stream neural network with an explicit memory module. The two streams encode appearance and motion cues in a video sequence respectively, while the memory module captures the evolution of objects over time, exploiting the temporal consistency. The motion stream is a convolutional neural network trained on synthetic videos to segment independently moving objects in the optical flow field. The module to build a 'visual memory' in video, i.e., a joint representation of all the video frames, is realized with a convolutional recurrent unit learned from a small number of training video sequences. </p> <p>For every pixel in a frame of a test video, our approach assigns an object or background label based on the learned spatio-temporal features as well as the 'visual memory' specific to the video. We evaluate our method extensively on three benchmarks, DAVIS, Freiburg-Berkeley motion segmentation dataset and SegTrack. In addition, we provide an extensive ablation study to investigate both the choice of the training data and the influence of each component in the proposed framework.

##### Abstract (translated by Google)
我们研究在无约束视频中分割移动对象的问题。给定一个视频，任务是分割所有在至少一帧中展示独立运动的对象。我们将其作为一个学习问题，并用三个线索来设计我们的框架：（i）一对框架之间的独立对象运动，它补充对象识别;（ii）对象外观，这有助于纠正运动估计中的错误; ）时间一致性，这对分割施加了额外的限制。该框架是一个具有显式存储器模块的双流神经网络。两个流分别对视频序列中的外观和运动提示进行编码，而内存模块随时间捕获对象的演变，利用时间一致性。运动流是在合成视频上训练的卷积神经网络，以在光流场中分割独立移动的物体。利用从少量训练视频序列中学习的卷积递归单元来实现在视频中构建“视觉存储器”的模块，即所有视频帧的联合表示。对于测试视频帧中的每个像素，我们的方法根据学习的时空特征以及特定于视频的“视觉记忆”来分配对象或背景标签。我们在三个基准（DAVIS，Freiburg-Berkeley运动分割数据集和SegTrack）上广泛评估我们的方法。此外，我们提供广泛的消融研究来调查培训数据的选择和每个组件在拟议框架中的影响。

