---
layout: post
title: "Lip Movements Generation at a Glance"
date: 2018-03-29 16:07:21
categories: arXiv_CV
tags: arXiv_CV Embedding Relation
author: Lele Chen, Zhiheng Li, Ross K. Maddox, Zhiyao Duan, Chenliang Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Cross-modality generation is an emerging topic that aims to synthesize data in one modality based on information in a different modality. In this paper, we consider a task of such: given an arbitrary audio speech and one lip image of arbitrary target identity, generate synthesized lip movements of the target identity saying the speech. To perform well in this task, it inevitably requires a model to not only consider the retention of target identity, photo-realistic of synthesized images, consistency and smoothness of lip images in a sequence, but more importantly, learn the correlations between audio speech and lip movements. To solve the collective problems, we explore the best modeling of the audio-visual correlations in building and training a lip-movement generator network. Specifically, we devise a method to fuse audio and image embeddings to generate multiple lip images at once and propose a novel correlation loss to synchronize lip changes and speech changes. Our final model utilizes a combination of four losses for a comprehensive consideration in generating lip movements; it is trained in an end-to-end fashion and is robust to lip shapes, view angles and different facial characteristics. Thoughtful experiments on three datasets ranging from lab-recorded to lips in-the-wild show that our model significantly outperforms other state-of-the-art methods extended to this task.

##### Abstract (translated by Google)
生成交叉模式是一个新兴课题，旨在基于不同形式的信息以一种模式综合数据。在本文中，我们考虑这样的任务：给定任意音频语音和任意目标身份的一张嘴唇图像，产生说出该语音的目标身份的合成嘴唇移动。要在这项任务中表现良好，它不可避免地需要一个模型，不仅要考虑目标身份的保留，合成图像的照片真实感，序列中嘴唇图像的一致性和平滑性，更重要的是要学习音频语音和嘴唇动作。为了解决集体问题，我们探讨了建立和训练嘴唇移动发生器网络时视听关系的最佳建模。具体而言，我们设计了一种融合音频和图像嵌入的方法，以一次生成多个嘴唇图像，并提出了一种新颖的相关损失来同步嘴唇变化和言语变化。我们的最终模型利用四种损失的组合来综合考虑产生唇部运动;它以端到端的方式进行训练，并且对嘴唇形状，视角和不同的面部特征都很有效。对三个数据集进行周密的实验，从实验室记录到狂野中的嘴唇，都表明我们的模型明显优于其他延伸至此任务的最新方法。

##### URL
[http://arxiv.org/abs/1803.10404](http://arxiv.org/abs/1803.10404)

##### PDF
[http://arxiv.org/pdf/1803.10404](http://arxiv.org/pdf/1803.10404)

