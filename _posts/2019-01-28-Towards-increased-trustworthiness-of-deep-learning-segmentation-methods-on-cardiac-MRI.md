---
layout: post
title: "Towards increased trustworthiness of deep learning segmentation methods on cardiac MRI"
date: 2019-01-28 09:30:59
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning
author: J&#xf6;rg Sander, Bob D. de Vos, Jelmer M. Wolterink, Ivana I&#x161;gum
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art deep learning segmentation methods have not yet made a broad entrance into the clinical setting in spite of high demand for such automatic methods. One important reason is the lack of reliability caused by models that fail unnoticed and often locally produce anatomically implausible results that medical experts would not make. This paper presents an automatic image segmentation method based on (Bayesian) dilated convolutional networks (DCNN) that generate segmentation masks and spatial uncertainty maps for the input image at hand. The method was trained and evaluated using segmentation of the left ventricle (LV) cavity, right ventricle (RV) endocardium and myocardium (Myo) at end-diastole (ED) and end-systole (ES) in 100 cardiac 2D MR scans from the MICCAI 2017 Challenge (ACDC). Combining segmentations and uncertainty maps and employing a human-in-the-loop setting, we provide evidence that image areas indicated as highly uncertain regarding the obtained segmentation almost entirely cover regions of incorrect segmentations. The fused information can be harnessed to increase segmentation performance. Our results reveal that we can obtain valuable spatial uncertainty maps with low computational effort using DCNNs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.10430](http://arxiv.org/abs/1809.10430)

##### PDF
[http://arxiv.org/pdf/1809.10430](http://arxiv.org/pdf/1809.10430)

