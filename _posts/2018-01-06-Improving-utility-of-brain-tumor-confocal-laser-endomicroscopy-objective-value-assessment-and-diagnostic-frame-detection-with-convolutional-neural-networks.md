---
layout: post
title: "Improving utility of brain tumor confocal laser endomicroscopy: objective value assessment and diagnostic frame detection with convolutional neural networks"
date: 2018-01-06 22:57:06
categories: arXiv_CV
tags: arXiv_CV CNN Detection
author: Mohammadhassan Izadyyazdanabadi, Evgenii Belykh, Nikolay Martirosyan, Jennifer Eschbacher, Peter Nakaji, Yezhou Yang, Mark C. Preul
mathjax: true
---

* content
{:toc}

##### Abstract
Confocal laser endomicroscopy (CLE), although capable of obtaining images at cellular resolution during surgery of brain tumors in real time, creates as many non-diagnostic as diagnostic images. Non-useful images are often distorted due to relative motion between probe and brain or blood artifacts. Many images, however, simply lack diagnostic features immediately informative to the physician. Examining all the hundreds or thousands of images from a single case to discriminate diagnostic images from nondiagnostic ones can be tedious. Providing a real-time diagnostic value assessment of images (fast enough to be used during the surgical acquisition process and accurate enough for the pathologist to rely on) to automatically detect diagnostic frames would streamline the analysis of images and filter useful images for the pathologist/surgeon. We sought to automatically classify images as diagnostic or non-diagnostic. AlexNet, a deep-learning architecture, was used in a 4-fold cross validation manner. Our dataset includes 16,795 images (8572 nondiagnostic and 8223 diagnostic) from 74 CLE-aided brain tumor surgery patients. The ground truth for all the images is provided by the pathologist. Average model accuracy on test data was 91% overall (90.79 % accuracy, 90.94 % sensitivity and 90.87 % specificity). To evaluate the model reliability we also performed receiver operating characteristic (ROC) analysis yielding 0.958 average for the area under ROC curve (AUC). These results demonstrate that a deeply trained AlexNet network can achieve a model that reliably and quickly recognizes diagnostic CLE images.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1801.02101](https://arxiv.org/abs/1801.02101)

##### PDF
[https://arxiv.org/pdf/1801.02101](https://arxiv.org/pdf/1801.02101)

