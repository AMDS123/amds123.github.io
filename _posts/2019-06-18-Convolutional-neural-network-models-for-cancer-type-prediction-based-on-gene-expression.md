---
layout: post
title: "Convolutional neural network models for cancer type prediction based on gene expression"
date: 2019-06-18 20:27:35
categories: arXiv_AI
tags: arXiv_AI Salient Embedding CNN Prediction
author: Milad Mostavi, Yu-Chiao Chiu, Yufei Huang, Yidong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Background Precise prediction of cancer types is vital for cancer diagnosis and therapy. Important cancer marker genes can be inferred through predictive model. Several studies have attempted to build machine learning models for this task however none has taken into consideration the effects of tissue of origin that can potentially bias the identification of cancer markers. Results In this paper, we introduced several Convolutional Neural Network (CNN) models that take unstructured gene expression inputs to classify tumor and non-tumor samples into their designated cancer types or as normal. Based on different designs of gene embeddings and convolution schemes, we implemented three CNN models: 1D-CNN, 2D-Vanilla-CNN, and 2D-Hybrid-CNN. The models were trained and tested on combined 10,340 samples of 33 cancer types and 731 matched normal tissues of The Cancer Genome Atlas (TCGA). Our models achieved excellent prediction accuracies (93.9-95.0%) among 34 classes (33 cancers and normal). Furthermore, we interpreted one of the models, known as 1D-CNN model, with a guided saliency technique and identified a total of 2,090 cancer markers (108 per class). The concordance of differential expression of these markers between the cancer type they represent and others is confirmed. In breast cancer, for instance, our model identified well-known markers, such as GATA3 and ESR1. Finally, we extended the 1D-CNN model for prediction of breast cancer subtypes and achieved an average accuracy of 88.42% among 5 subtypes. The codes can be found at https://github.com/chenlabgccri/CancerTypePrediction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07794](http://arxiv.org/abs/1906.07794)

##### PDF
[http://arxiv.org/pdf/1906.07794](http://arxiv.org/pdf/1906.07794)

