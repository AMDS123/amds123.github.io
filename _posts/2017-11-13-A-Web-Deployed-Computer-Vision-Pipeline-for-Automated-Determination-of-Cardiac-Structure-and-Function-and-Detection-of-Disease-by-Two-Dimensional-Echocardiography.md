---
layout: post
title: "A Web-Deployed Computer Vision Pipeline for Automated Determination of Cardiac Structure and Function and Detection of Disease by Two-Dimensional Echocardiography"
date: 2017-11-13 00:36:10
categories: arXiv_CV
tags: arXiv_CV Segmentation Tracking CNN Detection Relation
author: Jeffrey Zhang, Sravani Gajjala, Pulkit Agrawal, Geoffrey H. Tison, Laura A. Hallock, Lauren Beussink-Nelson, Eugene Fan, Mandar A. Aras, ChaRandle Jordan, Kirsten E. Fleischmann, Michelle Melisko, Atif Qasim, Alexei Efros, Sanjiv J. Shah, Ruzena Bajcsy, Rahul C. Deo
mathjax: true
---

* content
{:toc}

##### Abstract
Automated cardiac image interpretation has the potential to transform clinical practice in multiple ways including enabling low-cost serial assessment of cardiac function in the primary care and rural setting. We hypothesized that advances in computer vision could enable building a fully automated, scalable analysis pipeline for echocardiogram (echo) interpretation. Our approach entailed: 1) preprocessing; 2) convolutional neural networks (CNN) for view identification, image segmentation, and phasing of the cardiac cycle; 3) quantification of chamber volumes and left ventricular mass; 4) particle tracking to compute longitudinal strain; and 5) targeted disease detection. CNNs accurately identified views (e.g. 99% for apical 4-chamber) and segmented individual cardiac chambers. Cardiac structure measurements agreed with study report values (e.g. mean absolute deviations (MAD) of 7.7 mL/kg/m2 for left ventricular diastolic volume index, 2918 studies). We computed automated ejection fraction and longitudinal strain measurements (within 2 cohorts), which agreed with commercial software-derived values [for ejection fraction, MAD=5.3%, N=3101 studies; for strain, MAD=1.5% (n=175) and 1.6% (n=110)], and demonstrated applicability to serial monitoring of breast cancer patients for trastuzumab cardiotoxicity. Overall, we found that, compared to manual measurements, automated measurements had superior performance across seven internal consistency metrics with an average increase in the Spearman correlation coefficient of 0.05 (p=0.02). Finally, we developed disease detection algorithms for hypertrophic cardiomyopathy and cardiac amyloidosis, with C-statistics of 0.90 and 0.84, respectively. Our pipeline lays the groundwork for using automated interpretation to support point-of-care handheld cardiac ultrasound and large-scale analysis of the millions of echos archived within healthcare systems.

##### Abstract (translated by Google)
自动化的心脏图像解读有可能以多种方式改变临床实践，包括在初级保健和农村环境中实现对心脏功能的低成本系列评估。我们假设计算机视觉的进步可以为超声心动图（回声）解释建立一个全自动的，可扩展的分析流水线。我们的方法包括：1）预处理; 2）用于视图识别，图像分割和心动周期的定相的卷积神经网络（CNN）; 3）量化室容积和左心室质量; 4）粒子跟踪计算纵向应变; 5）有针对性的疾病检测。 CNN准确地识别视图（例如对于心尖四腔室99％）和分割的单个心腔室。心脏结构测量结果与研究报告值（例如左心室舒张容积指数为7.7mL / kg / m 2的平均绝对偏差（MAD），2918研究）一致。我们计算了自动射血分数和纵向应变测量值（在2个队列内），这与商业软件衍生值（射血分数，MAD = 5.3％，N = 3101研究;对于菌株，MAD = 1.5％（n = 175）和1.6％（n = 110）]，并证明了适用于连续监测乳腺癌患者的曲妥珠单抗心脏毒性。总体而言，我们发现，与手动测量相比，自动化测量在七个内部一致性度量标准方面具有优异的性能，Spearman相关系数平均增加0.05（p = 0.02）。最后，我们开发了肥厚型心肌病和心脏淀粉样变的疾病检测算法，C值分别为0.90和0.84。我们的工作流程为使用自动化解释来支持即时心脏手持式心脏超声波和大规模分析医疗系统中数百万回波提供了基础。

##### URL
[https://arxiv.org/abs/1706.07342](https://arxiv.org/abs/1706.07342)

##### PDF
[https://arxiv.org/pdf/1706.07342](https://arxiv.org/pdf/1706.07342)

