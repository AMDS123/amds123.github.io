---
layout: post
title: "Asymmetric Totally-corrective Boosting for Real-time Object Detection"
date: 2010-09-16 02:45:59
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face_Detection Detection
author: Peng Wang, Chunhua Shen, Nick Barnes, Hong Zheng, Zhang Ren
mathjax: true
---

* content
{:toc}

##### Abstract
Real-time object detection is one of the core problems in computer vision. The cascade boosting framework proposed by Viola and Jones has become the standard for this problem. In this framework, the learning goal for each node is asymmetric, which is required to achieve a high detection rate and a moderate false positive rate. We develop new boosting algorithms to address this asymmetric learning problem. We show that our methods explicitly optimize asymmetric loss objectives in a totally corrective fashion. The methods are totally corrective in the sense that the coefficients of all selected weak classifiers are updated at each iteration. In contract, conventional boosting like AdaBoost is stage-wise in that only the current weak classifier's coefficient is updated. At the heart of the totally corrective boosting is the column generation technique. Experiments on face detection show that our methods outperform the state-of-the-art asymmetric boosting methods.

##### Abstract (translated by Google)
实时对象检测是计算机视觉中的核心问题之一。 Viola和Jones提出的级联增强框架已经成为这个问题的标准。在这个框架下，每个节点的学习目标是不对称的，这是实现高检测率和中等误报率所需要的。我们开发新的提升算法来解决这个不对称的学习问题。我们表明，我们的方法显式优化非完全纠正方式的非对称损失目标。从所有选择的弱分类器的系数在每次迭代更新的意义上来说，这些方法是完全纠正的。在合约中，像AdaBoost这样的传统提升是阶段性的，因为只有当前弱分类器的系数被更新。在完全纠正助推的核心是列生成技术。人脸检测实验表明，我们的方法胜过了最先进的非对称增强方法。

##### URL
[https://arxiv.org/abs/1009.3078](https://arxiv.org/abs/1009.3078)

