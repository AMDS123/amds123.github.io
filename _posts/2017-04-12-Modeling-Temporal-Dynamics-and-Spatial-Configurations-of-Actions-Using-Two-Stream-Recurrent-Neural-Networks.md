---
layout: post
title: "Modeling Temporal Dynamics and Spatial Configurations of Actions Using Two-Stream Recurrent Neural Networks"
date: 2017-04-12 09:08:19
categories: arXiv_CV
tags: arXiv_CV Action_Recognition RNN Recognition
author: Hongsong Wang, Liang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, skeleton based action recognition gains more popularity due to cost-effective depth sensors coupled with real-time skeleton estimation algorithms. Traditional approaches based on handcrafted features are limited to represent the complexity of motion patterns. Recent methods that use Recurrent Neural Networks (RNN) to handle raw skeletons only focus on the contextual dependency in the temporal domain and neglect the spatial configurations of articulated skeletons. In this paper, we propose a novel two-stream RNN architecture to model both temporal dynamics and spatial configurations for skeleton based action recognition. We explore two different structures for the temporal stream: stacked RNN and hierarchical RNN. Hierarchical RNN is designed according to human body kinematics. We also propose two effective methods to model the spatial structure by converting the spatial graph into a sequence of joints. To improve generalization of our model, we further exploit 3D transformation based data augmentation techniques including rotation and scaling transformation to transform the 3D coordinates of skeletons during training. Experiments on 3D action recognition benchmark datasets show that our method brings a considerable improvement for a variety of actions, i.e., generic actions, interaction activities and gestures.

##### Abstract (translated by Google)
最近，基于骨架的动作识别由于具有成本有效的深度传感器以及实时骨架估计算法而变得更加流行。基于手工特征的传统方法仅限于表示运动模式的复杂性。最近使用递归神经网络（RNN）来处理原始骨架的方法只关注时域中的上下文依赖关系，而忽略了关节骨架的空间配置。在本文中，我们提出了一种新颖的双流RNN架构来模拟基于骨架的动作识别的时间动态和空间配置。我们探索了两种不同的时间流结构：堆栈RNN和分层RNN。分层RNN是根据人体运动学设计的。我们还提出了两种有效的方法，通过将空间图转化为一系列关节来建模空间结构。为了改进我们模型的泛化，我们进一步利用基于三维变换的数据增强技术，包括旋转和缩放变换，以在训练期间变换骨架的三维坐标。三维动作识别基准数据集的实验表明，我们的方法为各种动作，即通用动作，交互活动和手势带来了相当大的改善。

##### URL
[https://arxiv.org/abs/1704.02581](https://arxiv.org/abs/1704.02581)

##### PDF
[https://arxiv.org/pdf/1704.02581](https://arxiv.org/pdf/1704.02581)

