---
layout: post
title: "Lung Cancer Detection using Co-learning from Chest CT Images and Clinical Demographics"
date: 2019-02-21 20:01:35
categories: arXiv_CV
tags: arXiv_CV Attention CNN Classification Detection
author: Jiachen Wang, Riqiang Gao, Yuankai Huo, Shunxing Bao, Yunxi Xiong, Sanja L. Antic, Travis J. Osterman, Pierre P. Massion, Bennett A. Landman
mathjax: true
---

* content
{:toc}

##### Abstract
Early detection of lung cancer is essential in reducing mortality. Recent studies have demonstrated the clinical utility of low-dose computed tomography (CT) to detect lung cancer among individuals selected based on very limited clinical information. However, this strategy yields high false positive rates, which can lead to unnecessary and potentially harmful procedures. To address such challenges, we established a pipeline that co-learns from detailed clinical demographics and 3D CT images. Toward this end, we leveraged data from the Consortium for Molecular and Cellular Characterization of Screen-Detected Lesions (MCL), which focuses on early detection of lung cancer. A 3D attention-based deep convolutional neural net (DCNN) is proposed to identify lung cancer from the chest CT scan without prior anatomical location of the suspicious nodule. To improve upon the non-invasive discrimination between benign and malignant, we applied a random forest classifier to a dataset integrating clinical information to imaging data. The results show that the AUC obtained from clinical demographics alone was 0.635 while the attention network alone reached an accuracy of 0.687. In contrast when applying our proposed pipeline integrating clinical and imaging variables, we reached an AUC of 0.787 on the testing dataset. The proposed network both efficiently captures anatomical information for classification and also generates attention maps that explain the features that drive performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.08236](http://arxiv.org/abs/1902.08236)

##### PDF
[http://arxiv.org/pdf/1902.08236](http://arxiv.org/pdf/1902.08236)

