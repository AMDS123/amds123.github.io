---
layout: post
title: "Hands-Free Segmentation of Medical Volumes via Binary Inputs"
date: 2016-09-20 14:18:40
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN
author: Florian Dubost, Loic Peter, Christian Rupprecht, Benjamin Gutierrez-Becker, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel hands-free method to interactively segment 3D medical volumes. In our scenario, a human user progressively segments an organ by answering a series of questions of the form "Is this voxel inside the object to segment?". At each iteration, the chosen question is defined as the one halving a set of candidate segmentations given the answered questions. For a quick and efficient exploration, these segmentations are sampled according to the Metropolis-Hastings algorithm. Our sampling technique relies on a combination of relaxed shape prior, learnt probability map and consistency with previous answers. We demonstrate the potential of our strategy on a prostate segmentation MRI dataset. Through the study of failure cases with synthetic examples, we demonstrate the adaptation potential of our method. We also show that our method outperforms two intuitive baselines: one based on random questions, the other one being the thresholded probability map.

##### Abstract (translated by Google)
我们提出了一种新颖的免提方法来交互式地分割3D医疗卷。在我们的场景中，一个用户通过回答一系列形式为“这个体素在分割对象内部的体素”的问题来逐渐分割一个器官。在每次迭代中，所选择的问题被定义为给出回答问题的一组候选分割的一半。为了快速而有效的探索，根据Metropolis-Hastings算法对这些分段进行采样。我们的抽样技术依赖于松弛形状先验，学习概率图和前一个答案的一致性。我们展示了我们的战略在前列腺分割MRI数据集的潜力。通过对合成案例的失败案例的研究，我们证明了我们方法的适应潜力。我们还表明，我们的方法胜过两个直观的基线：一个基于随机问题，另一个是阈值概率图。

##### URL
[https://arxiv.org/abs/1609.06192](https://arxiv.org/abs/1609.06192)

##### PDF
[https://arxiv.org/pdf/1609.06192](https://arxiv.org/pdf/1609.06192)

