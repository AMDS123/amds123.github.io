---
layout: post
title: "Weakly-Supervised Convolutional Neural Networks for Multimodal Image Registration"
date: 2018-07-09 19:53:16
categories: arXiv_AI
tags: arXiv_AI GAN CNN Inference
author: Yipeng Hu, Marc Modat, Eli Gibson, Wenqi Li, Nooshin Ghavami, Ester Bonmati, Guotai Wang, Steven Bandula, Caroline M. Moore, Mark Emberton, S&#xe9;bastien Ourselin, J. Alison Noble, Dean C. Barratt, Tom Vercauteren
mathjax: true
---

* content
{:toc}

##### Abstract
One of the fundamental challenges in supervised learning for multimodal image registration is the lack of ground-truth for voxel-level spatial correspondence. This work describes a method to infer voxel-level transformation from higher-level correspondence information contained in anatomical labels. We argue that such labels are more reliable and practical to obtain for reference sets of image pairs than voxel-level correspondence. Typical anatomical labels of interest may include solid organs, vessels, ducts, structure boundaries and other subject-specific ad hoc landmarks. The proposed end-to-end convolutional neural network approach aims to predict displacement fields to align multiple labelled corresponding structures for individual image pairs during the training, while only unlabelled image pairs are used as the network input for inference. We highlight the versatility of the proposed strategy, for training, utilising diverse types of anatomical labels, which need not to be identifiable over all training image pairs. At inference, the resulting 3D deformable image registration algorithm runs in real-time and is fully-automated without requiring any anatomical labels or initialisation. Several network architecture variants are compared for registering T2-weighted magnetic resonance images and 3D transrectal ultrasound images from prostate cancer patients. A median target registration error of 3.6 mm on landmark centroids and a median Dice of 0.87 on prostate glands are achieved from cross-validation experiments, in which 108 pairs of multimodal images from 76 patients were tested with high-quality anatomical labels.

##### Abstract (translated by Google)
多模态图像配准的监督学习的基本挑战之一是缺乏体素级空间对应的基础事实。该工作描述了一种从解剖标签中包含的更高级别对应信息推断体素级变换的方法。我们认为这样的标签对于参考图像对集合比体素级对应更可靠和实用。感兴趣的典型解剖标签可包括实体器官，血管，导管，结构边界和其他特定于受试者的特设标志。所提出的端到端卷积神经网络方法旨在预测位移场以在训练期间对准各个图像对的多个标记的对应结构，而仅使用未标记的图像对作为用于推断的网络输入。我们强调所提出的策略的多功能性，用于训练，利用不同类型的解剖标签，其不需要在所有训练图像对上可识别。在推断时，得到的3D可变形图像配准算法实时运行并且是完全自动化的，无需任何解剖标记或初始化。比较了几种网络架构变体，用于记录来自前列腺癌患者的T2加权磁共振图像和3D经直肠超声图像。通过交叉验证实验，在标志性质心上的中位目标配准误差为3.6mm，前列腺上的中位骰子为0.87，其中来自76位患者的108对多模态图像用高质量解剖标记进行测试。

##### URL
[http://arxiv.org/abs/1807.03361](http://arxiv.org/abs/1807.03361)

##### PDF
[http://arxiv.org/pdf/1807.03361](http://arxiv.org/pdf/1807.03361)

