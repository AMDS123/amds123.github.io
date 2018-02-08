---
layout: post
title: "MRI Tumor Segmentation with Densely Connected 3D CNN"
date: 2018-01-18 05:16:26
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Quantitative
author: Lele Chen, Yue Wu, Adora M. DSouza, Anas Z. Abidin, Axel Wismuller, Chenliang Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Glioma is one of the most common and aggressive types of primary brain tumors. The accurate segmentation of subcortical brain structures is crucial to the study of gliomas in that it helps the monitoring of the progression of gliomas and aids the evaluation of treatment outcomes. However, the large amount of required human labor makes it difficult to obtain the manually segmented Magnetic Resonance Imaging (MRI) data, limiting the use of precise quantitative measurements in the clinical practice. In this work, we try to address this problem by developing a 3D Convolutional Neural Network~(3D CNN) based model to automatically segment gliomas. The major difficulty of our segmentation model comes with the fact that the location, structure, and shape of gliomas vary significantly among different patients. In order to accurately classify each voxel, our model captures multi-scale contextual information by extracting features from two scales of receptive fields. To fully exploit the tumor structure, we propose a novel architecture that hierarchically segments different lesion regions of the necrotic and non-enhancing tumor~(NCR/NET), peritumoral edema~(ED) and GD-enhancing tumor~(ET). Additionally, we utilize densely connected convolutional blocks to further boost the performance. We train our model with a patch-wise training schema to mitigate the class imbalance problem. The proposed method is validated on the BraTS 2017 dataset~\cite{DBLP:journals/tmi/MenzeJBKFKBPSWL15} and it achieves Dice scores of 0.72, 0.83 and 0.81 for the complete tumor, tumor core and enhancing tumor, respectively. These results are comparable to the reported state-of-the-art results, and our method is better than existing 3D-based methods in terms of compactness, time and space efficiency.

##### Abstract (translated by Google)
胶质瘤是原发性脑肿瘤中最常见的侵袭性类型之一。精确分割皮质下脑结构对于研究胶质瘤至关重要，因为它有助于监测神经胶质瘤的进展并有助于评估治疗结果。然而，大量的人力劳动使得手工分割的磁共振成像（MRI）数据难以获得，限制了在临床实践中使用精确的定量测量。在这项工作中，我们试图通过开发基于3D卷积神经网络（3D CNN）的模型来自动分割神经胶质瘤来解决这个问题。我们的分割模型的主要困难在于不同患者的胶质瘤的位置，结构和形状差异显着。为了准确地对每个体素进行分类，我们的模型通过从两个尺度的接受域中提取特征来捕获多尺度的上下文信息。为了充分利用肿瘤结构，我们提出了一种分层分割坏死和非增强肿瘤（NCR / NET），瘤周水肿（ED）和GD增强肿瘤（ET）的不同病变区域的新型结构。另外，我们使用密集连接的卷积块来进一步提高性能。我们训练我们的模型与补丁明智的训练模式，以缓解类失衡问题。所提出的方法在BraTS2017数据集上进行验证，并且对于完整的肿瘤，肿瘤核心和增强的肿瘤，其Dice分数分别为0.72,0.83和0.81。这些结果与已报道的最新结果相当，我们的方法在紧凑性，时间和空间效率方面比现有的基于3D的方法更好。

##### URL
[https://arxiv.org/abs/1802.02427](https://arxiv.org/abs/1802.02427)

##### PDF
[https://arxiv.org/pdf/1802.02427](https://arxiv.org/pdf/1802.02427)

