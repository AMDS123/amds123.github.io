---
layout: post
title: "Exploring Temporal Preservation Networks for Precise Temporal Action Localization"
date: 2017-09-11 08:32:50
categories: arXiv_CV
tags: arXiv_CV GAN CNN Prediction
author: Ke Yang, Peng Qiao, Dongsheng Li, Shaohe Lv, Yong Dou
mathjax: true
---

* content
{:toc}

##### Abstract
Temporal action localization is an important task of computer vision. Though a variety of methods have been proposed, it still remains an open question how to predict the temporal boundaries of action segments precisely. Most works use segment-level classifiers to select video segments pre-determined by action proposal or dense sliding windows. However, in order to achieve more precise action boundaries, a temporal localization system should make dense predictions at a fine granularity. A newly proposed work exploits Convolutional-Deconvolutional-Convolutional (CDC) filters to upsample the predictions of 3D ConvNets, making it possible to perform per-frame action predictions and achieving promising performance in terms of temporal action localization. However, CDC network loses temporal information partially due to the temporal downsampling operation. In this paper, we propose an elegant and powerful Temporal Preservation Convolutional (TPC) Network that equips 3D ConvNets with TPC filters. TPC network can fully preserve temporal resolution and downsample the spatial resolution simultaneously, enabling frame-level granularity action localization. TPC network can be trained in an end-to-end manner. Experiment results on public datasets show that TPC network achieves significant improvement on per-frame action prediction and competing results on segment-level temporal action localization.

##### Abstract (translated by Google)
时态动作定位是计算机视觉的一项重要任务。虽然已经提出了各种方法，但是如何精确地预测动作片段的时间边界还是一个悬而未决的问题。大多数作品使用片段级分类器来选择由动作提议预先确定的视频片段或者密集滑动窗口。然而，为了实现更精确的行动边界，时间定位系统应该以精细的粒度进行密集的预测。最近提出的一个工作是利用卷积 - 去卷积 - 卷积（CDC）滤波器对3D ConvNets的预测进行上采样，使得可以执行每帧动作预测，并在时间动作定位方面获得有希望的性能。然而，由于时间下采样操作，CDC网络部分地丢失了时间信息。在本文中，我们提出了一个优雅和强大的时间保存卷积（TPC）网络，配备三维ConvNets TPC滤波器。 TPC网络可以完全保留时间分辨率，同时对空间分辨率进行降采样，实现帧级粒度动作定位。 TPC网络可以以端到端的方式进行培训。公共数据集上的实验结果表明，TPC网络在每帧动作预测方面取得了显着的改善，并且在片段级时态动作定位上取得了显着的改善。

##### URL
[https://arxiv.org/abs/1708.03280](https://arxiv.org/abs/1708.03280)

##### PDF
[https://arxiv.org/pdf/1708.03280](https://arxiv.org/pdf/1708.03280)

