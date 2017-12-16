---
layout: post
title: "Learning Human Pose Models from Synthesized Data for Robust RGB-D Action Recognition"
date: 2017-07-04 06:18:34
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Action_Recognition Classification Recognition
author: Jian Liu, Ajmal Mian
mathjax: true
---

* content
{:toc}

##### Abstract
We propose Human Pose Models that represent RGB and depth images of human poses independent of clothing textures, backgrounds, lighting conditions, body shapes and camera viewpoints. Learning such universal models requires training images where all factors are varied for every human pose. Capturing such data is prohibitively expensive. Therefore, we develop a framework for synthesizing the training data. First, we learn representative human poses from a large corpus of real motion captured human skeleton data. Next, we fit synthetic 3D humans with different body shapes to each pose and render each from 180 camera viewpoints while randomly varying the clothing textures, background and lighting. Generative Adversarial Networks are employed to minimize the gap between synthetic and real image distributions. CNN models are then learned that transfer human poses to a shared high-level invariant space. The learned CNN models are then used as invariant feature extractors from real RGB and depth frames of human action videos and the temporal variations are modelled by Fourier Temporal Pyramid. Finally, linear SVM is used for classification. Experiments on three benchmark cross-view human action datasets show that our algorithm outperforms existing methods by significant margins for RGB only and RGB-D action recognition.

##### Abstract (translated by Google)
我们建议人体姿态模型代表人体姿态的RGB和深度图像，与服装的纹理，背景，照明条件，身体形状和相机视点无关。学习这样的通用模型需要对每个人体姿势的所有因素进行变化的训练图像。捕获这样的数据是非常昂贵的。因此，我们开发了一个综合训练数据的框架。首先，我们从真实运动的大型语料库中学习人类的代表人体姿态数据。接下来，我们将适合不同人体形状的合成3D人物放置在每个姿势上，并在随机改变服装的纹理，背景和灯光的同时渲染180个相机视点。生成敌对网络被用来最小化合成图像和真实图像分布之间的差距。然后学习CNN模型，将人的姿势转移到共享的高层不变空间。然后将学习的CNN模型用作来自真实RGB和人类活动视频的深度帧的不变特征提取器，并且时间变化由傅立叶时间金字塔来建模。最后，线性SVM用于分类。对三个基准交叉视图人类行动数据集的实验表明，我们的算法比仅有RGB和RGB-D行为识别的显着幅度优于现有方法。

##### URL
[https://arxiv.org/abs/1707.00823](https://arxiv.org/abs/1707.00823)

##### PDF
[https://arxiv.org/pdf/1707.00823](https://arxiv.org/pdf/1707.00823)

