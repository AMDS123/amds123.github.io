---
layout: post
title: "SenseGen: A Deep Learning Architecture for Synthetic Sensor Data Generation"
date: 2017-01-31 01:59:58
categories: arXiv_CV
tags: arXiv_CV Adversarial RNN Deep_Learning
author: Moustafa Alzantot, Supriyo Chakraborty, Mani B. Srivastava
mathjax: true
---

* content
{:toc}

##### Abstract
Our ability to synthesize sensory data that preserves specific statistical properties of the real data has had tremendous implications on data privacy and big data analytics. The synthetic data can be used as a substitute for selective real data segments,that are sensitive to the user, thus protecting privacy and resulting in improved analytics.However, increasingly adversarial roles taken by data recipients such as mobile apps, or other cloud-based analytics services, mandate that the synthetic data, in addition to preserving statistical properties, should also be difficult to distinguish from the real data. Typically, visual inspection has been used as a test to distinguish between datasets. But more recently, sophisticated classifier models (discriminators), corresponding to a set of events, have also been employed to distinguish between synthesized and real data. The model operates on both datasets and the respective event outputs are compared for consistency. In this paper, we take a step towards generating sensory data that can pass a deep learning based discriminator model test, and make two specific contributions: first, we present a deep learning based architecture for synthesizing sensory data. This architecture comprises of a generator model, which is a stack of multiple Long-Short-Term-Memory (LSTM) networks and a Mixture Density Network. second, we use another LSTM network based discriminator model for distinguishing between the true and the synthesized data. Using a dataset of accelerometer traces, collected using smartphones of users doing their daily activities, we show that the deep learning based discriminator model can only distinguish between the real and synthesized traces with an accuracy in the neighborhood of 50%.

##### Abstract (translated by Google)
我们综合保留真实数据的特定统计特性的感官数据的能力已经对数据隐私和大数据分析产生了巨大的影响。合成数据可以用来替代对用户敏感的选择性真实数据段，从而保护隐私，从而改善分析。然而，数据接收者（如移动应用程序或其他基于云的分析服务，要求合成数据除了保留统计特性外，还应该难以与真实数据区分开来。通常，视觉检查已被用作区分数据集的测试。但是最近，与一组事件相对应的复杂分类器模型（鉴别器）也被用来区分合成数据和真实数据。该模型在两个数据集上运行，并对各个事件输出的一致性进行比较。在本文中，我们迈出了一步，产生的感官数据，可以通过一个深入的学习为基础的鉴别模型测试，并做出了两个具体的贡献：首先，我们提出一个深度学习为基础的体系结构合成感官数据。这种架构包括一个发电机模型，它是一个多个长期短期记忆（LSTM）网络和一个混合密度网络的堆栈。其次，我们使用另一种基于LSTM网络的鉴别器模型来区分真实数据和合成数据。使用用户的日常活动智能手机采集的加速度计轨迹数据集，我们表明，基于深度学习的鉴别器模型只能区分真实轨迹和合成轨迹，精确度在50％左右。

##### URL
[https://arxiv.org/abs/1701.08886](https://arxiv.org/abs/1701.08886)

##### PDF
[https://arxiv.org/pdf/1701.08886](https://arxiv.org/pdf/1701.08886)

