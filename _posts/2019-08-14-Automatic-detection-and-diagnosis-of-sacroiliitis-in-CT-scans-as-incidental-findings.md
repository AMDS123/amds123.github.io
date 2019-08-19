---
layout: post
title: "Automatic detection and diagnosis of sacroiliitis in CT scans as incidental findings"
date: 2019-08-14 18:51:34
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning Detection
author: Yigal Shenkman, Bilal Qutteineh, Leo Joskowicz, Adi Szeskin, Yusef Azraq, Arnaldo Mayer, Iris Eshed
mathjax: true
---

* content
{:toc}

##### Abstract
Early diagnosis of sacroiliitis may lead to preventive treatment which can significantly improve the patient's quality of life in the long run. Oftentimes, a CT scan of the lower back or abdomen is acquired for suspected back pain. However, since the differences between a healthy and an inflamed sacroiliac joint in the early stages are subtle, the condition may be missed. We have developed a new automatic algorithm for the diagnosis and grading of sacroiliitis CT scans as incidental findings, for patients who underwent CT scanning as part of their lower back pain workout. The method is based on supervised machine and deep learning techniques. The input is a CT scan that includes the patient's pelvis. The output is a diagnosis for each sacroiliac joint. The algorithm consists of four steps: 1) computation of an initial region of interest (ROI) that includes the pelvic joints region using heuristics and a U-Net classifier; 2) refinement of the ROI to detect both sacroiliac joints using a four-tree random forest; 3) individual sacroiliitis grading of each sacroiliac joint in each CT slice with a custom slice CNN classifier, and; 4) sacroiliitis diagnosis and grading by combining the individual slice grades using a random forest. Experimental results on 484 sacroiliac joints yield a binary and a 3-class case classification accuracy of 91.9% and 86%, a sensitivity of 95% and 82%, and an Area-Under-the-Curve of 0.97 and 0.57, respectively. Automatic computer-based analysis of CT scans has the potential of being a useful method for the diagnosis and grading of sacroiliitis as an incidental finding.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1908.05663](https://arxiv.org/abs/1908.05663)

##### PDF
[https://arxiv.org/pdf/1908.05663](https://arxiv.org/pdf/1908.05663)

