---
layout: post
title: "The utility of a convolutional neural network for generating a myelin volume index map from rapid simultaneous relaxometry imaging"
date: 2019-04-24 06:50:22
categories: arXiv_AI
tags: arXiv_AI CNN Relation
author: Yasuhiko Tachibana (1 and 2), Akifumi Hagiwara (2 and 3), Masaaki Hori (2), Jeff Kershaw (1), Misaki Nakazawa (2), Tokuhiko Omatsu (1), Riwa Kishimoto (1), Kazumasa Yokoyama (4), Nobutaka Hattori (4), Shigeki Aoki (2), Tatsuya Higashi (5), Takayuki Obata (1 and 5) ((1) Applied MRI Research, Department of Molecular imaging and Theranostics, National Institute of Radiological Sciences, QST, (2) Department of Radiology, Juntendo University School of Medicine, (3) Department of Radiology, Graduate School of Medicine, The University of Tokyo, (4) Department of Neurology, Juntendo University School of Medicine, (5) Department of Molecular imaging and Theranostics, National Institute of Radiological Sciences, QST)
mathjax: true
---

* content
{:toc}

##### Abstract
Background and Purpose: A current algorithm to obtain a synthetic myelin volume fraction map (SyMVF) from rapid simultaneous relaxometry imaging (RSRI) has a potential problem, that it does not incorporate information from surrounding pixels. The purpose of this study was to develop a method that utilizes a convolutional neural network (CNN) to overcome this problem. Methods: RSRI and magnetization transfer images from 20 healthy volunteers were included. A CNN was trained to reconstruct RSRI-related metric maps into a myelin volume-related index (generated myelin volume index: GenMVI) map using the myelin volume index map calculated from magnetization transfer images (MTMVI) as reference. The SyMVF and GenMVI maps were statistically compared by testing how well they correlated with the MTMVI map. The correlations were evaluated based on: (i) averaged values obtained from 164 atlas-based ROIs, and (ii) pixel-based comparison for ROIs defined in four different tissue types (cortical and subcortical gray matter, white matter, and whole brain). Results: For atlas-based ROIs, the overall correlation with the MTMVI map was higher for the GenMVI map than for the SyMVF map. In the pixel-based comparison, correlation with the MTMVI map was stronger for the GenMVI map than for the SyMVF map, and the difference in the distribution for the volunteers was significant (Wilcoxon sign-rank test, P&lt;.001) in all tissue types. Conclusion: The proposed method is useful, as it can incorporate more specific information about local tissue properties than the existing method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10960](http://arxiv.org/abs/1904.10960)

##### PDF
[http://arxiv.org/pdf/1904.10960](http://arxiv.org/pdf/1904.10960)

