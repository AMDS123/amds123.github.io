---
layout: post
title: "Response monitoring of breast cancer on DCE-MRI using convolutional neural network-generated seed points and constrained volume growing"
date: 2018-11-22 09:02:41
categories: arXiv_CV
tags: arXiv_CV Segmentation Embedding CNN Deep_Learning Detection
author: Bas H.M. van der Velden, Bob D. de Vos, Claudette E. Loo, Hugo J. Kuijf, Ivana Isgum, Kenneth G.A. Gilhuijs
mathjax: true
---

* content
{:toc}

##### Abstract
Response of breast cancer to neoadjuvant chemotherapy (NAC) can be monitored using the change in visible tumor on magnetic resonance imaging (MRI). In our current workflow, seed points are manually placed in areas of enhancement likely to contain cancer. A constrained volume growing method uses these manually placed seed points as input and generates a tumor segmentation. This method is rigorously validated using complete pathological embedding. In this study, we propose to exploit deep learning for fast and automatic seed point detection, replacing manual seed point placement in our existing and well-validated workflow. The seed point generator was developed in early breast cancer patients with pathology-proven segmentations (N=100), operated shortly after MRI. It consisted of an ensemble of three independently trained fully convolutional dilated neural networks that classified breast voxels as tumor or non-tumor. Subsequently, local maxima were used as seed points for volume growing in patients receiving NAC (N=10). The percentage of tumor volume change was evaluated against semi-automatic segmentations. The primary cancer was localized in 95% of the tumors at the cost of 0.9 false positive per patient. False positives included focally enhancing regions of unknown origin and parts of the intramammary blood vessels. Volume growing from the seed points showed a median tumor volume decrease of 70% (interquartile range: 50%-77%), comparable to the semi-automatic segmentations (median: 70%, interquartile range 23%-76%). To conclude, a fast and automatic seed point generator was developed, fully automating a well-validated semi-automatic workflow for response monitoring of breast cancer to neoadjuvant chemotherapy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.09063](http://arxiv.org/abs/1811.09063)

##### PDF
[http://arxiv.org/pdf/1811.09063](http://arxiv.org/pdf/1811.09063)

