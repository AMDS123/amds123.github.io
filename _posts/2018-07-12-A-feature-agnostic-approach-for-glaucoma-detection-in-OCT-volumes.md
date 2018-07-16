---
layout: post
title: "A feature agnostic approach for glaucoma detection in OCT volumes"
date: 2018-07-12 22:57:19
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN CNN Classification Deep_Learning Detection
author: Stefan Maetschke, Bhavna Antony, Hiroshi Ishikawa, Rahil Garvani
mathjax: true
---

* content
{:toc}

##### Abstract
Optical coherence tomography (OCT) based measurements of retinal layer thickness, such as the retinal nerve fibre layer (RNFL) and the ganglion cell with inner plexiform layer (GCIPL) are commonly used for the diagnosis and monitoring of glaucoma. Previously, machine learning techniques have utilized segmentation-based imaging features such as the peripapillary RNFL thickness and the cup-to-disc ratio. Here, we propose a deep learning technique that classifies eyes as healthy or glaucomatous directly from raw, unsegmented OCT volumes of the optic nerve head (ONH) using a 3D Convolutional Neural Network (CNN). We compared the accuracy of this technique with various feature-based machine learning algorithms and demonstrated the superiority of the proposed deep learning based method. 
 Logistic regression was found to be the best performing classical machine learning technique with an AUC of 0.89. In direct comparison, the deep learning approach achieved a substantially higher AUC of 0.94 with the additional advantage of providing insight into which regions of an OCT volume are important for glaucoma detection. 
 Computing Class Activation Maps (CAM), we found that the CNN identified neuroretinal rim and optic disc cupping as well as the lamina cribrosa (LC) and its surrounding areas as the regions significantly associated with the glaucoma classification. These regions anatomically correspond to the well established and commonly used clinical markers for glaucoma diagnosis such as increased cup volume, cup diameter, and neuroretinal rim thinning at the superior and inferior segments.

##### Abstract (translated by Google)
基于光学相干断层扫描（OCT）的视网膜层厚度测量，例如视网膜神经纤维层（RNFL）和具有内丛状层（GCIPL）的神经节细胞，通常用于诊断和监测青光眼。以前，机器学习技术已经利用了基于分段的成像特征，例如周围的RNFL厚度和杯到盘比。在这里，我们提出了一种深度学习技术，使用3D卷积神经网络（CNN）直接从视神经乳头（ONH）的原始，未分段的OCT体积将眼睛分类为健康或青光眼。我们将该技术的准确性与各种基于特征的机器学习算法进行了比较，并证明了所提出的基于深度学习的方法的优越性。
 Logistic回归被发现是表现最佳的经典机器学习技术，AUC为0.89。在直接比较中，深度学习方法实现了显着更高的0.94的AUC，另外的优点是提供了对OCT体积的哪些区域对于青光眼检测是重要的的洞察。
 计算类激活图（CAM），我们发现CNN识别神经视网膜边缘和视盘拔罐以及筛状板（LC）及其周围区域作为与青光眼分类显着相关的区域。这些区域在解剖学上对应于用于青光眼诊断的成熟且常用的临床标志物，例如增加的杯体积，杯直径和在上段和下段的神经视网膜边缘变薄。

##### URL
[http://arxiv.org/abs/1807.04855](http://arxiv.org/abs/1807.04855)

##### PDF
[http://arxiv.org/pdf/1807.04855](http://arxiv.org/pdf/1807.04855)

