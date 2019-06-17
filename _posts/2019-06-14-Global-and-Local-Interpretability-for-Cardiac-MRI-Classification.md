---
layout: post
title: "Global and Local Interpretability for Cardiac MRI Classification"
date: 2019-06-14 13:06:24
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification Deep_Learning
author: James R. Clough, Ilkay Oksuz, Esther Puyol-Anton, Bram Ruijsink, Andrew P. King, Julia A. Schnabel
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning methods for classifying medical images have demonstrated impressive accuracy in a wide range of tasks but often these models are hard to interpret, limiting their applicability in clinical practice. In this work we introduce a convolutional neural network model for identifying disease in temporal sequences of cardiac MR segmentations which is interpretable in terms of clinically familiar measurements. The model is based around a variational autoencoder, reducing the input into a low-dimensional latent space in which classification occurs. We then use the recently developed `concept activation vector' technique to associate concepts which are diagnostically meaningful (eg. clinical biomarkers such as `low left-ventricular ejection fraction') to certain vectors in the latent space. These concepts are then qualitatively inspected by observing the change in the image domain resulting from interpolations in the latent space in the direction of these vectors. As a result, when the model classifies images it is also capable of providing naturally interpretable concepts relevant to that classification and demonstrating the meaning of those concepts in the image domain. Our approach is demonstrated on the UK Biobank cardiac MRI dataset where we detect the presence of coronary artery disease.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06188](https://arxiv.org/abs/1906.06188)

##### PDF
[https://arxiv.org/pdf/1906.06188](https://arxiv.org/pdf/1906.06188)

