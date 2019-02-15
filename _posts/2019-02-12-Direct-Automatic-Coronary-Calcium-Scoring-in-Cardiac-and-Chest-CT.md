---
layout: post
title: "Direct Automatic Coronary Calcium Scoring in Cardiac and Chest CT"
date: 2019-02-12 21:50:21
categories: arXiv_CV
tags: arXiv_CV Segmentation Relation
author: Bob D. de Vos, Jelmer M. Wolterink, Tim Leiner, Pim A. de Jong, Nikolas Lessmann, Ivana Isgum
mathjax: true
---

* content
{:toc}

##### Abstract
Cardiovascular disease (CVD) is the global leading cause of death. A strong risk factor for CVD events is the amount of coronary artery calcium (CAC). To meet demands of the increasing interest in quantification of CAC, i.e. coronary calcium scoring, especially as an unrequested finding for screening and research, automatic methods have been proposed. Current automatic calcium scoring methods are relatively computationally expensive and only provide scores for one type of CT. To address this, we propose a computationally efficient method that employs two ConvNets: the first performs registration to align the fields of view of input CTs and the second performs direct regression of the calcium score, thereby circumventing time-consuming intermediate CAC segmentation. Optional decision feedback provides insight in the regions that contributed to the calcium score. Experiments were performed using 903 cardiac CT and 1,687 chest CT scans. The method predicted calcium scores in less than 0.3 s. Intra-class correlation coefficient between predicted and manual calcium scores was 0.98 for both cardiac and chest CT. The method showed almost perfect agreement between automatic and manual CVD risk categorization in both datasets, with a linearly weighted Cohen's kappa of 0.95 in cardiac CT and 0.93 in chest CT. Performance is similar to that of state-of-the-art methods, but the proposed method is hundreds of times faster. By providing visual feedback, insight is given in the decision process, making it readily implementable in clinical and research settings.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.05408](http://arxiv.org/abs/1902.05408)

##### PDF
[http://arxiv.org/pdf/1902.05408](http://arxiv.org/pdf/1902.05408)

