---
layout: post
title: "Exploring Uncertainty Measures in Deep Networks for Multiple Sclerosis Lesion Detection and Segmentation"
date: 2018-08-03 14:19:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning Prediction Detection
author: Tanya Nair, Doina Precup, Douglas L. Arnold, Tal Arbel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning (DL) networks have recently been shown to outperform other segmentation methods on various public, medical-image challenge datasets [3,11,16], especially for large pathologies. However, in the context of diseases such as Multiple Sclerosis (MS), monitoring all the focal lesions visible on MRI sequences, even very small ones, is essential for disease staging, prognosis, and evaluating treatment efficacy. Moreover, producing deterministic outputs hinders DL adoption into clinical routines. Uncertainty estimates for the predictions would permit subsequent revision by clinicians. We present the first exploration of multiple uncertainty estimates based on Monte Carlo (MC) dropout [4] in the context of deep networks for lesion detection and segmentation in medical images. Specifically, we develop a 3D MS lesion segmentation CNN, augmented to provide four different voxel-based uncertainty measures based on MC dropout. We train the network on a proprietary, large-scale, multi-site, multi-scanner, clinical MS dataset, and compute lesion-wise uncertainties by accumulating evidence from voxel-wise uncertainties within detected lesions. We analyze the performance of voxel-based segmentation and lesion-level detection by choosing operating points based on the uncertainty. Empirical evidence suggests that uncertainty measures consistently allow us to choose superior operating points compared only using the network's sigmoid output as a probability.

##### Abstract (translated by Google)
最近，深度学习（DL）网络在各种公共医学图像挑战数据集[3,11,16]上表现优于其他分割方法，特别是对于大型病理学。然而，在诸如多发性硬化症（MS）的疾病的背景下，监测MRI序列上可见的所有局灶性病变，甚至是非常小的病灶，对于疾病分期，预后和评估治疗功效是必需的。此外，产生确定性输出阻碍了DL在临床常规中的应用。预测的不确定性估计将允许临床医生随后进行修订。我们提出了基于蒙特卡罗（MC）辍学[4]的多重不确定性估计的第一次探索，用于医学图像中病变检测和分割的深度网络。具体而言，我们开发了3D MS病变分割CNN，增强以基于MC丢失提供四种不同的基于体素的不确定性测量。我们在专有的，大规模的，多站点，多扫描仪，临床MS数据集上训练网络，并通过从检测到的病变内的体素不确定性中积累证据来计算病变不确定性。我们通过基于不确定性选择操作点来分析基于体素的分割和病变水平检测的性能。经验证据表明，不确定性指标一致地允许我们选择优越的操作点，而仅使用网络的S形模型输出作为概率。

##### URL
[http://arxiv.org/abs/1808.01200](http://arxiv.org/abs/1808.01200)

##### PDF
[http://arxiv.org/pdf/1808.01200](http://arxiv.org/pdf/1808.01200)

