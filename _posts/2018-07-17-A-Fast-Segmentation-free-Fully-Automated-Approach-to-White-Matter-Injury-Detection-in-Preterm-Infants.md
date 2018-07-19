---
layout: post
title: "A Fast Segmentation-free Fully Automated Approach to White Matter Injury Detection in Preterm Infants"
date: 2018-07-17 18:00:26
categories: arXiv_CV
tags: arXiv_CV Segmentation Detection
author: Subhayan Mukherjee, Irene Cheng, Steven Miller, Jessie Guo, Vann Chau, Anup Basu
mathjax: true
---

* content
{:toc}

##### Abstract
White Matter Injury (WMI) is the most prevalent brain injury in the preterm neonate leading to developmental deficits. However, detecting WMI in Magnetic Resonance (MR) images of preterm neonate brains using traditional WM segmentation-based methods is difficult mainly due to lack of reliable preterm neonate brain atlases to guide segmentation. Hence, we propose a segmentation-free, fast, unsupervised, atlas-free WMI detection method. We detect the ventricles as blobs using a fast linear Maximally Stable Extremal Regions algorithm. A reference contour equidistant from the blobs and the brain-background boundary is used to identify tissue adjacent to the blobs. Assuming normal distribution of the gray-value intensity of this tissue, the outlier intensities in the entire brain region are identified as potential WMI candidates. Thereafter, false positives are discriminated using appropriate heuristics. Experiments using an expert-annotated dataset show that the proposed method runs 20 times faster than our earlier work which relied on time-consuming segmentation of the WM region, without compromising WMI detection accuracy.

##### Abstract (translated by Google)
白质损伤（WMI）是早产新生儿中最常见的脑损伤，导致发育缺陷。然而，使用传统的基于WM分割的方法检测早产新生大脑的磁共振（MR）图像中的WMI是困难的，这主要是由于缺乏可靠的早产新生儿脑图谱来指导分割。因此，我们提出了一种无分割，快速，无监督，无图谱的WMI检测方法。我们使用快速线性Maximally Stable Extremal Regions算法将心室检测为斑点。与斑点等距的参考轮廓和脑 - 背景边界用于识别与斑点相邻的组织。假设该组织的灰度值强度的正态分布，整个脑区域中的离群值强度被识别为潜在的WMI候选者。此后，使用适当的启发法区分误报。使用专家注释数据集的实验表明，所提出的方法运行速度比我们之前的工作快20倍，后者依赖于WM区域的耗时分段，而不会影响WMI检测精度。

##### URL
[https://arxiv.org/abs/1807.06604](https://arxiv.org/abs/1807.06604)

##### PDF
[https://arxiv.org/pdf/1807.06604](https://arxiv.org/pdf/1807.06604)

