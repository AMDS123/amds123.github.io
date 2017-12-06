---
layout: post
title: "Occlusion-aware Hand Pose Estimation Using Hierarchical Mixture Density Network"
date: 2017-11-29 14:25:18
categories: arXiv_CV
tags: arXiv_CV
author: Qi Ye, Tae-Kyun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Hand pose estimation is to predict the pose parameters representing a 3D hand model, such as locations of hand joints. This problem is very challenging due to large changes in viewpoints and articulations, and intense self-occlusions, etc. Many researchers have investigated the problem from both aspects of input feature learning and output prediction modelling. Though effective, most of the existing discriminative methods only give a deterministic estimation of target poses. Also, due to their single-value mapping intrinsic, they fail to adequately handle self-occlusion problems, where occluded joints present multiple modes. In this paper, we tackle the self-occlusion issue and provide a complete description of observed poses given an input depth image through a hierarchical mixture density network (HMDN) framework. In particular, HMDN leverages the state-of-the-art CNN module to facilitate feature learning, while proposes a density in a two-level hierarchy to reconcile single-valued and multi-valued mapping in the output. The whole framework is naturally end-to-end trainable with a mixture of two differentiable density functions. HMDN produces interpretable and diverse candidate samples, and significantly outperforms the state-of-the-art algorithms on benchmarks that exhibit occlusions.

##### Abstract (translated by Google)
手姿态估计是预测表示3D手模型的姿态参数，例如手关节的位置。这个问题由于观点和发音方面的巨大变化以及强烈的自我遮挡等原因而非常具有挑战性。许多研究人员从输入特征学习和输出预测建模两个方面对这个问题进行了研究。尽管有效，但大多数现有的判别方法只能给出目标姿态的确定性估计。此外，由于它们的单值映射本质，它们不能充分地处理自闭塞问题，闭塞的关节呈现多种模式。在本文中，我们处理自闭塞问题，并通过分层混合密度网络（HMDN）框架给出了输入深度图像的观察姿态的完整描述。具体而言，HMDN利用最先进的CNN模块来促进特征学习，同时在两级层次中提出密度来协调输出中的单值和多值映射。整个框架自然是端到端的可训练的混合两个不同的密度函数。 HMDN产生可解释和多样化的候选样本，并且在显示闭塞的基准上显着优于最先进的算法。

##### URL
[https://arxiv.org/abs/1711.10872](https://arxiv.org/abs/1711.10872)

