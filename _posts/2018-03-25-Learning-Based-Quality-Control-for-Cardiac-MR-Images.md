---
layout: post
title: "Learning-Based Quality Control for Cardiac MR Images"
date: 2018-03-25 21:49:55
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Detection
author: Giacomo Tarroni, Ozan Oktay, Wenjia Bai, Andreas Schuh, Hideaki Suzuki, Jonathan Passerat-Palmbach, Ben Glocker, Paul M. Matthews, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
The effectiveness of a cardiovascular magnetic resonance (CMR) scan depends on the ability of the operator to correctly tune the acquisition parameters to the subject being scanned and on the potential occurrence of imaging artefacts such as cardiac and respiratory motion. In clinical practice, a quality control step is performed by visual assessment of the acquired images: however, this procedure is strongly operator-dependent, cumbersome and sometimes incompatible with the time constraints in clinical settings and large-scale studies. We propose a fast, fully-automated, learning-based quality control pipeline for CMR images, specifically for short-axis image stacks. Our pipeline performs three important quality checks: 1) heart coverage estimation, 2) inter-slice motion detection, 3) image contrast estimation in the cardiac region. The pipeline uses a hybrid decision forest method - integrating both regression and structured classification models - to extract landmarks as well as probabilistic segmentation maps from both long- and short-axis images as a basis to perform the quality checks. The technique was tested on up to 3000 cases from the UK Biobank study and validated against manual annotations and visual inspections performed by expert interpreters. The results show the capability of the proposed pipeline to correctly detect incomplete or corrupted scans, allowing their exclusion from the analysed dataset or the triggering of a new acquisition.

##### Abstract (translated by Google)
心血管磁共振（CMR）扫描的有效性取决于操作员正确调整扫描对象的采集参数的能力以及可能发生的成像伪像，如心脏和呼吸运动。在临床实践中，质量控制步骤通过对获取的图像进行视觉评估来执行：然而，该过程强烈依赖于操作者，麻烦并且有时与临床环境和大规模研究中的时间限制不相容。我们针对CMR图像提出了一种快速，全自动，基于学习的质量控制管道，专门用于短轴图像堆栈。我们的管道执行三项重要的质量检查：1）心脏覆盖率估计，2）层间运动检测，3）心脏区域中的图像对比度估计。该流水线采用混合决策森林方法 - 整合回归和结构化分类模型 - 从长轴和短轴图像中提取地标以及概率分割图作为执行质量检查的基础。该技术在英国生物银行研究中的多达3000例病例中进行了测试，并通过专家口译员的手动注释和视觉检查进行了验证。结果显示所提出的流水线能够正确地检测不完整或损坏的扫描，从而允许从分析的数据集中排除它们或触发新的采集。

##### URL
[https://arxiv.org/abs/1803.09354](https://arxiv.org/abs/1803.09354)

##### PDF
[https://arxiv.org/pdf/1803.09354](https://arxiv.org/pdf/1803.09354)

