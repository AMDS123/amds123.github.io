---
layout: post
title: "ModDrop: adaptive multi-modal gesture recognition"
date: 2015-06-06 14:46:33
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction Detection Relation Recognition
author: Natalia Neverova, Christian Wolf, Graham W. Taylor, Florian Nebout
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for gesture detection and localisation based on multi-scale and multi-modal deep learning. Each visual modality captures spatial information at a particular spatial scale (such as motion of the upper body or a hand), and the whole system operates at three temporal scales. Key to our technique is a training strategy which exploits: i) careful initialization of individual modalities; and ii) gradual fusion involving random dropping of separate channels (dubbed ModDrop) for learning cross-modality correlations while preserving uniqueness of each modality-specific representation. We present experiments on the ChaLearn 2014 Looking at People Challenge gesture recognition track, in which we placed first out of 17 teams. Fusing multiple modalities at several spatial and temporal scales leads to a significant increase in recognition rates, allowing the model to compensate for errors of the individual classifiers as well as noise in the separate channels. Futhermore, the proposed ModDrop training technique ensures robustness of the classifier to missing signals in one or several channels to produce meaningful predictions from any number of available modalities. In addition, we demonstrate the applicability of the proposed fusion scheme to modalities of arbitrary nature by experiments on the same dataset augmented with audio.

##### Abstract (translated by Google)
我们提出了一种基于多尺度多模态深度学习的手势检测和定位方法。每种视觉形态都以特定的空间尺度（如上身或手的运动）捕捉空间信息，整个系统以三个时间尺度运行。我们技术的关键是一种培训策略，它利用：i）个人模式的仔细初始化;和ii）逐步融合，涉及随机丢弃单独的通道（称为ModDrop），用于学习交叉模态相关性，同时保持每个模态特定表示的唯一性。我们在ChaLearn 2014展望人物挑战手势识别轨道上展示实验，其中我们在17个团队中排第一。在多个空间和时间尺度上融合多种模态可以显着提高识别率，使模型能够补偿单个分类器的误差以及单独通道中的噪声。此外，所提出的ModDrop训练技术确保了分类器在一个或多个通道中丢失信号的鲁棒性，以从任何数量的可用模式产生有意义的预测。另外，我们通过在音频增强的相同数据集上的实验来证明所提出的融合方案对任意性质的模态的适用性。

##### URL
[https://arxiv.org/abs/1501.00102](https://arxiv.org/abs/1501.00102)

##### PDF
[https://arxiv.org/pdf/1501.00102](https://arxiv.org/pdf/1501.00102)

