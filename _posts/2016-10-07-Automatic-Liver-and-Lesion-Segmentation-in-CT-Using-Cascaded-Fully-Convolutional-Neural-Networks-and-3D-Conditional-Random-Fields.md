---
layout: post
title: "Automatic Liver and Lesion Segmentation in CT Using Cascaded Fully Convolutional Neural Networks and 3D Conditional Random Fields"
date: 2016-10-07 08:23:32
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Quantitative
author: Patrick Ferdinand Christ, Mohamed Ezzeldin A. Elshaer, Florian Ettlinger, Sunil Tatavarty, Marc Bickel, Patrick Bilic, Markus Rempfler, Marco Armbruster, Felix Hofmann, Melvin D'Anastasi, Wieland H. Sommer, Seyed-Ahmad Ahmadi, Bjoern H. Menze
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic segmentation of the liver and its lesion is an important step towards deriving quantitative biomarkers for accurate clinical diagnosis and computer-aided decision support systems. This paper presents a method to automatically segment liver and lesions in CT abdomen images using cascaded fully convolutional neural networks (CFCNs) and dense 3D conditional random fields (CRFs). We train and cascade two FCNs for a combined segmentation of the liver and its lesions. In the first step, we train a FCN to segment the liver as ROI input for a second FCN. The second FCN solely segments lesions from the predicted liver ROIs of step 1. We refine the segmentations of the CFCN using a dense 3D CRF that accounts for both spatial coherence and appearance. CFCN models were trained in a 2-fold cross-validation on the abdominal CT dataset 3DIRCAD comprising 15 hepatic tumor volumes. Our results show that CFCN-based semantic liver and lesion segmentation achieves Dice scores over 94% for liver with computation times below 100s per volume. We experimentally demonstrate the robustness of the proposed method as a decision support system with a high accuracy and speed for usage in daily clinical routine.

##### Abstract (translated by Google)
肝脏及其病变的自动分割是获取定量生物标记物以准确临床诊断和计算机辅助决策支持系统的重要步骤。本文提出了一种使用级联完全卷积神经网络（CFCN）和密集的三维条件随机场（CRF）自动分割CT腹部图像中的肝脏和病灶的方法。我们对两个FCN进行训练和级联，对肝脏及其病变进行组合分割。在第一步，我们训练一个FCN将肝脏分割成第二个FCN的ROI输入。第二个FCN仅从步骤1的预测的肝脏ROI中分割出病灶。我们使用密集的3D CRF来细化CFCN的分割，这涉及空间相干性和外观。 CFCN模型在包含15个肝肿瘤体积的腹部CT数据集3DIRCAD上进行2倍交叉验证。我们的研究结果表明，基于CFCN的语义肝脏和病灶分割对于肝脏的骰子分数达到94％以上，计算时间低于每个体积100s。我们通过实验证明了所提出的方法作为一个决策支持系统的稳健性，在日常临床常规中具有很高的准确性和速度。

##### URL
[https://arxiv.org/abs/1610.02177](https://arxiv.org/abs/1610.02177)

##### PDF
[https://arxiv.org/pdf/1610.02177](https://arxiv.org/pdf/1610.02177)

