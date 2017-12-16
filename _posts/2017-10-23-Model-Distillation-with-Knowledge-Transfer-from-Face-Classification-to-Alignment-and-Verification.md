---
layout: post
title: "Model Distillation with Knowledge Transfer from Face Classification to Alignment and Verification"
date: 2017-10-23 07:51:29
categories: arXiv_CV
tags: arXiv_CV Knowledge Face Classification Recognition Face_Recognition
author: Chong Wang, Xipeng Lan, Yangang Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge distillation is a potential solution for model compression. The idea is to make a small student network imitate the target of a large teacher network, then the student network can be competitive to the teacher one. Most previous studies focus on model distillation in the classification task, where they propose different architects and initializations for the student network. However, only the classification task is not enough, and other related tasks such as regression and retrieval are barely considered. To solve the problem, in this paper, we take face recognition as a breaking point and propose model distillation with knowledge transfer from face classification to alignment and verification. By selecting appropriate initializations and targets in the knowledge transfer, the distillation can be easier in non-classification tasks. Experiments on the CelebA and CASIA-WebFace datasets demonstrate that the student network can be competitive to the teacher one in alignment and verification, and even surpasses the teacher network under specific compression rates. In addition, to achieve stronger knowledge transfer, we also use a common initialization trick to improve the distillation performance of classification. Evaluations on the CASIA-Webface and large-scale MS-Celeb-1M datasets show the effectiveness of this simple trick.

##### Abstract (translated by Google)
知识蒸馏是模型压缩的潜在解决方案。这个想法是让一个小的学生网络模仿一个大型的教师网络的目标，那么这个学生网络就可以对老师有竞争力。大多数以前的研究集中在分类任务的模型蒸馏，他们提出不同的建筑师和学生网络的初始化。然而，只有分类任务是不够的，勉强考虑其他相关的任务，如回归和检索。为解决这个问题，本文以人脸识别为切入点，提出了从人脸分类到对齐验证的知识转移模型蒸馏。通过在知识转移中选择适当的初始化和目标，在非分类任务中蒸馏可以更容易。在CelebA和CASIA-WebFace数据集上的实验表明，学生网络可以在校准和验证方面与老师相比具有竞争性，甚至可以在特定的压缩率下超过教师网络。另外，为了实现更强的知识转移，我们也使用一个共同的初始化技巧来提高分类的精馏性能。 CASIA-Webface和大规模MS-Celeb-1M数据集的评估显示了这个简单技巧的有效性。

##### URL
[https://arxiv.org/abs/1709.02929](https://arxiv.org/abs/1709.02929)

##### PDF
[https://arxiv.org/pdf/1709.02929](https://arxiv.org/pdf/1709.02929)

