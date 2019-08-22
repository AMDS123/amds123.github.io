---
layout: post
title: "Adaptive Segmentation of Knee Radiographs for Selecting the Optimal ROI in Texture Analysis"
date: 2019-08-21 07:48:02
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification
author: Neslihan Bayramoglu, Aleksei Tiulpin, Jukka Hirvasniemi, Miika T. Nieminen, Simo Saarakkala
mathjax: true
---

* content
{:toc}

##### Abstract
The purposes of this study were to investigate: 1) the effect of placement of region-of-interest (ROI) for texture analysis of subchondral bone in knee radiographs, and 2) the ability of several texture descriptors to distinguish between the knees with and without radiographic osteoarthritis (OA). Bilateral posterior-anterior knee radiographs were analyzed from the baseline of OAI and MOST datasets. A fully automatic method to locate the most informative region from subchondral bone using adaptive segmentation was developed. We used an oversegmentation strategy for partitioning knee images into the compact regions that follow natural texture boundaries. LBP, Fractal Dimension (FD), Haralick features, Shannon entropy, and HOG methods were computed within the standard ROI and within the proposed adaptive ROIs. Subsequently, we built logistic regression models to identify and compare the performances of each texture descriptor and each ROI placement method using 5-fold cross validation setting. Importantly, we also investigated the generalizability of our approach by training the models on OAI and testing them on MOST dataset.We used area under the receiver operating characteristic (ROC) curve (AUC) and average precision (AP) obtained from the precision-recall (PR) curve to compare the results. We found that the adaptive ROI improves the classification performance (OA vs. non-OA) over the commonly used standard ROI (up to 9% percent increase in AUC). We also observed that, from all texture parameters, LBP yielded the best performance in all settings with the best AUC of 0.840 [0.825, 0.852] and associated AP of 0.804 [0.786, 0.820]. Compared to the current state-of-the-art approaches, our results suggest that the proposed adaptive ROI approach in texture analysis of subchondral bone can increase the diagnostic performance for detecting the presence of radiographic OA.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07736](http://arxiv.org/abs/1908.07736)

##### PDF
[http://arxiv.org/pdf/1908.07736](http://arxiv.org/pdf/1908.07736)

