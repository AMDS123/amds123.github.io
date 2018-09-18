---
layout: post
title: "Learning-Based Quality Control for Cardiac MR Images"
date: 2018-09-15 09:36:00
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Detection
author: Giacomo Tarroni, Ozan Oktay, Wenjia Bai, Andreas Schuh, Hideaki Suzuki, Jonathan Passerat-Palmbach, Antonio de Marvao, Declan P. O&#x27;Regan, Stuart Cook, Ben Glocker, Paul M. Matthews, Daniel Rueckert
mathjax: true
---

* content
{:toc}

##### Abstract
The effectiveness of a cardiovascular magnetic resonance (CMR) scan depends on the ability of the operator to correctly tune the acquisition parameters to the subject being scanned and on the potential occurrence of imaging artefacts such as cardiac and respiratory motion. In the clinical practice, a quality control step is performed by visual assessment of the acquired images: however, this procedure is strongly operator-dependent, cumbersome and sometimes incompatible with the time constraints in clinical settings and large-scale studies. We propose a fast, fully-automated, learning-based quality control pipeline for CMR images, specifically for short-axis image stacks. Our pipeline performs three important quality checks: 1) heart coverage estimation, 2) inter-slice motion detection, 3) image contrast estimation in the cardiac region. The pipeline uses a hybrid decision forest method - integrating both regression and structured classification models - to extract landmarks as well as probabilistic segmentation maps from both long- and short-axis images as a basis to perform the quality checks. The technique was tested on up to 3000 cases from the UK Biobank as well as on 100 cases from the UK Digital Heart Project, and validated against manual annotations and visual inspections performed by expert interpreters. The results show the capability of the proposed pipeline to correctly detect incomplete or corrupted scans (e.g. on UK Biobank, sensitivity and specificity respectively 88% and 99% for heart coverage estimation, 85% and 95% for motion detection), allowing their exclusion from the analysed dataset or the triggering of a new acquisition.

##### Abstract (translated by Google)
心血管磁共振（CMR）扫描的有效性取决于操作者正确地调整被扫描对象的采集参数以及可能出现的成像假象（例如心脏和呼吸运动）的能力。在临床实践中，通过对获得的图像进行视觉评估来执行质量控制步骤：然而，该过程强烈依赖于操作者，麻烦且有时与临床设置和大规模研究中的时间限制不相容。我们为CMR图像提供了一种快速，全自动，基于学习的质量控制管道，专门用于短轴图像堆栈。我们的管道执行三项重要的质量检查：1）心脏覆盖率估计，2）切片间运动检测，3）心脏区域中的图像对比度估计。该管道使用混合决策森林方法 - 整合回归和结构化分类模型 - 从长轴和短轴图像中提取地标以及概率分割图，作为执行质量检查的基础。该技术在来自英国生物银行的多达3000个案例以及来自英国数字心脏项目的100个案例中进行了测试，并通过专家口译员进行的人工注释和目视检查进行了验证。结果显示所提出的管道能够正确检测不完整或损坏的扫描（例如，英国生物库，灵敏度和特异性分别为心脏覆盖率估计的88％和99％，运动检测的85％和95％），允许将它们排除在外分析的数据集或触发新的采集。

##### URL
[http://arxiv.org/abs/1803.09354](http://arxiv.org/abs/1803.09354)

##### PDF
[http://arxiv.org/pdf/1803.09354](http://arxiv.org/pdf/1803.09354)

