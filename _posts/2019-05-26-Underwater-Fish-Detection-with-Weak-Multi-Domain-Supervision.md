---
layout: post
title: "Underwater Fish Detection with Weak Multi-Domain Supervision"
date: 2019-05-26 01:43:58
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection
author: Dmitry A. Konovalov, Alzayat Saleh, Michael Bradley, Mangalam Sankupellay, Simone Marini, Marcus Sheaves
mathjax: true
---

* content
{:toc}

##### Abstract
Given a sufficiently large training dataset, it is relatively easy to train a modern convolution neural network (CNN) as a required image classifier. However, for the task of fish classification and/or fish detection, if a CNN was trained to detect or classify particular fish species in particular background habitats, the same CNN exhibits much lower accuracy when applied to new/unseen fish species and/or fish habitats. Therefore, in practice, the CNN needs to be continuously fine-tuned to improve its classification accuracy to handle new project-specific fish species or habitats. In this work we present a labelling-efficient method of training a CNN-based fish-detector (the Xception CNN was used as the base) on relatively small numbers (4,000) of project-domain underwater fish/no-fish images from 20 different habitats. Additionally, 17,000 of known negative (that is, missing fish) general-domain (VOC2012) above-water images were used. Two publicly available fish-domain datasets supplied additional 27,000 of above-water and underwater positive/fish images. By using this multi-domain collection of images, the trained Xception-based binary (fish/not-fish) classifier achieved 0.17% false-positives and 0.61% false-negatives on the project's 20,000 negative and 16,000 positive holdout test images, respectively. The area under the ROC curve (AUC) was 99.94%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10708](http://arxiv.org/abs/1905.10708)

##### PDF
[http://arxiv.org/pdf/1905.10708](http://arxiv.org/pdf/1905.10708)

