---
layout: post
title: "Temporal Action Localization in Untrimmed Videos via Multi-stage CNNs"
date: 2016-04-21 22:15:22
categories: arXiv_CV
tags: arXiv_CV Classification Prediction
author: Zheng Shou, Dongang Wang, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
We address temporal action localization in untrimmed long videos. This is important because videos in real applications are usually unconstrained and contain multiple action instances plus video content of background scenes or other activities. To address this challenging issue, we exploit the effectiveness of deep networks in temporal action localization via three segment-based 3D ConvNets: (1) a proposal network identifies candidate segments in a long video that may contain actions; (2) a classification network learns one-vs-all action classification model to serve as initialization for the localization network; and (3) a localization network fine-tunes on the learned classification network to localize each action instance. We propose a novel loss function for the localization network to explicitly consider temporal overlap and therefore achieve high temporal localization accuracy. Only the proposal network and the localization network are used during prediction. On two large-scale benchmarks, our approach achieves significantly superior performances compared with other state-of-the-art systems: mAP increases from 1.7% to 7.4% on MEXaction2 and increases from 15.0% to 19.0% on THUMOS 2014, when the overlap threshold for evaluation is set to 0.5.

##### Abstract (translated by Google)
我们解决未修剪的长视频中的时间动作本地化。这一点很重要，因为真实应用程序中的视频通常不受限制，并且包含多个动作实例以及背景场景或其他活动的视频内容。为了解决这个具有挑战性的问题，我们通过三个基于分段的3D通信来利用深度网络在时间动作定位中的有效性：（1）提案网络在长视频中识别可能包含动作的候选片段; （2）分类网络学习一对一动作分类模型作为本地化网络的初始化; （3）定位网络在学习的分类网络上微调以定位每个动作实例。我们提出了一个新的损失函数的定位网络明确考虑时间重叠，从而实现高时间定位精度。预测期间只使用提案网络和本地化网络。在两个大规模的基准测试中，我们的方法与其他最先进的系统相比具有显着的优势：MEXaction2的mAP从1.7％上升到7.4％，在THUMOS 2014上从15.0％上升到19.0％评估阈值设置为0.5。

##### URL
[https://arxiv.org/abs/1601.02129](https://arxiv.org/abs/1601.02129)

##### PDF
[https://arxiv.org/pdf/1601.02129](https://arxiv.org/pdf/1601.02129)

