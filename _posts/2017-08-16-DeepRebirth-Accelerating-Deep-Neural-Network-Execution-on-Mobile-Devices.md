---
layout: post
title: "DeepRebirth: Accelerating Deep Neural Network Execution on Mobile Devices"
date: 2017-08-16 00:45:22
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Dawei Li, Xiaolong Wang, Deguang Kong
mathjax: true
---

* content
{:toc}

##### Abstract
Deploying deep neural networks on mobile devices is a challenging task due to computation complexity and memory intensity. Current model reduction methods (e.g., matrix approximation using SVD) cannot satisfy real-time processing requirement. This paper first discovers that the major obstacle is the excessive execution time of non-tensor layers (with tensor-like parameters) such as pooling and normalization. This motivates us to design a novel acceleration framework: DeepRebirth through "slimming" existing consecutive and parallel non-tensor and tensor layers. The layer slimming is executed at different substructures: (a) streamline slimming by merging the consecutive non-tensor and tensor layer vertically; (b) branch slimming by merging non-tensor and tensor branches horizontally. These different optimization operations accelerate the model execution and reduce the run-time memory cost significantly. To maximally avoid accuracy loss, the parameters in new generated layers are learned with layer-wise fine-tuning based on both theoretical analysis and empirical verification. As observed in the experiment, DeepRebirth achieves 3x-5x speed-up and energy saving on GoogLeNet with only 0.4% accuracy drop on top-5 categorization in ImageNet. Further, by combining with other model compression techniques, DeepRebirth offers an average of 65ms model forwarding time on a single image using Samsung Galaxy S6 with 86.54% top-5 accuracy with 2.5x run-time memory saving.

##### Abstract (translated by Google)
在移动设备上部署深度神经网络是一个具有挑战性的任务，由于计算复杂度和记忆强度。当前的模型减少方法（例如，使用SVD的矩阵逼近）不能满足实时处理要求。本文首先发现主要的障碍是非张量层（具有张量状参数）的执行时间过长，如池化和归一化。这激励我们设计一个新的加速框架：通过“瘦身”现有的连续和平行的非张量和张量层的DeepRebirth。 （a）通过垂直合并连续的非张量和张量层来使流线瘦身; （b）通过横向合并非张量和张量分支来减少分支。这些不同的优化操作可加速模型执行，并显着降低运行时内存成本。为了最大限度地避免精度损失，在理论分析和实证验证的基础上，通过层层微调学习新生成层的参数。正如实验中所观察到的，DeepRebirth在GoogLeNet上实现了3x-5x的加速和节能，在ImageNet的前5分类中精度仅下降了0.4％。此外，通过与其他模型压缩技术相结合，DeepRebirth使用三星Galaxy S6平均在单个图像上提供65ms的模型转发时间，前者的准确率为86.54％，节省2.5倍的运行时间。

##### URL
[https://arxiv.org/abs/1708.04728](https://arxiv.org/abs/1708.04728)

##### PDF
[https://arxiv.org/pdf/1708.04728](https://arxiv.org/pdf/1708.04728)

