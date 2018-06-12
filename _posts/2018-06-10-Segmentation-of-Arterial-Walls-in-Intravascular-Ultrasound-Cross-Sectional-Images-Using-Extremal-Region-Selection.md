---
layout: post
title: "Segmentation of Arterial Walls in Intravascular Ultrasound Cross-Sectional Images Using Extremal Region Selection"
date: 2018-06-10 17:37:11
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Quantitative Detection
author: Mehdi Faraji, Irene Cheng, Iris Naudin, Anup Basu
mathjax: true
---

* content
{:toc}

##### Abstract
Intravascular Ultrasound (IVUS) is an intra-operative imaging modality that facilitates observing and appraising the vessel wall structure of the human coronary arteries. Segmentation of arterial wall boundaries from the IVUS images is not only crucial for quantitative analysis of the vessel walls and plaque characteristics, but is also necessary for generating 3D reconstructed models of the artery. The aim of this study is twofold. Firstly, we investigate the feasibility of using a recently proposed region detector, namely Extremal Region of Extremum Level (EREL) to delineate the luminal and media-adventitia borders in IVUS frames acquired by 20 MHz probes. Secondly, we propose a region selection strategy to label two ERELs as lumen and media based on the stability of their textural information. We extensively evaluated our selection strategy on the test set of a standard publicly available dataset containing 326 IVUS B-mode images. We showed that in the best case, the average Hausdorff Distances (HD) between the extracted ERELs and the actual lumen and media were $0.22$ mm and $0.45$ mm, respectively. The results of our experiments revealed that our selection strategy was able to segment the lumen with $\le 0.3$ mm HD to the gold standard even though the images contained major artifacts such as bifurcations, shadows, and side branches. Moreover, when there was no artifact, our proposed method was able to delineate media-adventitia boundaries with $0.31$ mm HD to the gold standard. Furthermore, our proposed segmentation method runs in time that is linear in the number of pixels in each frame. Based on the results of this work, by using a 20 MHz IVUS probe with controlled pullback, not only can we now analyze the internal structure of human arteries more accurately, but also segment each frame during the pullback procedure because of the low run time of our proposed segmentation method.

##### Abstract (translated by Google)
血管内超声（IVUS）是一种手术中成像方式，有助于观察和评估人体冠状动脉的血管壁结构。来自IVUS图像的动脉壁边界的分割不仅对定量分析血管壁和斑块特征至关重要，而且对于产生动脉的3D重建模型也是必需的。这项研究的目的是双重的。首先，我们研究使用最近提出的区域检测器即Extremal Region of Extremum Level（EREL）来描绘20 MHz探针获得的IVUS帧中的腔和媒体 - 外膜边界的可行性。其次，我们提出了一个区域选择策略，根据其纹理信息的稳定性将两个EREL标记为流明和媒体。我们广泛评估了我们在包含326个IVUS B模式图像的标准公开可用数据集的测试集上的选择策略。我们表明，在最好的情况下，提取的EREL与实际流明和媒体之间的平均Hausdorff距离（HD）分别为0.22美元和0.45美元。我们的实验结果表明，我们的选择策略能够将流明分割成金色标准，即使图像包含诸如分叉，阴影和侧枝等主要伪像。此外，当没有人工产物时，我们提出的方法能够以0.31美元/平方米的HD标准来描述媒体 - 外膜界限。此外，我们提出的分割方法的运行时间与每帧中的像素数量成线性关系。基于这项工作的结果，通过使用具有受控回拉的20 MHz IVUS探头，我们不仅可以更准确地分析人体动脉的内部结构，而且还可以在回拉过程中分割每个帧，因为其运行时间较短我们提出的分割方法。

##### URL
[http://arxiv.org/abs/1806.03695](http://arxiv.org/abs/1806.03695)

##### PDF
[http://arxiv.org/pdf/1806.03695](http://arxiv.org/pdf/1806.03695)

