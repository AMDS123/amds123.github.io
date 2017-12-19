---
layout: post
title: "Variable-state Latent Conditional Random Fields for Facial Expression Recognition and Action Unit Detection"
date: 2015-10-13 21:57:47
categories: arXiv_CV
tags: arXiv_CV Regularization Face Detection Relation Recognition
author: Robert Walecki, Ognjen Rudovic, Vladimir Pavlovic, Maja Pantic
mathjax: true
---

* content
{:toc}

##### Abstract
Automated recognition of facial expressions of emotions, and detection of facial action units (AUs), from videos depends critically on modeling of their dynamics. These dynamics are characterized by changes in temporal phases (onset-apex-offset) and intensity of emotion expressions and AUs, the appearance of which may vary considerably among target subjects, making the recognition/detection task very challenging. The state-of-the-art Latent Conditional Random Fields (L-CRF) framework allows one to efficiently encode these dynamics through the latent states accounting for the temporal consistency in emotion expression and ordinal relationships between its intensity levels, these latent states are typically assumed to be either unordered (nominal) or fully ordered (ordinal). Yet, such an approach is often too restrictive. For instance, in the case of AU detection, the goal is to discriminate between the segments of an image sequence in which this AU is active or inactive. While the sequence segments containing activation of the target AU may better be described using ordinal latent states, the inactive segments better be described using unordered (nominal) latent states, as no assumption can be made about their underlying structure (since they can contain either neutral faces or activations of non-target AUs). To address this, we propose the variable-state L-CRF (VSL-CRF) model that automatically selects the optimal latent states for the target image sequence. To reduce the model overfitting either the nominal or ordinal latent states, we propose a novel graph-Laplacian regularization of the latent states. Our experiments on three public expression databases show that the proposed model achieves better generalization performance compared to traditional L-CRFs and other related state-of-the-art models.

##### Abstract (translated by Google)
自动识别情绪的面部表情，以及从视频中检测面部动作单元（AU），这关键取决于他们动态的建模。这些动力学的特征是时间阶段（起始 - 顶点偏移）的变化以及情绪表达和AU的强度，其外观在目标受试者之间可能差异很大，使得识别/检测任务非常具有挑战性。最先进的潜在条件随机场（L-CRF）框架允许通过潜在状态有效地对这些动态进行编码，从而说明情绪表达中的时间一致性和其强度水平之间的有序关系，这些潜在状态通常是假定为无序（名义）或完全有序（有序）。然而，这种做法往往过于严格。例如，在AU检测的情况下，目标是区分AU在其中活动或不活动的图像序列的片段。尽管包含目标AU活化的序列片段可能更好地使用序数潜伏状态来描述，但是更好地使用无序（标称）潜伏状态来描述非活性片段，因为不能对其基础结构进行假设（因为它们可以包含中性面对或激活非目标AU）。为了解决这个问题，我们提出了自动选择目标图像序列的最佳潜在状态的可变状态L-CRF（VSL-CRF）模型。为了减少模型过拟合的名义或序数潜在状态，我们提出了一种新的图拉普拉斯正规化的潜态。我们在三个公共表达数据库上的实验表明，与传统的L-CRF和其他相关的最新模型相比，所提出的模型实现了更好的泛化性能。

##### URL
[https://arxiv.org/abs/1510.03909](https://arxiv.org/abs/1510.03909)

##### PDF
[https://arxiv.org/pdf/1510.03909](https://arxiv.org/pdf/1510.03909)

