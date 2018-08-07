---
layout: post
title: "Soft + Hardwired Attention: An LSTM Framework for Human Trajectory Prediction and Abnormal Event Detection"
date: 2017-02-18 01:08:18
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention Caption RNN Prediction Detection
author: Tharindu Fernando, Simon Denman, Sridha Sridharan, Clinton Fookes
mathjax: true
---

* content
{:toc}

##### Abstract
As humans we possess an intuitive ability for navigation which we master through years of practice; however existing approaches to model this trait for diverse tasks including monitoring pedestrian flow and detecting abnormal events have been limited by using a variety of hand-crafted features. Recent research in the area of deep-learning has demonstrated the power of learning features directly from the data; and related research in recurrent neural networks has shown exemplary results in sequence-to-sequence problems such as neural machine translation and neural image caption generation. Motivated by these approaches, we propose a novel method to predict the future motion of a pedestrian given a short history of their, and their neighbours, past behaviour. The novelty of the proposed method is the combined attention model which utilises both "soft attention" as well as "hard-wired" attention in order to map the trajectory information from the local neighbourhood to the future positions of the pedestrian of interest. We illustrate how a simple approximation of attention weights (i.e hard-wired) can be merged together with soft attention weights in order to make our model applicable for challenging real world scenarios with hundreds of neighbours. The navigational capability of the proposed method is tested on two challenging publicly available surveillance databases where our model outperforms the current-state-of-the-art methods. Additionally, we illustrate how the proposed architecture can be directly applied for the task of abnormal event detection without handcrafting the features.

##### Abstract (translated by Google)
作为人类，我们拥有直观的导航能力，这是我们通过多年的实践掌握的;然而，通过使用各种手工制作的特征，已经限制了用于对包括监视行人流量和检测异常事件在内的各种任务建模该特征的现有方法。最近在深度学习领域的研究表明，直接从数据中学习特征的能力;在递归神经网络中的相关研究已经显示了序列到序列问题的示例性结果，例如神经机器翻译和神经图像标题生成。在这些方法的推动下，我们提出了一种新方法来预测行人的未来运动，因为他们和他们的邻居，过去的行为有短暂的历史。所提出的方法的新颖性是组合注意模型，其利用“软注意”以及“硬连线”注意，以便将来自本地邻域的轨迹信息映射到感兴趣的行人的未来位置。我们说明了如何将简单近似的注意权重（即硬连线）与软注意权重合并在一起，以使我们的模型适用于挑战具有数百个邻居的真实世界场景。该方法的导航能力在两个具有挑战性的公开监测数据库中进行了测试，其中我们的模型优于当前最先进的方法。此外，我们还说明了如何将所提出的架构直接应用于异常事件检测任务，而无需手工编写这些功能。

##### URL
[https://arxiv.org/abs/1702.05552](https://arxiv.org/abs/1702.05552)

##### PDF
[https://arxiv.org/pdf/1702.05552](https://arxiv.org/pdf/1702.05552)

