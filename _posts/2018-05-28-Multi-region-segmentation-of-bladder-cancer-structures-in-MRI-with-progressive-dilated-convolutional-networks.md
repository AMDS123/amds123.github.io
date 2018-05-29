---
layout: post
title: "Multi-region segmentation of bladder cancer structures in MRI with progressive dilated convolutional networks"
date: 2018-05-28 00:28:56
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Inference Deep_Learning
author: Jose Dolz, Xiaopan Xu, Jerome Rony, Jing Yuan, Yang Liu, Eric Granger, Christian Desrosiers, Xi Zhang, Ismail Ben Ayed, Hongbing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Precise segmentation of bladder walls and tumor regions is an essential step towards non-invasive identification of tumor stage and grade, which is critical for treatment decision and prognosis of patients with bladder cancer (BC). However, the automatic delineation of bladder walls and tumor in magnetic resonance images (MRI) is a challenging task, due to important bladder shape variations, strong intensity inhomogeneity in urine and very high variability across population, particularly on tumors appearance. To tackle these issues, we propose to use a deep fully convolutional neural network. The proposed network includes dilated convolutions to increase the receptive field without incurring extra cost nor degrading its performance. Furthermore, we introduce progressive dilations in each convolutional block, thereby enabling extensive receptive fields without the need for large dilation rates. The proposed network is evaluated on 3.0T T2-weighted MRI scans from 60 pathologically confirmed patients with BC. Experiments shows the proposed model to achieve high accuracy, with a mean Dice similarity coefficient of 0.98, 0.84 and 0.69 for inner wall, outer wall and tumor region, respectively. These results represent a very good agreement with reference contours and an increase in performance compared to existing methods. In addition, inference times are less than a second for a whole 3D volume, which is between 2-3 orders of magnitude faster than related state-of-the-art methods for this application. We showed that a CNN can yield precise segmentation of bladder walls and tumors in bladder cancer patients on MRI. The whole segmentation process is fully-automatic and yields results in very good agreement with the reference standard, demonstrating the viability of deep learning models for the automatic multi-region segmentation of bladder cancer MRI images.

##### Abstract (translated by Google)
精确分割膀胱壁和肿瘤区域是非侵入性识别肿瘤分期和分级的必要步骤，这对于膀胱癌（BC）患者的治疗决策和预后至关重要。然而，磁共振图像（MRI）中膀胱壁和肿瘤的自动描绘是一项具有挑战性的任务，这是由于膀胱形状的重要变化，尿液中强烈的不均匀性以及人群中非常高的变异性，特别是在肿瘤外观上。为了解决这些问题，我们建议使用深度完全卷积神经网络。拟议的网络包括扩张卷积以增加接受领域而不引起额外费用或降低其表现。此外，我们在每个卷积块中引入渐进式扩张，从而使扩大的接受场不需要大的扩张速率。所提出的网络在来自60位病理证实的BC患者的3.0T T2加权MRI扫描上进行评估。实验表明，所提出的模型实现了高精度，对于内壁，外壁和肿瘤区域，平均Dice相似系数分别为0.98,0.84和0.69。这些结果与参考轮廓非常吻合，与现有方法相比性能有所提高。此外，对于整个3D体积，推断时间不到一秒钟，这比该应用的相关最先进方法快2-3个数量级。我们发现CNN可以在MRI上对膀胱癌患者的膀胱壁和肿瘤进行精确分割。整个分割过程是全自动的，并产生与参考标准非常吻合的结果，证明了用于膀胱癌MRI图像的自动多区域分割的深度学习模型的可行性。

##### URL
[http://arxiv.org/abs/1805.10720](http://arxiv.org/abs/1805.10720)

##### PDF
[http://arxiv.org/pdf/1805.10720](http://arxiv.org/pdf/1805.10720)

