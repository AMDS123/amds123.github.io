---
layout: post
title: "Deep Video-Based Performance Cloning"
date: 2018-08-21 11:20:49
categories: arXiv_CV
tags: arXiv_CV
author: Kfir Aberman, Mingyi Shi, Jing Liao, Dani Lischinski, Baoquan Chen, Daniel Cohen-Or
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new video-based performance cloning technique. After training a deep generative network using a reference video capturing the appearance and dynamics of a target actor, we are able to generate videos where this actor reenacts other performances. All of the training data and the driving performances are provided as ordinary video segments, without motion capture or depth information. Our generative model is realized as a deep neural network with two branches, both of which train the same space-time conditional generator, using shared weights. One branch, responsible for learning to generate the appearance of the target actor in various poses, uses \emph{paired} training data, self-generated from the reference video. The second branch uses unpaired data to improve generation of temporally coherent video renditions of unseen pose sequences. We demonstrate a variety of promising results, where our method is able to generate temporally coherent videos, for challenging scenarios where the reference and driving videos consist of very different dance performances. Supplementary video: https://youtu.be/JpwsEeqNhhA.

##### Abstract (translated by Google)
我们提出了一种新的基于视频的性能克隆技术。在使用捕获目标演员的外观和动态的参考视频训练深度生成网络之后，我们能够生成该演员重演其他演出的视频。所有训练数据和驾驶表现都作为普通视频片段提供，没有动作捕捉或深度信息。我们的生成模型被实现为具有两个分支的深度神经网络，两个分支都使用共享权重训练相同的空时条件生成器。负责学习以各种姿势生成目标演员外观的一个分支使用从参考视频自生成的\ emph {配对}训练数据。第二分支使用不成对数据来改进看不见的姿势序列的时间相干视频再现的生成。我们展示了各种有希望的结果，我们的方法能够生成时间上连贯的视频，适用于参考和驾驶视频由非常不同的舞蹈表演组成的挑战性场景。补充视频：https：//youtu.be/JpwsEeqNhhA。

##### URL
[http://arxiv.org/abs/1808.06847](http://arxiv.org/abs/1808.06847)

##### PDF
[http://arxiv.org/pdf/1808.06847](http://arxiv.org/pdf/1808.06847)

