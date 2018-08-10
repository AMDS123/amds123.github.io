---
layout: post
title: "Multi-region segmentation of bladder cancer structures in MRI with progressive dilated convolutional networks"
date: 2018-08-09 14:33:46
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
膀胱壁和肿瘤区域的精确分割是朝向肿瘤分期和分级的非侵入性鉴定的关键步骤，这对于膀胱癌（BC）患者的治疗决策和预后是至关重要的。然而，磁共振图像（MRI）中膀胱壁和肿瘤的自动描绘是一项具有挑战性的任务，因为重要的膀胱形状变化，尿中强烈的强度不均匀性和跨群体的非常高的变异性，特别是在肿瘤外观上。为了解决这些问题，我们建议使用深度完全卷积神经网络。建议的网络包括扩张的卷积，以增加感受野，而不会产生额外的成本，也不会降低其性能。此外，我们在每个卷积块中引入渐进式扩张，从而实现广泛的感受野，而不需要大的扩张率。所提出的网络在来自60名经病理证实的BC患者的3.0T T2加权MRI扫描中进行评估。实验表明，该模型实现了高精度，内壁，外壁和肿瘤区域的平均Dice相似系数分别为0.98,0.84和0.69。与现有方法相比，这些结果与参考轮廓和性能的提高非常吻合。此外，整个3D体积的推理时间小于一秒，比此应用的相关最先进方法快2-3个数量级。我们发现CNN可以在MRI上对膀胱癌患者的膀胱壁和肿瘤进行精确分割。整个分割过程是全自动的，产生的结果与参考标准非常吻合，证明了深度学习模型对于膀胱癌MRI图像的自动多区域分割的可行性。

##### URL
[http://arxiv.org/abs/1805.10720](http://arxiv.org/abs/1805.10720)

##### PDF
[http://arxiv.org/pdf/1805.10720](http://arxiv.org/pdf/1805.10720)

