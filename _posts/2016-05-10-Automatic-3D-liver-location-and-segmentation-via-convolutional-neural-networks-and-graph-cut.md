---
layout: post
title: "Automatic 3D liver location and segmentation via convolutional neural networks and graph cut"
date: 2016-05-10 13:42:51
categories: arXiv_CV
tags: arXiv_CV Segmentation Face CNN Deep_Learning Quantitative Detection Relation
author: Fang Lu, Fa Wu, Peijun Hu, Zhiyi Peng, Dexing Kong
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose Segmentation of the liver from abdominal computed tomography (CT) image is an essential step in some computer assisted clinical interventions, such as surgery planning for living donor liver transplant (LDLT), radiotherapy and volume measurement. In this work, we develop a deep learning algorithm with graph cut refinement to automatically segment liver in CT scans. Methods The proposed method consists of two main steps: (i) simultaneously liver detection and probabilistic segmentation using 3D convolutional neural networks (CNNs); (ii) accuracy refinement of initial segmentation with graph cut and the previously learned probability map. Results The proposed approach was validated on forty CT volumes taken from two public databases MICCAI-Sliver07 and 3Dircadb. For the MICCAI-Sliver07 test set, the calculated mean ratios of volumetric overlap error (VOE), relative volume difference (RVD), average symmetric surface distance (ASD), root mean square symmetric surface distance (RMSD) and maximum symmetric surface distance (MSD) are 5.9%, 2.7%, 0.91%, 1.88 mm, and 18.94 mm, respectively. In the case of 20 3Dircadb data, the calculated mean ratios of VOE, RVD, ASD, RMSD and MSD are 9.36%, 0.97%, 1.89%, 4.15 mm and 33.14 mm, respectively. Conclusion The proposed method is fully automatic without any user interaction. Quantitative results reveal that the proposed approach is efficient and accurate for hepatic volume estimation in a clinical setup. The high correlation between the automatic and manual references shows that the proposed method can be good enough to replace the time-consuming and non-reproducible manual segmentation method.

##### Abstract (translated by Google)
目的从腹部计算机断层扫描（CT）图像中分割肝脏是一些计算机辅助临床干预中不可缺少的步骤，例如活体肝移植（LDLT）的手术规划，放射治疗和体积测量。在这项工作中，我们开发了一种深度学习算法，通过图形细化来自动分割CT扫描中的肝脏。方法提出的方法包括两个主要步骤:(一）同时肝检测和概率分割使用三维卷积神经网络（CNNs）; （ii）利用图形切割和先前学习的概率图精确地完成初始分割。结果所提出的方法在来自两个公共数据库MICCAI-Sliver07和3Dircadb的四十个CT卷上进行了验证。对于MICCAI-Sliver07测试集，计算的体积重叠误差（VOE），相对体积差（RVD），平均对称表面距离（ASD），均方根对称表面距离（RMSD）和最大对称表面距离MSD）分别为5.9％，2.7％，0.91％，1.88mm和18.94mm。在20个3Dircadb数据的情况下，VOE，RVD，ASD，RMSD和MSD的计算平均比率分别为9.36％，0.97％，1.89％，4.15mm和33.14mm。结论所提出的方法是全自动的，没有任何用户交互。定量结果表明，所提出的方法是有效和准确的肝体积估计在临床设置。自动和手动参考之间的高度相关性表明，所提出的方法可以很好地替代耗时且不可重现的手动分割方法。

##### URL
[https://arxiv.org/abs/1605.03012](https://arxiv.org/abs/1605.03012)

##### PDF
[https://arxiv.org/pdf/1605.03012](https://arxiv.org/pdf/1605.03012)

