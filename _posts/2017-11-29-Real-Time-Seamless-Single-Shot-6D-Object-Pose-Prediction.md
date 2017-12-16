---
layout: post
title: "Real-Time Seamless Single Shot 6D Object Pose Prediction"
date: 2017-11-29 16:23:49
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Prediction
author: Bugra Tekin, Sudipta N. Sinha, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a single-shot approach for simultaneously detecting an object in an RGB image and predicting its 6D pose without requiring multiple stages or having to examine multiple hypotheses. Unlike a recently proposed single-shot technique for this task (Kehl et al., ICCV'17) that only predicts an approximate 6D pose that must then be refined, ours is accurate enough not to require additional post-processing. As a result, it is much faster - 50 fps on a Titan X (Pascal) GPU - and more suitable for real-time processing. The key component of our method is a new CNN architecture inspired by the YOLO network design that directly predicts the 2D image locations of the projected vertices of the object's 3D bounding box. The object's 6D pose is then estimated using a PnP algorithm. For single object and multiple object pose estimation on the LINEMOD and OCCLUSION datasets, our approach substantially outperforms other recent CNN-based approaches when they are all used without post-processing. During post-processing, a pose refinement step can be used to boost the accuracy of the existing methods, but at 10 fps or less, they are much slower than our method.

##### Abstract (translated by Google)
我们提出了一种同步检测RGB图像中的对象的单次方法，并且预测其6D姿态，而不需要多个阶段或者必须检查多个假设。与最近提出的这项任务的单发技术（Kehl等人，ICCV'17）不同，后者只能预测近似的6D姿态，而后者必须进行细化，而我们的准确性不需要额外的后处理。因此，速度要快得多 - 在Titan X（Pascal）GPU上可以达到50 fps，而且更适合实时处理。我们方法的关键部分是受YOLO网络设计启发的新的CNN架构，它直接预测对象的3D边界框的投影顶点的2D图像位置。然后使用PnP算法估计物体的6D姿态。对于LINEMOD和OCCLUSION数据集上的单个对象和多个对象姿态估计，当我们的方法全部使用而没有后处理时，我们的方法基本上胜过了其他基于CNN的方法。在后期处理过程中，可以使用姿态细化步骤来提高现有方法的精度，但是在10 fps或更小时，它们比我们的方法慢得多。

##### URL
[https://arxiv.org/abs/1711.08848](https://arxiv.org/abs/1711.08848)

##### PDF
[https://arxiv.org/pdf/1711.08848](https://arxiv.org/pdf/1711.08848)

