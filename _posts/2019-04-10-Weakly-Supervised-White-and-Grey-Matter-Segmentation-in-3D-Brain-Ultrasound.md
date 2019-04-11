---
layout: post
title: "Weakly-Supervised White and Grey Matter Segmentation in 3D Brain Ultrasound"
date: 2019-04-10 13:55:10
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Transfer_Learning
author: Beatrice Demiray, Julia Rackerseder, Stevica Bozhinoski, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
Although the segmentation of brain structures in ultrasound helps initialize image based registration, assist brain shift compensation, and provides interventional decision support, the task of segmenting grey and white matter in cranial ultrasound is very challenging and has not been addressed yet. We train a multi-scale fully convolutional neural network simultaneously for two classes in order to segment real clinical 3D ultrasound data. Parallel pathways working at different levels of resolution account for high frequency speckle noise and global 3D image features. To ensure reproducibility, the publicly available RESECT dataset is utilized for training and cross-validation. Due to the absence of a ground truth, we train with weakly annotated label. We implement label transfer from MRI to US, which is prone to a residual but inevitable registration error. To further improve results, we perform transfer learning using synthetic US data. The resulting method leads to excellent Dice scores of 0.7080, 0.8402 and 0.9315 for grey matter, white matter and background. Our proposed methodology sets an unparalleled standard for white and grey matter segmentation in 3D intracranial ultrasound.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05191](http://arxiv.org/abs/1904.05191)

##### PDF
[http://arxiv.org/pdf/1904.05191](http://arxiv.org/pdf/1904.05191)

