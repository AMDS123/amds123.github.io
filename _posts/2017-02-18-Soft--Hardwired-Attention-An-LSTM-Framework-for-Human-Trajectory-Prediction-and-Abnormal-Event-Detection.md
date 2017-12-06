---
layout: post
title: "Soft + Hardwired Attention: An LSTM Framework for Human Trajectory Prediction and Abnormal Event Detection"
date: 2017-02-18 01:08:18
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN Detection
author: Tharindu Fernando, Simon Denman, Sridha Sridharan, Clinton Fookes
mathjax: true
---

* content
{:toc}

##### Abstract
As humans we possess an intuitive ability for navigation which we master through years of practice; however existing approaches to model this trait for diverse tasks including monitoring pedestrian flow and detecting abnormal events have been limited by using a variety of hand-crafted features. Recent research in the area of deep-learning has demonstrated the power of learning features directly from the data; and related research in recurrent neural networks has shown exemplary results in sequence-to-sequence problems such as neural machine translation and neural image caption generation. Motivated by these approaches, we propose a novel method to predict the future motion of a pedestrian given a short history of their, and their neighbours, past behaviour. The novelty of the proposed method is the combined attention model which utilises both "soft attention" as well as "hard-wired" attention in order to map the trajectory information from the local neighbourhood to the future positions of the pedestrian of interest. We illustrate how a simple approximation of attention weights (i.e hard-wired) can be merged together with soft attention weights in order to make our model applicable for challenging real world scenarios with hundreds of neighbours. The navigational capability of the proposed method is tested on two challenging publicly available surveillance databases where our model outperforms the current-state-of-the-art methods. Additionally, we illustrate how the proposed architecture can be directly applied for the task of abnormal event detection without handcrafting the features.

##### Abstract (translated by Google)
作为人类，我们拥有通过多年实践掌握的直观的导航能力;然而，现有的方法来模拟这种特性的各种任务，包括监测行人流量和检测异常事件已被限制，通过使用各种手工制作的功能。最近在深度学习方面的研究已经证明直接从数据中学习特征的力量;并且在递归神经网络中的相关研究已经在序列到序列的问题（例如神经机器翻译和神经图像字幕生成）中示出了示例性结果。受这些方法的启发，我们提出了一种新的方法来预测行人的未来运动，只要他们的历史和他们的邻居过去的行为历史。所提出的方法的新颖性是为了将来自本地邻居的轨迹信息映射到感兴趣的行人的未来位置而利用“软注意”以及“硬连线”注意的组合注意模型。我们举例说明，为了使我们的模型适用于挑战具有数百个邻居的真实世界场景，可以如何将注意力权重（即硬连线）的简单近似与软注意力权重合并在一起。所提出的方法的导航能力在两个具有挑战性的公开可用的监视数据库上进行测试，其中我们的模型胜过当前最先进的方法。此外，我们说明了如何提出的架构可以直接应用于异常事件检测的任务，而无需手动的功能。

##### URL
[https://arxiv.org/abs/1702.05552](https://arxiv.org/abs/1702.05552)

