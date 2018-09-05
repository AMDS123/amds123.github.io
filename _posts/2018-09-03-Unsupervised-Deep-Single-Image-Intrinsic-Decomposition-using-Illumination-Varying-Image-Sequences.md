---
layout: post
title: "Unsupervised Deep Single-Image Intrinsic Decomposition using Illumination-Varying Image Sequences"
date: 2018-09-03 08:41:15
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Quantitative Relation
author: Louis Lettry, Kenneth Vanhoey, Luc van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
Machine learning based Single Image Intrinsic Decomposition (SIID) methods decompose a captured scene into its albedo and shading images by using the knowledge of a large set of known and realistic ground truth decompositions. Collecting and annotating such a dataset is an approach that cannot scale to sufficient variety and realism. We free ourselves from this limitation by training on unannotated images. 
 Our method leverages the observation that two images of the same scene but with different lighting provide useful information on their intrinsic properties: by definition, albedo is invariant to lighting conditions, and cross-combining the estimated albedo of a first image with the estimated shading of a second one should lead back to the second one's input image. We transcribe this relationship into a siamese training scheme for a deep convolutional neural network that decomposes a single image into albedo and shading. The siamese setting allows us to introduce a new loss function including such cross-combinations, and to train solely on (time-lapse) images, discarding the need for any ground truth annotations. 
 As a result, our method has the good properties of i) taking advantage of the time-varying information of image sequences in the (pre-computed) training step, ii) not requiring ground truth data to train on, and iii) being able to decompose single images of unseen scenes at runtime. To demonstrate and evaluate our work, we additionally propose a new rendered dataset containing illumination-varying scenes and a set of quantitative metrics to evaluate SIID algorithms. Despite its unsupervised nature, our results compete with state of the art methods, including supervised and non data-driven methods.

##### Abstract (translated by Google)
基于机器学习的单图像内在分解（SIID）方法通过使用大量已知和现实地面真实分解的知识将捕获的场景分解为其反照率和阴影图像。收集和注释这样的数据集是一种无法扩展到足够多样性和现实性的方法。通过对未注释的图像进行培训，我们摆脱了这种限制。
 我们的方法利用观察到相同场景但具有不同光照的两个图像提供关于其内在属性的有用信息：根据定义，反照率对于光照条件是不变的，并且将第一图像的估计反照率与估计的阴影交叉组合。第二个应该回到第二个输入图像。我们将这种关系转化为一种用于深度卷积神经网络的暹罗训练方案，该网络将单个图像分解为反照率和阴影。暹罗设置允许我们引入包括这种交叉组合的新损失函数，并且仅对（延时）图像进行训练，而不需要任何地面实况注释。
 因此，我们的方法具有以下优点：i）利用（预先计算的）训练步骤中的图像序列的时变信息，ii）不需要地面实况数据训练，以及iii）能够在运行时分解看不见的场景的单个图像。为了演示和评估我们的工作，我们还提出了一个新的渲染数据集，其中包含照明变化场景和一组定量指标来评估SIID算法。尽管其无人监督，但我们的结果与最先进的方法竞争，包括监督和非数据驱动的方法。

##### URL
[http://arxiv.org/abs/1803.00805](http://arxiv.org/abs/1803.00805)

##### PDF
[http://arxiv.org/pdf/1803.00805](http://arxiv.org/pdf/1803.00805)

