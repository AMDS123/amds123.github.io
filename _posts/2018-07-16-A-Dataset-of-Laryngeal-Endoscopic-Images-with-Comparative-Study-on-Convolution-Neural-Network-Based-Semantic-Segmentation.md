---
layout: post
title: "A Dataset of Laryngeal Endoscopic Images with Comparative Study on Convolution Neural Network Based Semantic Segmentation"
date: 2018-07-16 19:56:13
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference
author: Max-Heinrich Laves, Jens Bicker, L&#xfc;der A. Kahrs, Tobias Ortmaier
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: Automated segmentation of anatomical structures in medical image analysis is a key step in defining topology to enable or assist autonomous intervention robots. Recent methods based on deep convolutional neural networks (CNN) have outperformed former heuristic methods. However, those methods were primarily evaluated on rigid, real-world environments. In this study, we evaluate existing segmentation methods for their use with soft tissue. Methods: The four CNN-based methods SegNet, UNet, ENet and ErfNet are trained with high supervision on a novel 7-class dataset of surgeries on the human larynx. The dataset contains 400 manually segmented images from two patients during laser incisions. The Intersection-over-Union (IoU) evaluation metric is used to measure the accuracy of each method. Stochastic inference is used to show the uncertainty of the individual models. Results: Our study shows that ErfNet is best suited for laryngeal soft tissue with a mean IoU of 48.6 %. The highest efficiency is achieved by ENet with a mean inference time of 9.22 ms per image on an NVIDIA GeForce GTX 1080 Ti GPGPU. Conclusion: CNN-based methods for semantic segmentation are applicable to laryngeal soft tissue. The segmentation can be used for active constraints or autonomous control in robot-assisted laser surgery. Further improvements could be achieved by using a larger dataset or training the models in a self-supervised manner.

##### Abstract (translated by Google)
目的：医学图像分析中解剖结构的自动分割是定义拓扑以启用或辅助自主干预机器人的关键步骤。最近基于深度卷积神经网络（CNN）的方法优于以前的启发式方法。但是，这些方法主要是在严格的现实环境中进行评估的。在本研究中，我们评估了现有的分割方法，用于软组织。方法：基于CNN的四种方法SegNet，UNet，ENet和ErfNet在一个新的7级人体喉部手术数据集上受到高度监督。该数据集包含来自激光切口期间两名患者的400个手动分割图像。联合交叉（IoU）评估度量用于衡量每种方法的准确性。随机推断用于显示各个模型的不确定性。结果：我们的研究表明，ErfNet最适合喉部软组织，平均IoU为48.6％。 ENet实现了最高效率，NVIDIA GeForce GTX 1080 Ti GPGPU的每幅图像的平均推断时间为9.22 ms。结论：基于CNN的语义分割方法适用于喉部软组织。该分割可用于机器人辅助激光手术中的主动约束或自主控制。通过使用更大的数据集或以自我监督的方式训练模型，可以实现进一步的改进。

##### URL
[http://arxiv.org/abs/1807.06081](http://arxiv.org/abs/1807.06081)

##### PDF
[http://arxiv.org/pdf/1807.06081](http://arxiv.org/pdf/1807.06081)

