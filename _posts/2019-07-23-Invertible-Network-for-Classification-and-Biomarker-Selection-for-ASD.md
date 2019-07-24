---
layout: post
title: "Invertible Network for Classification and Biomarker Selection for ASD"
date: 2019-07-23 07:31:39
categories: arXiv_CV
tags: arXiv_CV Classification Deep_Learning Prediction
author: Juntang Zhuang, Nicha C. Dvornek, Xiaoxiao Li, Pamela Ventola, James S. Duncan
mathjax: true
---

* content
{:toc}

##### Abstract
Determining biomarkers for autism spectrum disorder (ASD) is crucial to understanding its mechanisms. Recently deep learning methods have achieved success in the classification task of ASD using fMRI data. However, due to the black-box nature of most deep learning models, it's hard to perform biomarker selection and interpret model decisions. The recently proposed invertible networks can accurately reconstruct the input from its output, and have the potential to unravel the black-box representation. Therefore, we propose a novel method to classify ASD and identify biomarkers for ASD using the connectivity matrix calculated from fMRI as the input. Specifically, with invertible networks, we explicitly determine the decision boundary and the projection of data points onto the boundary. Like linear classifiers, the difference between a point and its projection onto the decision boundary can be viewed as the explanation. We then define the importance as the explanation weighted by the gradient of prediction $w.r.t$ the input, and identify biomarkers based on this importance measure. We perform a regression task to further validate our biomarker selection: compared to using all edges in the connectivity matrix, using the top 10\% important edges we generate a lower regression error on 6 different severity scores. Our experiments show that the invertible network is both effective at ASD classification and interpretable, allowing for discovery of reliable biomarkers.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.09729](http://arxiv.org/abs/1907.09729)

##### PDF
[http://arxiv.org/pdf/1907.09729](http://arxiv.org/pdf/1907.09729)

