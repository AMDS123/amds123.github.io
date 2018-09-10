---
layout: post
title: "Adversarial Feature-Mapping for Speech Enhancement"
date: 2018-09-06 23:42:21
categories: arXiv_CL
tags: arXiv_CL Adversarial Classification
author: Zhong Meng, Jinyu Li, Yifan Gong, Biing-Hwang (Fred)Juang
mathjax: true
---

* content
{:toc}

##### Abstract
Feature-mapping with deep neural networks is commonly used for single-channel speech enhancement, in which a feature-mapping network directly transforms the noisy features to the corresponding enhanced ones and is trained to minimize the mean square errors between the enhanced and clean features. In this paper, we propose an adversarial feature-mapping (AFM) method for speech enhancement which advances the feature-mapping approach with adversarial learning. An additional discriminator network is introduced to distinguish the enhanced features from the real clean ones. The two networks are jointly optimized to minimize the feature-mapping loss and simultaneously mini-maximize the discrimination loss. The distribution of the enhanced features is further pushed towards that of the clean features through this adversarial multi-task training. To achieve better performance on ASR task, senone-aware (SA) AFM is further proposed in which an acoustic model network is jointly trained with the feature-mapping and discriminator networks to optimize the senone classification loss in addition to the AFM losses. Evaluated on the CHiME-3 dataset, the proposed AFM achieves 16.95% and 5.27% relative word error rate (WER) improvements over the real noisy data and the feature-mapping baseline respectively and the SA-AFM achieves 9.85% relative WER improvement over the multi-conditional acoustic model.

##### Abstract (translated by Google)
具有深度神经网络的特征映射通常用于单通道语音增强，其中特征映射网络将噪声特征直接转换为相应的增强特征，并且被训练以最小化增强特征和干净特征之间的均方误差。在本文中，我们提出了一种用于语音增强的对抗特征映射（AFM）方法，该方法通过对抗性学习推进了特征映射方法。引入了另外的鉴别器网络以区分增强特征和真正干净特征。这两个网络是联合优化的，以最大限度地减少特征映射损失，同时最小化歧视损失。通过这种对抗性多任务训练，增强功能的分布进一步推向了清洁功能的分布。为了在ASR任务上实现更好的性能，进一步提出了senone-aware（SA）AFM，其中声学模型网络与特征映射和鉴别器网络联合训练以优化除了AFM损失之外的senone分类损失。根据CHiME-3数据集进行评估，拟议的AFM分别比实际噪声数据和特征映射基线实现了16.95％和5.27％的相对字错误率（WER）改进，并且SA-AFM相对于WER改进达到了9.85％。多条件声学模型。

##### URL
[https://arxiv.org/abs/1809.02251](https://arxiv.org/abs/1809.02251)

##### PDF
[https://arxiv.org/pdf/1809.02251](https://arxiv.org/pdf/1809.02251)

