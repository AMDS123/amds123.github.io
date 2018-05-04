---
layout: post
title: "Evolving Mario Levels in the Latent Space of a Deep Convolutional Generative Adversarial Network"
date: 2018-05-02 10:59:36
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN CNN
author: Vanessa Volz, Jacob Schrum, Jialin Liu, Simon M. Lucas, Adam Smith, Sebastian Risi
mathjax: true
---

* content
{:toc}

##### Abstract
Generative Adversarial Networks (GANs) are a machine learning approach capable of generating novel example outputs across a space of provided training examples. Procedural Content Generation (PCG) of levels for video games could benefit from such models, especially for games where there is a pre-existing corpus of levels to emulate. This paper trains a GAN to generate levels for Super Mario Bros using a level from the Video Game Level Corpus. The approach successfully generates a variety of levels similar to one in the original corpus, but is further improved by application of the Covariance Matrix Adaptation Evolution Strategy (CMA-ES). Specifically, various fitness functions are used to discover levels within the latent space of the GAN that maximize desired properties. Simple static properties are optimized, such as a given distribution of tile types. Additionally, the champion A* agent from the 2009 Mario AI competition is used to assess whether a level is playable, and how many jumping actions are required to beat it. These fitness functions allow for the discovery of levels that exist within the space of examples designed by experts, and also guide the search towards levels that fulfill one or more specified objectives.

##### Abstract (translated by Google)
生成对抗网络（GAN）是一种机器学习方法，能够在提供的训练示例空间中生成新的示例输出。视频游戏级别的程序内容生成（PCG）可以从这种模型中受益，特别是对于存在预先存在的语料库模拟的游戏。本文使用视频游戏关卡语料库中的关卡训练GAN来为超级马里奥兄弟生成关卡。该方法成功地生成了与原始语料库中类似的各种级别，但通过应用协方差矩阵适应进化策略（CMA-ES）得到进一步改进。具体而言，使用各种适应度函数来发现GAN的潜在空间内的水平，以最大化期望的性质。简单的静态属性进行了优化，例如瓷砖类型的给定分布。此外，2009年马里奥AI竞赛的冠军A *代理人用来评估一个级别是否可玩，以及需要多少次跳跃动作来击败它。这些适应度函数可以发现由专家设计的示例空间中存在的水平，还可以指导搜索达到满足一个或多个特定目标的水平。

##### URL
[https://arxiv.org/abs/1805.00728](https://arxiv.org/abs/1805.00728)

##### PDF
[https://arxiv.org/pdf/1805.00728](https://arxiv.org/pdf/1805.00728)

