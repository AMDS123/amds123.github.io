---
layout: post
title: "Evaluation of head segmentation quality for treatment planning of tumor treating fields in brain tumors"
date: 2019-06-26 12:17:00
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Reuben R Shamir, Zeev Bomzon
mathjax: true
---

* content
{:toc}

##### Abstract
Tumor treating fields (TTFields) is an FDA approved therapy for the treatment of Gliobastoma Multiform (GBM) and currently being investigated for additional tumor types. TTFields are delivered to the tumor through the placement of transducer arrays (TAs) placed on the patient scalp. The positions of the TAs are associated with treatment outcomes via simulations of the electric fields. Therefore, we are currently developing a method for recommending optimal placement of TAs. A key step to achieve this goal is to correctly segment the head into tissues of similar electrical properties. Visual inspection of segmentation quality is invaluable but time-consuming. Automatic quality assessment can assist in automatic refinement of the segmentation parameters, suggest flaw points to the user and indicate if the segmented method is of sufficient accuracy for TTFields simulation. As a first step in this direction, we identified a set of features that are relevant to atlas-based segmentation and show that these are significantly correlated (p &lt; 0.05) with a similarity measure between validated and automatically computed segmentations. Furthermore, we incorporated these features in a decision tree regressor to predict the similarity of the validated and computed segmentations of 20 TTFields patients using a leave-one-out approach. The predicted similarity measures were highly correlated with the actual ones (average abs. difference 3% (SD = 3%); r = 0.92, p &lt; 0.001). We conclude that quality estimation of segmentations is feasible by incorporating machine learning and segmentation-relevant features.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.11014](http://arxiv.org/abs/1906.11014)

##### PDF
[http://arxiv.org/pdf/1906.11014](http://arxiv.org/pdf/1906.11014)

