---
layout: post
title: "Multiple Sclerosis Lesion Segmentation from Brain MRI via Fully Convolutional Neural Networks"
date: 2018-03-24 22:43:16
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Quantitative
author: Snehashis Roy, John A. Butman, Daniel S. Reich, Peter A. Calabresi, Dzung L. Pham
mathjax: true
---

* content
{:toc}

##### Abstract
Multiple Sclerosis (MS) is an autoimmune disease that leads to lesions in the central nervous system. Magnetic resonance (MR) images provide sufficient imaging contrast to visualize and detect lesions, particularly those in the white matter. Quantitative measures based on various features of lesions have been shown to be useful in clinical trials for evaluating therapies. Therefore robust and accurate segmentation of white matter lesions from MR images can provide important information about the disease status and progression. In this paper, we propose a fully convolutional neural network (CNN) based method to segment white matter lesions from multi-contrast MR images. The proposed CNN based method contains two convolutional pathways. The first pathway consists of multiple parallel convolutional filter banks catering to multiple MR modalities. In the second pathway, the outputs of the first one are concatenated and another set of convolutional filters are applied. The output of this last pathway produces a membership function for lesions that may be thresholded to obtain a binary segmentation. The proposed method is evaluated on a dataset of 100 MS patients, as well as the ISBI 2015 challenge data consisting of 14 patients. The comparison is performed against four publicly available MS lesion segmentation methods. Significant improvement in segmentation quality over the competing methods is demonstrated on various metrics, such as Dice and false positive ratio. While evaluating on the ISBI 2015 challenge data, our method produces a score of 90.48, where a score of 90 is considered to be comparable to a human rater.

##### Abstract (translated by Google)
多发性硬化症（MS）是导致中枢神经系统损伤的自身免疫性疾病。磁共振（MR）图像提供足够的成像对比度来显现和检测病灶，尤其是白质中的病灶。基于病变各种特征的定量测量已被证明可用于评估治疗的临床试验。因此，MR图像白质病灶的健壮和准确分割可以提供有关疾病状态和进展的重要信息。在本文中，我们提出了一种基于全卷积神经网络（CNN）的方法来分割来自多对比MR图像的白质病灶。提出的基于CNN的方法包含两条卷积路径。第一路由多个并行卷积滤波器组组成，以适应多种MR模式。在第二条路径中，第一条路径的输出连接起来，另一组卷积滤波器被应用。最后一个途径的输出产生可被阈值化以得到二元分割的病变的隶属函数。所提出的方法在100个MS患者的数据集上进行评估，以及由14个患者组成的ISBI 2015挑战数据。该比较是针对四种公开可用的MS病灶分割方法进行的。在各种指标（如Dice和假阳性比率）上展示了与竞争方法相比分段质量的显着提高。在对ISBI 2015挑战数据进行评估时，我们的方法得分为90.48，其中90分被认为与人类评估者相当。

##### URL
[https://arxiv.org/abs/1803.09172](https://arxiv.org/abs/1803.09172)

##### PDF
[https://arxiv.org/pdf/1803.09172](https://arxiv.org/pdf/1803.09172)

