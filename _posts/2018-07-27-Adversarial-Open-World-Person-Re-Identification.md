---
layout: post
title: "Adversarial Open-World Person Re-Identification"
date: 2018-07-27 08:15:48
categories: arXiv_CV
tags: arXiv_CV Re-identification Adversarial GAN Person_Re-identification
author: Xiang Li, Ancong Wu, Wei-Shi Zheng
mathjax: true
---

* content
{:toc}

##### Abstract
In a typical real-world application of re-id, a watch-list (gallery set) of a handful of target people (e.g. suspects) to track around a large volume of non-target people are demanded across camera views, and this is called the open-world person re-id. Different from conventional (closed-world) person re-id, a large portion of probe samples are not from target people in the open-world setting. And, it always happens that a non-target person would look similar to a target one and therefore would seriously challenge a re-id system. In this work, we introduce a deep open-world group-based person re-id model based on adversarial learning to alleviate the attack problem caused by similar non-target people. The main idea is learning to attack feature extractor on the target people by using GAN to generate very target-like images (imposters), and in the meantime the model will make the feature extractor learn to tolerate the attack by discriminative learning so as to realize group-based verification. The framework we proposed is called the adversarial open-world person re-identification, and this is realized by our Adversarial PersonNet (APN) that jointly learns a generator, a person discriminator, a target discriminator and a feature extractor, where the feature extractor and target discriminator share the same weights so as to makes the feature extractor learn to tolerate the attack by imposters for better group-based verification. While open-world person re-id is challenging, we show for the first time that the adversarial-based approach helps stabilize person re-id system under imposter attack more effectively.

##### Abstract (translated by Google)
在re-id的典型现实应用中，在摄像机视图中需要少量目标人（例如嫌疑人）的监视列表（图库集）以跟踪大量非目标人员，这是称为开放世界的人。与传统（封闭世界）人物不同，大部分探测样本不是来自开放世界环境中的目标人物。并且，总是会发生非目标人看起来与目标人类似，因此会严重挑战重新识别系统。在这项工作中，我们引入了一个基于对抗性学习的深度开放世界的基于群体的人物重新模型，以减轻由类似的非目标人群引起的攻击问题。主要思想是学习通过使用GAN生成非常类似目标的图像（冒名顶替者）来攻击目标人物上的特征提取器，同时该模型将使特征提取器学会通过判别性学习来容忍攻击，从而实现基于群组的验证。我们提出的框架被称为对抗性开放世界人员重新识别，这是由我们的对抗人员网络（APN）实现的，它共同学习生成器，人物鉴别器，目标鉴别器和特征提取器，其中特征提取器和目标鉴别器共享相同的权重，以使特征提取器学会容忍冒名顶替者的攻击，以便更好地进行基于组的验证。虽然开放世界的人物具有挑战性，但我们首次表明，基于对抗的方法有助于更有效地稳定人员重建系统。

##### URL
[http://arxiv.org/abs/1807.10482](http://arxiv.org/abs/1807.10482)

##### PDF
[http://arxiv.org/pdf/1807.10482](http://arxiv.org/pdf/1807.10482)

