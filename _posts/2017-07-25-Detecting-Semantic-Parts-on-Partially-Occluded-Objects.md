---
layout: post
title: "Detecting Semantic Parts on Partially Occluded Objects"
date: 2017-07-25 05:54:01
categories: arXiv_CV
tags: arXiv_CV Detection
author: Jianyu Wang, Cihang Xie, Zhishuai Zhang, Jun Zhu, Lingxi Xie, Alan Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the task of detecting semantic parts on partially occluded objects. We consider a scenario where the model is trained using non-occluded images but tested on occluded images. The motivation is that there are infinite number of occlusion patterns in real world, which cannot be fully covered in the training data. So the models should be inherently robust and adaptive to occlusions instead of fitting / learning the occlusion patterns in the training data. Our approach detects semantic parts by accumulating the confidence of local visual cues. Specifically, the method uses a simple voting method, based on log-likelihood ratio tests and spatial constraints, to combine the evidence of local cues. These cues are called visual concepts, which are derived by clustering the internal states of deep networks. We evaluate our voting scheme on the VehicleSemanticPart dataset with dense part annotations. We randomly place two, three or four irrelevant objects onto the target object to generate testing images with various occlusions. Experiments show that our algorithm outperforms several competitors in semantic part detection when occlusions are present.

##### Abstract (translated by Google)
在本文中，我们解决检测部分遮挡物体上的语义部分的任务。我们考虑一个场景，其中模型使用非遮挡图像进行训练，但在遮挡图像上进行测试。其动机是在现实世界中存在无数的遮挡模式，在训练数据中不能完全覆盖遮挡模式。所以模型应该是固有的鲁棒性和适应性的遮挡，而不是在训练数据中拟合/学习遮挡模式。我们的方法通过累积局部视觉线索的信心来检测语义部分。具体而言，该方法使用基于对数似然比检验和空间约束的简单投票方法来结合局部线索的证据。这些线索被称为视觉概念，它是通过对深度网络的内部状态进行聚类而得到的。我们使用密集部分注释评估VehicleSemanticPart数据集上的投票方案。我们随机地将2,3,4个不相关的物体放置在目标物体上，以产生具有各种遮挡的测试图像。实验表明，当出现遮挡时，我们的算法在语义部分检测方面胜过了几个竞争者。

##### URL
[https://arxiv.org/abs/1707.07819](https://arxiv.org/abs/1707.07819)

