---
layout: post
title: "FatSegNet : A Fully Automated Deep Learning Pipeline for Adipose Tissue Segmentation on Abdominal Dixon MRI"
date: 2019-04-03 16:22:37
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: Santiago Estrada, Ran Lu, Sailesh Conjeti, Ximena Orozco-Ruiz, Joana Panos-Willuhn, Monique M.B Breteler, Martin Reuter
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: Development of a fast and fully automated deep learning pipeline (FatSegNet) to accurately identify, segment, and quantify abdominal adipose tissue on Dixon MRI from the Rhineland Study - a large prospective population-based study. Method: FatSegNet is composed of three stages: (i) consistent localization of the abdominal region using two 2D-Competitive Dense Fully Convolutional Networks (CDFNet), (ii) segmentation of adipose tissue on three views by independent CDFNets, and (iii) view aggregation. FatSegNet is trained with 33 manually annotated subjects, and validated by: 1) comparison of segmentation accuracy against a testingset covering a wide range of body mass index (BMI), 2) test-retest reliability, and 3) robustness in a large cohort study. Results: The CDFNet demonstrates increased robustness compared to traditional deep learning networks. FatSegNet dice score outperforms manual raters on the abdominal visceral adipose tissue (VAT, 0.828 vs. 0.788), and produces comparable results on subcutaneous adipose tissue (SAT, 0.973 vs. 0.982). The pipeline has very small test-retest absolute percentage difference and excellent agreement between scan sessions (VAT: APD = 2.957%, ICC=0.998 and SAT: APD= 3.254%, ICC=0.996). Conclusion: FatSegNet can reliably analyze a 3D Dixon MRI in1 min. It generalizes well to different body shapes, sensitively replicates known VAT and SAT volume effects in a large cohort study, and permits localized analysis of fat compartments.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02082](https://arxiv.org/abs/1904.02082)

##### PDF
[https://arxiv.org/pdf/1904.02082](https://arxiv.org/pdf/1904.02082)

