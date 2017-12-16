---
layout: post
title: "Virtual Blood Vessels in Complex Background using Stereo X-ray Images"
date: 2017-09-22 00:43:55
categories: arXiv_CV
tags: arXiv_CV Segmentation Quantitative
author: Qiuyu Chen, Ryoma Bise, Lin Gu, Yinqiang Zheng, Imari Sato, Jenq-Neng Hwang, Nobuaki Imanishi, Sadakazu Aiso
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a fully automatic system to reconstruct and visualize 3D blood vessels in Augmented Reality (AR) system from stereo X-ray images with bones and body fat. Currently, typical 3D imaging technologies are expensive and carrying the risk of irradiation exposure. To reduce the potential harm, we only need to take two X-ray images before visualizing the vessels. Our system can effectively reconstruct and visualize vessels in following steps. We first conduct initial segmentation using Markov Random Field and then refine segmentation in an entropy based post-process. We parse the segmented vessels by extracting their centerlines and generating trees. We propose a coarse-to-fine scheme for stereo matching, including initial matching using affine transform and dense matching using Hungarian algorithm guided by Gaussian regression. Finally, we render and visualize the reconstructed model in a HoloLens based AR system, which can essentially change the way of visualizing medical data. We have evaluated its performance by using synthetic and real stereo X-ray images, and achieved satisfactory quantitative and qualitative results.

##### Abstract (translated by Google)
我们提出了一个全自动的系统，用骨骼和身体脂肪的立体X射线图像，在增强现实（AR）系统中重建和可视化三维血管。目前，典型的3D成像技术是昂贵的并且存在辐照风险。为了减少潜在的危害，我们只需要在显示血管之前拍摄两张X射线图像。我们的系统可以在以下步骤中有效地重建和可视化船只。我们首先使用马尔科夫随机场进行初始分割，然后在基于熵的后处理中细化分割。我们通过提取中心线和生成树木来解析分段的船只。我们提出了一个从粗到细的立体匹配方案，包括使用仿射变换的初始匹配和使用高斯回归引导的匈牙利算法的稠密匹配。最后，我们在基于HoloLens的AR系统中渲染和可视化重建的模型，从根本上改变医学数据的可视化方式。我们使用合成和真实的立体X射线图像评估其性能，并取得了令人满意的定量和定性结果。

##### URL
[https://arxiv.org/abs/1709.07551](https://arxiv.org/abs/1709.07551)

##### PDF
[https://arxiv.org/pdf/1709.07551](https://arxiv.org/pdf/1709.07551)

