---
layout: post
title: "Multi Scale Curriculum CNN for Context-Aware Breast MRI Malignancy Classification"
date: 2019-06-14 07:33:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Classification Detection
author: Christoph Haarburger, Michael Baumgartner, Daniel Truhn, Mirjam Broeckmann, Hannah Schneider, Simone Schwabing, Christiane Kuhl, Dorit Merhof
mathjax: true
---

* content
{:toc}

##### Abstract
Classification of malignancy for breast cancer and other cancer types is usually tackled as an object detection problem: Individual lesions are first localized and then classified with respect to malignancy. However, the drawback of this approach is that abstract features incorporating several lesions and areas that are not labelled as a lesion but contain global medically relevant information are thus disregarded: especially for dynamic contrast-enhanced breast MRI, criteria such as background parenchymal enhancement and location within the breast are important for diagnosis and cannot be captured by object detection approaches properly. In this work, we propose a 3D CNN and a multi scale curriculum learning strategy to classify malignancy globally based on an MRI of the whole breast. Thus, the global context of the whole breast rather than individual lesions is taken into account. Our proposed approach does not rely on lesion segmentations, which renders the annotation of training data much more effective than in current object detection approaches. Achieving an AUROC of 0.89, we compare the performance of our approach to Mask R-CNN and Retina U-Net as well as a radiologist. Our performance is on par with approaches that, in contrast to our method, rely on pixelwise segmentations of lesions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06058](https://arxiv.org/abs/1906.06058)

##### PDF
[https://arxiv.org/pdf/1906.06058](https://arxiv.org/pdf/1906.06058)

