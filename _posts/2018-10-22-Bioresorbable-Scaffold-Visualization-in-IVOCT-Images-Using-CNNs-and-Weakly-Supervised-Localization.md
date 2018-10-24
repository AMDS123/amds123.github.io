---
layout: post
title: "Bioresorbable Scaffold Visualization in IVOCT Images Using CNNs and Weakly Supervised Localization"
date: 2018-10-22 22:06:09
categories: arXiv_CV
tags: arXiv_CV Salient Review Weakly_Supervised CNN Classification Deep_Learning Detection
author: Nils Gessert, Sarah Latus, Youssef S. Abdelwahed, David M. Leistner, Matthias Lutz, Alexander Schlaefer
mathjax: true
---

* content
{:toc}

##### Abstract
Bioresorbable scaffolds have become a popular choice for treatment of coronary heart disease, replacing traditional metal stents. Often, intravascular optical coherence tomography is used to assess potential malapposition after implantation and for follow-up examinations later on. Typically, the scaffold is manually reviewed by an expert, analyzing each of the hundreds of image slices. As this is time consuming, automatic stent detection and visualization approaches have been proposed, mostly for metal stent detection based on classic image processing. As bioresorbable scaffolds are harder to detect, recent approaches have used feature extraction and machine learning methods for automatic detection. However, these methods require detailed, pixel-level labels in each image slice and extensive feature engineering for the particular stent type which might limit the approaches' generalization capabilities. Therefore, we propose a deep learning-based method for bioresorbable scaffold visualization using only image-level labels. A convolutional neural network is trained to predict whether an image slice contains a metal stent, a bioresorbable scaffold, or no device. Then, we derive local stent strut information by employing weakly supervised localization using saliency maps with guided backpropagation. As saliency maps are generally diffuse and noisy, we propose a novel patch-based method with image shifting which allows for high resolution stent visualization. Our convolutional neural network model achieves a classification accuracy of 99.0 % for image-level stent classification which can be used for both high quality in-slice stent visualization and 3D rendering of the stent structure.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.09578](http://arxiv.org/abs/1810.09578)

##### PDF
[http://arxiv.org/pdf/1810.09578](http://arxiv.org/pdf/1810.09578)

