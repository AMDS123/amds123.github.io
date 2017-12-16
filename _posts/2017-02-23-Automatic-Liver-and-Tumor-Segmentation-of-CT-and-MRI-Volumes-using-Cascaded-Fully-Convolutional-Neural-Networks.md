---
layout: post
title: "Automatic Liver and Tumor Segmentation of CT and MRI Volumes using Cascaded Fully Convolutional Neural Networks"
date: 2017-02-23 15:02:59
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Quantitative
author: Patrick Ferdinand Christ, Florian Ettlinger, Felix Grün, Mohamed Ezzeldin A. Elshaera, Jana Lipkova, Sebastian Schlecht, Freba Ahmaddy, Sunil Tatavarty, Marc Bickel, Patrick Bilic, Markus Rempfler, Felix Hofmann, Melvin D Anastasi, Seyed-Ahmad Ahmadi, Georgios Kaissis, Julian Holch, Wieland Sommer, Rickmer Braren, Volker Heinemann, Bjoern Menze
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic segmentation of the liver and hepatic lesions is an important step towards deriving quantitative biomarkers for accurate clinical diagnosis and computer-aided decision support systems. This paper presents a method to automatically segment liver and lesions in CT and MRI abdomen images using cascaded fully convolutional neural networks (CFCNs) enabling the segmentation of a large-scale medical trial or quantitative image analysis. We train and cascade two FCNs for a combined segmentation of the liver and its lesions. In the first step, we train a FCN to segment the liver as ROI input for a second FCN. The second FCN solely segments lesions within the predicted liver ROIs of step 1. CFCN models were trained on an abdominal CT dataset comprising 100 hepatic tumor volumes. Validations on further datasets show that CFCN-based semantic liver and lesion segmentation achieves Dice scores over 94% for liver with computation times below 100s per volume. We further experimentally demonstrate the robustness of the proposed method on an 38 MRI liver tumor volumes and the public 3DIRCAD dataset.

##### Abstract (translated by Google)
肝脏和肝脏病变的自动分割是获得准确临床诊断和计算机辅助决策支持系统的定量生物标志物的重要步骤。本文提出了一种使用级联完全卷积神经网络（CFCN）自动分割CT和MRI腹部图像中的肝脏和病变的方法，从而实现了大规模医学试验或定量图像分析的分割。我们对两个FCN进行训练和级联，对肝脏及其病变进行组合分割。在第一步，我们训练一个FCN将肝脏分割成第二个FCN的ROI输入。第二个FCN仅在步骤1的预测的肝ROI内区分病变。在包含100个肝肿瘤体积的腹部CT数据集上训练CFCN模型。进一步数据集的验证表明，基于CFCN的语义肝脏和病灶分割对于肝脏的骰子分数达到94％以上，计算时间低于每体积100s。我们进一步实验证明了所提出的方法对38个MRI肝肿瘤体积和公共3DIRCAD数据集的鲁棒性。

##### URL
[https://arxiv.org/abs/1702.05970](https://arxiv.org/abs/1702.05970)

##### PDF
[https://arxiv.org/pdf/1702.05970](https://arxiv.org/pdf/1702.05970)

