---
layout: post
title: "In-Bed Pose Estimation: Deep Learning with Shallow Dataset"
date: 2017-11-03 03:05:05
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Deep_Learning
author: Shuangjun Liu, Yu Yin, Sarah Ostadabbas
mathjax: true
---

* content
{:toc}

##### Abstract
Although human pose estimation for various computer vision (CV) applications has been studied extensively in the last few decades, yet in-bed pose estimation using camera-based vision methods has been ignored by the CV community because it is assumed to be identical to the general purpose pose estimation methods. However, in-bed pose estimation has its own specialized aspects and comes with specific challenges including the notable differences in lighting conditions throughout a day and also having different pose distribution from the common human surveillance viewpoint. In this paper, we demonstrate that these challenges significantly lessen the effectiveness of existing general purpose pose estimation models. In order to address the lighting variation challenge, infrared selective (IRS) image acquisition technique is proposed to provide uniform quality data under various lighting conditions. Deep learning framework proves to be the most effective model in human pose estimation, however the lack of large public dataset for in-bed poses prevents us from using a large network from scratch. In this work, we explored the idea of employing a pre-trained convolutional neural network (CNN) model trained on large public datasets of general human poses and fine-tuning the model using our own shallow (limited in size and different in perspective and color) in-bed IRS dataset. We developed an IRS imaging system and collected IRS image data from several realistic life-size mannequins in a simulated hospital room environment. A pre-trained CNN called convolutional pose machine (CPM) was repurposed for in-bed pose estimation by fine-tuning its specific intermediate layers. Using the HOG rectification method, the pose estimation performance of CPM significantly improved by 26.4% in PCK0.1 criteria compared to the model without such rectification.

##### Abstract (translated by Google)
尽管在过去的几十年中，人们对各种计算机视觉（CV）应用的姿态估计已经被广泛研究，但是使用基于相机的视觉方法的床上姿态估计已经被CV社区忽略了，因为它被假定为与通用姿态估计方法。然而，床上姿势估计有其自身的特殊性，并且面临着具体的挑战，包括一天中照明条件的显着差异，并且从普通的人类监视观点出发具有不同的姿态分布。在本文中，我们证明这些挑战显着降低了现有通用姿态估计模型的有效性。为了解决照明变化的挑战，提出了红外选择（IRS）图像采集技术，以在各种照明条件下提供统一的质量数据。深度学习框架被证明是人类姿态估计中最有效的模型，然而由于缺乏大型公共数据集，因此不能从头开始使用大型网络。在这项工作中，我们探索了使用预先训练的卷积神经网络（CNN）模型的想法，这个模型是在一般人体姿势的大型公共数据集上进行训练的，并且使用我们自己的浅层（模型大小有限，视角和颜色不同）在床IRS数据集。我们开发了IRS成像系统，并在模拟的医院房间环境中从几个真实人体模特身上采集了IRS图像数据。通过微调其特定的中间层，将预先训练的CNN卷积式姿态机（CPM）重新用于床上姿态估计。使用HOG纠正方法，CPM的姿态估计性能比没有纠正的模型在PCK0.1标准下显着提高了26.4％。

##### URL
[https://arxiv.org/abs/1711.01005](https://arxiv.org/abs/1711.01005)

##### PDF
[https://arxiv.org/pdf/1711.01005](https://arxiv.org/pdf/1711.01005)

