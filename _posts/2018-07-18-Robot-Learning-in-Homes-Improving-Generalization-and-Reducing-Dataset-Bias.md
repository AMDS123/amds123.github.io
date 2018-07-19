---
layout: post
title: "Robot Learning in Homes: Improving Generalization and Reducing Dataset Bias"
date: 2018-07-18 17:25:28
categories: arXiv_RO
tags: arXiv_RO
author: Abhinav Gupta, Adithyavairavan Murali, Dhiraj Gandhi, Lerrel Pinto
mathjax: true
---

* content
{:toc}

##### Abstract
Data-driven approaches to solving robotic tasks have gained a lot of traction in recent years. However, most existing policies are trained on large-scale datasets collected in curated lab settings. If we aim to deploy these models in unstructured visual environments like people's homes, they will be unable to cope with the mismatch in data distribution. In such light, we present the first systematic effort in collecting a large dataset for robotic grasping in homes. First, to scale and parallelize data collection, we built a low cost mobile manipulator assembled for under 3K USD. Second, data collected using low cost robots suffer from noisy labels due to imperfect execution and calibration errors. To handle this, we develop a framework which factors out the noise as a latent variable. Our model is trained on 28K grasps collected in several houses under an array of different environmental conditions. We evaluate our models by physically executing grasps on a collection of novel objects in multiple unseen homes. The models trained with our home dataset showed a marked improvement of 43.7% over a baseline model trained with data collected in lab. Our architecture which explicitly models the latent noise in the dataset also performed 10% better than one that did not factor out the noise. We hope this effort inspires the robotics community to look outside the lab and embrace learning based approaches to handle inaccurate cheap robots.

##### Abstract (translated by Google)
近年来，解决机器人任务的数据驱动方法获得了很大的关注。但是，大多数现有策略都是针对策划实验室设置中收集的大型数据集进行培训的。如果我们的目标是在人们家中的非结构化视觉环境中部署这些模型，他们将无法应对数据分布的不匹配。有鉴于此，我们首次系统地收集了一个用于家庭机器人抓取的大型数据集。首先，为了扩展和并行化数据收集，我们建立了一个低于3K美元组装的低成本移动机械手。其次，使用低成本机器人收集的数据由于不完美的执行和校准错误而受到噪声标签的影响。为了解决这个问题，我们开发了一个框架，将噪声作为潜在变量。我们的模型是在一系列不同环境条件下在几个房屋中收集的28K抓握培训。我们通过在多个看不见的家中对一组新物体进行物理执行来评估我们的模型。使用我们的家庭数据集训练的模型显示，与使用实验室收集的数据训练的基线模型相比，显着改善了43.7％。我们的架构明确地模拟了数据集中的潜在噪声，其性能也比未分解噪声的架构好10％。我们希望这项努力能激发机器人社区在实验室外寻找并采用基于学习的方法来处理不准确的廉价机器人。

##### URL
[http://arxiv.org/abs/1807.07049](http://arxiv.org/abs/1807.07049)

##### PDF
[http://arxiv.org/pdf/1807.07049](http://arxiv.org/pdf/1807.07049)

