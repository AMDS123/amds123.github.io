---
layout: post
title: "DeepRebirth: Accelerating Deep Neural Network Execution on Mobile Devices"
date: 2018-01-10 23:41:57
categories: arXiv_CV
tags: arXiv_CV Optimization Inference
author: Dawei Li, Xiaolong Wang, Deguang Kong
mathjax: true
---

* content
{:toc}

##### Abstract
Deploying deep neural networks on mobile devices is a challenging task. Current model compression methods such as matrix decomposition effectively reduce the deployed model size, but still cannot satisfy real-time processing requirement. This paper first discovers that the major obstacle is the excessive execution time of non-tensor layers such as pooling and normalization without tensor-like trainable parameters. This motivates us to design a novel acceleration framework: DeepRebirth through "slimming" existing consecutive and parallel non-tensor and tensor layers. The layer slimming is executed at different substructures: (a) streamline slimming by merging the consecutive non-tensor and tensor layer vertically; (b) branch slimming by merging non-tensor and tensor branches horizontally. The proposed optimization operations significantly accelerate the model execution and also greatly reduce the run-time memory cost since the slimmed model architecture contains less hidden layers. To maximally avoid accuracy loss, the parameters in new generated layers are learned with layer-wise fine-tuning based on both theoretical analysis and empirical verification. As observed in the experiment, DeepRebirth achieves more than 3x speed-up and 2.5x run-time memory saving on GoogLeNet with only 0.4% drop of top-5 accuracy on ImageNet. Furthermore, by combining with other model compression techniques, DeepRebirth offers an average of 65ms inference time on the CPU of Samsung Galaxy S6 with 86.5% top-5 accuracy, 14% faster than SqueezeNet which only has a top-5 accuracy of 80.5%.

##### Abstract (translated by Google)
在移动设备上部署深度神经网络是一项艰巨的任务。矩阵分解等当前的模型压缩方法有效地减少了部署模型的尺寸，但仍不能满足实时处理的要求。本文首先发现主要的障碍是非张量层的过度执行时间，如池化和归一化，没有张量状可训练参数。这激励我们设计一个新的加速框架：通过“瘦身”现有的连续和平行的非张量和张量层的DeepRebirth。 （a）通过垂直合并连续的非张量和张量层来使流线瘦身; （b）通过横向合并非张量和张量分支来减少分支。所提出的优化操作显着地加速了模型执行，并且由于减小的模型体系结构包含较少的隐藏层，所以也大大减少了运行时间内存成本。为了最大限度地避免精度损失，在理论分析和实证验证的基础上，通过层层微调学习新生成层的参数。正如实验中所观察到的，DeepRebirth在GoogLeNet上实现了3倍以上的加速和2.5倍的运行时间内存，在ImageNet上只有0.4％的精度下降了0.4％。此外，通过与其他模型压缩技术相结合，DeepRebirth在三星Galaxy S6的CPU上的平均推理时间为65ms，前5精度为86.5％，比SqueezeNet快了14％，前者的精度只有前者的80.5％。

##### URL
[http://arxiv.org/abs/1708.04728](http://arxiv.org/abs/1708.04728)

##### PDF
[http://arxiv.org/pdf/1708.04728](http://arxiv.org/pdf/1708.04728)

