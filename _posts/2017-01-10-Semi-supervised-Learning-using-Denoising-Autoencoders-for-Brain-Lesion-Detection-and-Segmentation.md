---
layout: post
title: "Semi-supervised Learning using Denoising Autoencoders for Brain Lesion Detection and Segmentation"
date: 2017-01-10 04:59:00
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Weakly_Supervised Transfer_Learning Detection
author: Varghese Alex, Kiran Vaidhya, Subramaniam Thirunavukkarasu, Chandrasekharan Kesavdas, Ganapathy Krishnamurthi
mathjax: true
---

* content
{:toc}

##### Abstract
The work presented explores the use of denoising autoencoders (DAE) for brain lesion detection, segmentation and false positive reduction. Stacked denoising autoencoders (SDAE) were pre-trained using a large number of unlabeled patient volumes and fine tuned with patches drawn from a limited number of patients (n=20, 40, 65). The results show negligible loss in performance even when SDAE was fine tuned using 20 patients. Low grade glioma (LGG) segmentation was achieved using a transfer learning approach wherein a network pre-trained with High Grade Glioma (HGG) data was fine tuned using LGG image patches. The weakly supervised SDAE (for HGG) and transfer learning based LGG network were also shown to generalize well and provide good segmentation on unseen BraTS 2013 & BraTS 2015 test data. An unique contribution includes a single layer DAE, referred to as novelty detector(ND). ND was trained to accurately reconstruct non-lesion patches using a mean squared error loss function. The reconstruction error maps of test data were used to identify regions containing lesions. The error maps were shown to assign unique error distributions to various constituents of the glioma, enabling localization. The ND learns the non-lesion brain accurately as it was also shown to provide good segmentation performance on ischemic brain lesions in images from a different database.

##### Abstract (translated by Google)
提出的工作探讨了使用去噪自动编码器（DAE）进行脑损伤检测，分割和假阳性减少。使用大量未标记的患者体积预先训练堆叠的去噪自动编码器（SDAE），并且从少数患者（n = 20,40,65）中抽取补片进行微调。即使在使用20名患者进行SDAE调整时，结果显示性能损失可忽略不计。使用转移学习方法实现了低级别胶质瘤（LGG）分割，其中使用LGG图像补丁精细调整了使用高级神经胶质瘤（HGG）数据预训练的网络。弱监督的SDAE（用于HGG）和基于LGG网络的转移学习也显示出良好的推广，并且对看不见的BraTS 2013和BraTS 2015测试数据提供了良好的分割。一个独特的贡献包括一个单层DAE，称为新颖性检测器（ND）。 ND被训练为使用均方误差损失函数准确地重建非损伤贴片。使用测试数据的重建误差图来识别包含病灶的区域。错误地图显示分配独特的错误分布到各种成分的胶质瘤，使本地化。 ND可以准确地了解非病灶大脑，因为它也显示出对来自不同数据库的图像中的缺血性脑损伤提供良好的分割性能。

##### URL
[https://arxiv.org/abs/1611.08664](https://arxiv.org/abs/1611.08664)

##### PDF
[https://arxiv.org/pdf/1611.08664](https://arxiv.org/pdf/1611.08664)

