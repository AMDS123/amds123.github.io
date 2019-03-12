---
layout: post
title: "Learning-Based Cost Functions for 3D and 4D Multi-Surface Multi-Object Segmentation of Knee MRI: Data from the Osteoarthritis Initiative"
date: 2019-03-10 05:48:53
categories: arXiv_CV
tags: arXiv_CV Segmentation Face
author: Satyananda Kashyap, Honghai Zhang, Karan Rao, Milan Sonka
mathjax: true
---

* content
{:toc}

##### Abstract
A fully automated knee MRI segmentation method to study osteoarthritis (OA) was developed using a novel hierarchical set of random forests (RF) classifiers to learn the appearance of cartilage regions and their boundaries. A neighborhood approximation forest is used first to provide contextual feature to the second-level RF classifier that also considers local features and produces location-specific costs for the layered optimal graph image segmentation of multiple objects and surfaces (LOGISMOS) framework. Double echo steady state (DESS) MRIs used in this work originated from the Osteoarthritis Initiative (OAI) study. Trained on 34 MRIs with varying degrees of OA, the performance of the learning-based method tested on 108 MRIs showed a significant reduction in segmentation errors (\emph{p}$<$0.05) compared with the conventional gradient-based and single-stage RF-learned costs. The 3D LOGISMOS was extended to longitudinal-3D (4D) to simultaneously segment multiple follow-up visits of the same patient. As such, data from all time-points of the temporal sequence contribute information to a single optimal solution that utilizes both spatial 3D and temporal contexts. 4D LOGISMOS validation on 108 MRIs from baseline and 12 month follow-up scans of 54 patients showed a significant reduction in segmentation errors (\emph{p}$<$0.01) compared to 3D. Finally, the potential of 4D LOGISMOS was further explored on the same 54 patients using 5 annual follow-up scans demonstrating a significant improvement of measuring cartilage thickness (\emph{p}$<$0.01) compared to the sequential 3D approach.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1903.03927](https://arxiv.org/abs/1903.03927)

##### PDF
[https://arxiv.org/pdf/1903.03927](https://arxiv.org/pdf/1903.03927)

