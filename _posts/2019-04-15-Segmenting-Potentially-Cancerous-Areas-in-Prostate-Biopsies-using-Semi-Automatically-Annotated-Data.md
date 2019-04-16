---
layout: post
title: "Segmenting Potentially Cancerous Areas in Prostate Biopsies using Semi-Automatically Annotated Data"
date: 2019-04-15 11:18:27
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Nikolay Burlutskiy, Nicolas Pinchaud, Feng Gu, Daniel H&#xe4;gg, Mats Andersson, Lars Bj&#xf6;rk, Kristian Eur&#xe9;n, Cristina Svensson, Lena Kajland Wil&#xe9;n, Martin Hedlund
mathjax: true
---

* content
{:toc}

##### Abstract
Gleason grading specified in ISUP 2014 is the clinical standard in staging prostate cancer and the most important part of the treatment decision. However, the grading is subjective and suffers from high intra and inter-user variability. To improve the consistency and objectivity in the grading, we introduced glandular tissue WithOut Basal cells (WOB) as the ground truth. The presence of basal cells is the most accepted biomarker for benign glandular tissue and the absence of basal cells is a strong indicator of acinar prostatic adenocarcinoma, the most common form of prostate cancer. Glandular tissue can objectively be assessed as WOB or not WOB by using specific immunostaining for glandular tissue (Cytokeratin 8/18) and for basal cells (Cytokeratin 5/6 + p63). Even more, WOB allowed us to develop a semi-automated data generation pipeline to speed up the tremendously time consuming and expensive process of annotating whole slide images by pathologists. We generated 295 prostatectomy images exhaustively annotated with WOB. Then we used our Deep Learning Framework, which achieved the $2^{nd}$ best reported score in Camelyon17 Challenge, to train networks for segmenting WOB in needle biopsies. Evaluation of the model on 63 needle biopsies showed promising results which were improved further by finetuning the model on 118 biopsies annotated with WOB, achieving F1-score of 0.80 and Precision-Recall AUC of 0.89 at the pixel-level. Then we compared the performance of the model against 17 biopsies annotated independently by 3 pathologists using only H\&amp;E staining. The comparison demonstrated that the model performed on a par with the pathologists. Finally, the model detected and accurately outlined existing WOB areas in two biopsies incorrectly annotated as totally WOB-free biopsies by three pathologists and in one biopsy by two pathologists.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.06969](http://arxiv.org/abs/1904.06969)

##### PDF
[http://arxiv.org/pdf/1904.06969](http://arxiv.org/pdf/1904.06969)

