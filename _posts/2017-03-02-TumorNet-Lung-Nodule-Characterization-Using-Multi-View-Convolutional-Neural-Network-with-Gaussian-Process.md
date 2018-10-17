---
layout: post
title: "TumorNet: Lung Nodule Characterization Using Multi-View Convolutional Neural Network with Gaussian Process"
date: 2017-03-02 07:26:37
categories: arXiv_AI
tags: arXiv_AI CNN
author: Sarfaraz Hussein, Robert Gillies, Kunlin Cao, Qi Song, Ulas Bagci
mathjax: true
---

* content
{:toc}

##### Abstract
Characterization of lung nodules as benign or malignant is one of the most important tasks in lung cancer diagnosis, staging and treatment planning. While the variation in the appearance of the nodules remains large, there is a need for a fast and robust computer aided system. In this work, we propose an end-to-end trainable multi-view deep Convolutional Neural Network (CNN) for nodule characterization. First, we use median intensity projection to obtain a 2D patch corresponding to each dimension. The three images are then concatenated to form a tensor, where the images serve as different channels of the input image. In order to increase the number of training samples, we perform data augmentation by scaling, rotating and adding noise to the input image. The trained network is used to extract features from the input image followed by a Gaussian Process (GP) regression to obtain the malignancy score. We also empirically establish the significance of different high level nodule attributes such as calcification, sphericity and others for malignancy determination. These attributes are found to be complementary to the deep multi-view CNN features and a significant improvement over other methods is obtained.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1703.00645](https://arxiv.org/abs/1703.00645)

##### PDF
[https://arxiv.org/pdf/1703.00645](https://arxiv.org/pdf/1703.00645)

