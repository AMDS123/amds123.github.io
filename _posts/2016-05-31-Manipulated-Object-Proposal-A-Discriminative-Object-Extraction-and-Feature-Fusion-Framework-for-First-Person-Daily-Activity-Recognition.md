---
layout: post
title: "Manipulated Object Proposal: A Discriminative Object Extraction and Feature Fusion Framework for First-Person Daily Activity Recognition"
date: 2016-05-31 12:26:08
categories: arXiv_CV
tags: arXiv_CV Object_Detection Action_Recognition CNN Detection Recognition
author: Changzhi Luo, Bingbing Ni, Jun Yuan, Jianfeng Wang, Shuicheng Yan, Meng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Detecting and recognizing objects interacting with humans lie in the center of first-person (egocentric) daily activity recognition. However, due to noisy camera motion and frequent changes in viewpoint and scale, most of the previous egocentric action recognition methods fail to capture and model highly discriminative object features. In this work, we propose a novel pipeline for first-person daily activity recognition, aiming at more discriminative object feature representation and object-motion feature fusion. Our object feature extraction and representation pipeline is inspired by the recent success of object hypotheses and deep convolutional neural network based detection frameworks. Our key contribution is a simple yet effective manipulated object proposal generation scheme. This scheme leverages motion cues such as motion boundary and motion magnitude (in contrast, camera motion is usually considered as "noise" for most previous methods) to generate a more compact and discriminative set of object proposals, which are more closely related to the objects which are being manipulated. Then, we learn more discriminative object detectors from these manipulated object proposals based on region-based convolutional neural network (R-CNN). Meanwhile, we develop a network based feature fusion scheme which better combines object and motion features. We show in experiments that the proposed framework significantly outperforms the state-of-the-art recognition performance on a challenging first-person daily activity benchmark.

##### Abstract (translated by Google)
检测和识别与人类交互的物体是第一人称（以自我为中心）日常活动识别的中心。然而，由于摄像机运动噪声较大，观察点和比例尺频繁变化，以前大多数以自我为中心的动作识别方法都无法捕获和建模高度区分性的物体特征。在这项工作中，我们提出了一种用于第一人称日常活动识别的新型流水线，旨在更加区分对象特征表示和对象运动特征融合。我们的对象特征提取和表示流水线的灵感来自最近成功的对象假设和基于深度卷积神经网络的检测框架。我们的主要贡献是一个简单而有效的操纵对象建议生成方案。该方案利用诸如运动边界和运动幅度之类的运动线索（相反，对于大多数先前的方法，相机运动通常被认为是“噪声”）以生成更紧凑和有区别的对象提议集，其与对象更紧密相关正在被操纵。然后，基于区域卷积神经网络（R-CNN），从这些操作对象提议中学习更多的判别性物体检测器。同时，我们开发了一个更好地结合对象和运动特征的基于网络的特征融合方案。我们在实验中表明，提出的框架明显优于具有挑战性的第一人称日常活动基准的最先进的识别性能。

##### URL
[https://arxiv.org/abs/1509.00651](https://arxiv.org/abs/1509.00651)

##### PDF
[https://arxiv.org/e-print/1509.00651](https://arxiv.org/e-print/1509.00651)

