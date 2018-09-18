---
layout: post
title: "Left Ventricle Segmentation and Volume Estimation on Cardiac MRI using Deep Learning"
date: 2018-09-14 06:40:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning Detection
author: Ehab Abdelmaguid, Jolene Huang, Sanjay Kenchareddy, Disha Singla, Laura Wilke, Mai H. Nguyen, Ilkay Altintas
mathjax: true
---

* content
{:toc}

##### Abstract
In the United States, heart disease is the leading cause of death for males and females, accounting for 610,000 deaths each year [1]. Physicians use Magnetic Resonance Imaging (MRI) scans to take images of the heart in order to non-invasively estimate its structural and functional parameters for cardiovascular diagnosis and disease management. The end-systolic volume (ESV) and end-diastolic volume (EDV) of the left ventricle (LV), and the ejection fraction (EF) are indicators of heart disease. These measures can be derived from the segmented contours of the LV; thus, consistent and accurate segmentation of the LV from MRI images are critical to the accuracy of the ESV, EDV, and EF, and to non-invasive cardiac disease detection. 
 In this work, various image preprocessing techniques, model configurations using the U-Net deep learning architecture, postprocessing methods, and approaches for volume estimation are investigated. An end-to-end analytics pipeline with multiple stages is provided for automated LV segmentation and volume estimation. First, image data are reformatted and processed from DICOM and NIfTI formats to raw images in array format. Secondly, raw images are processed with multiple image preprocessing methods and cropped to include only the Region of Interest (ROI). Thirdly, preprocessed images are segmented using U-Net models. Lastly, post processing of segmented images to remove extra contours along with intelligent slice and frame selection are applied, followed by calculation of the ESV, EDV, and EF. This analytics pipeline is implemented and runs on a distributed computing environment with a GPU cluster at the San Diego Supercomputer Center at UCSD.

##### Abstract (translated by Google)
在美国，心脏病是男性和女性死亡的主要原因，每年导致61万人死亡[1]。医生使用磁共振成像（MRI）扫描来拍摄心脏图像，以便非侵入性地估计其心血管诊断和疾病管理的结构和功能参数。左心室的收缩末期容积（ESV）和舒张末期容积（EDV）以及射血分数（EF）是心脏病的指标。这些测量可以从LV的分段轮廓得出;因此，从MRI图像中一致和准确地分割LV对于ESV，EDV和EF的准确性以及非侵入性心脏病检测是至关重要的。
 在这项工作中，研究了各种图像预处理技术，使用U-Net深度学习架构的模型配置，后处理方法和体积估计方法。为自动LV分段和体积估计提供了具有多个阶段的端到端分析管道。首先，图像数据被重新格式化并从DICOM和NIfTI格式处理成阵列格式的原始图像。其次，使用多种图像预处理方法处理原始图像，并将其裁剪为仅包括感兴趣区域（ROI）。第三，使用U-Net模型分割预处理的图像。最后，应用分段图像的后处理以去除额外的轮廓以及智能切片和帧选择，然后计算ESV，EDV和EF。此分析管道在加州大学圣地亚哥分校的圣地亚哥超级计算机中心的分布式计算环境中实施并运行。

##### URL
[http://arxiv.org/abs/1809.06247](http://arxiv.org/abs/1809.06247)

##### PDF
[http://arxiv.org/pdf/1809.06247](http://arxiv.org/pdf/1809.06247)

