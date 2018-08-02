---
layout: post
title: "Reinforced Evolutionary Neural Architecture Search"
date: 2018-08-01 06:53:53
categories: arXiv_CV
tags: arXiv_CV
author: Yukang Chen, Qian Zhang, Chang Huang, Lisen Mu, Gaofeng Meng, Xinggang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural architecture search (NAS) is an important task in network design, but it remains challenging due to high computational consumption in most methods and low stability in evolution algorithm (EA) based NAS. In this paper, we propose the Reinforced Evolutionary Neural Architecture Search (RENAS), an evolutionary method with reinforced mutation for NAS to address these two issues. Specifically, we integrate reinforced mutation into an EA based NAS method by adopting a mutation controller to learn the effects of slight modifications and make mutation actions. For this reason, the proposed method is more like the process of model design by human experts than typical RL-based NAS methods that construct networks sequentially. Furthermore, as the models are trained by fine-tuning rather than from scratch in model evaluation, the cell-wise search process becomes much more efficient and only takes less than 1.5 days using 4 GPUs (Titan xp). Experimental results demonstrate the effectiveness and efficiency of our method. Moreover, the architecture searched on CIFAR-10 sets a new state-of-the-art on ImageNet in the mobile setting (top-1/5 accuracy = 75.7%/92.6%).

##### Abstract (translated by Google)
神经架构搜索（NAS）是网络设计中的一项重要任务，但由于大多数方法的高计算量消耗和基于进化算法（EA）的NAS的低稳定性，它仍然具有挑战性。在本文中，我们提出了增强进化神经结构搜索（RENAS），这是一种具有NAS强化突变的进化方法，可以解决这两个问题。具体而言，我们通过采用变异控制器来学习轻微修改的影响并进行突变操作，将强化突变整合到基于EA的NAS方法中。由于这个原因，所提出的方法更像是人类专家的模型设计过程，而不是典型的基于RL的NAS方法，这些方法依次构建网络。此外，由于模型在模型评估中通过微调而不是从零开始进行训练，因此细胞方式搜索过程变得更加有效，并且使用4个GPU（Titan xp）只需不到1.5天。实验结果证明了该方法的有效性和有效性。此外，在CIFAR-10上搜索的架构在移动设置中为ImageNet设置了一个新的最新技术（前1/5精度= 75.7％/ 92.6％）。

##### URL
[https://arxiv.org/abs/1808.00193](https://arxiv.org/abs/1808.00193)

##### PDF
[https://arxiv.org/pdf/1808.00193](https://arxiv.org/pdf/1808.00193)

