---
layout: post
title: "What does AI see? Deep segmentation networks discover biomarkers for lung cancer survival"
date: 2019-03-26 19:55:44
categories: arXiv_AI
tags: arXiv_AI Segmentation CNN Relation
author: Stephen Baek, Yusen He, Bryan G. Allen, John M. Buatti, Brian J. Smith, Kristin A. Plichta, Steven N. Seyedin, Maggie Gannon, Katherine R. Cabel, Yusung Kim, Xiaodong Wu
mathjax: true
---

* content
{:toc}

##### Abstract
Non-small-cell lung cancer (NSCLC) represents approximately 80-85% of lung cancer diagnoses and is the leading cause of cancer-related death worldwide. Recent studies indicate that image-based radiomics features from positron emission tomography-computed tomography (PET/CT) images have predictive power on NSCLC outcomes. To this end, easily calculated functional features such as the maximum and the mean of standard uptake value (SUV) and total lesion glycolysis (TLG) are most commonly used for NSCLC prognostication, but their prognostic value remains controversial. Meanwhile, convolutional neural networks (CNN) are rapidly emerging as a new premise for cancer image analysis, with significantly enhanced predictive power compared to other hand-crafted radiomics features. Here we show that CNN trained to perform the tumor segmentation task, with no other information than physician contours, identify a rich set of survival-related image features with remarkable prognostic value. In a retrospective study on 96 NSCLC patients before stereotactic-body radiotherapy (SBRT), we found that the CNN segmentation algorithm (U-Net) trained for tumor segmentation in PET/CT images, contained features having strong correlation with 2- and 5-year overall and disease-specific survivals. The U-net algorithm has not seen any other clinical information (e.g. survival, age, smoking history) than the images and the corresponding tumor contours provided by physicians. Furthermore, through visualization of the U-Net, we also found convincing evidence that the regions of progression appear to match with the regions where the U-Net features identified patterns that predicted higher likelihood of death. We anticipate our findings will be a starting point for more sophisticated non-intrusive patient specific cancer prognosis determination.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11593](http://arxiv.org/abs/1903.11593)

##### PDF
[http://arxiv.org/pdf/1903.11593](http://arxiv.org/pdf/1903.11593)

