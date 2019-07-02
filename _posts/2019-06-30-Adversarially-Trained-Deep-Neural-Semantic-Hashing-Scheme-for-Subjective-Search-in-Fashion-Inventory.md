---
layout: post
title: "Adversarially Trained Deep Neural Semantic Hashing Scheme for Subjective Search in Fashion Inventory"
date: 2019-06-30 13:59:01
categories: arXiv_AI
tags: arXiv_AI Adversarial CNN
author: Saket Singh, Debdoot Sheet, Mithun Dasgupta
mathjax: true
---

* content
{:toc}

##### Abstract
The simple approach of retrieving a closest match of a query image from one in the gallery, compares an image pair using sum of absolute difference in pixel or feature space. The process is computationally expensive, ill-posed to illumination, background composition, pose variation, as well as inefficient to be deployed on gallery sets with more than 1000 elements. Hashing is a faster alternative which involves representing images in reduced dimensional simple feature spaces. Encoding images into binary hash codes enables similarity comparison in an image-pair using the Hamming distance measure. The challenge, however, lies in encoding the images using a semantic hashing scheme that lets subjective neighbors lie within the tolerable Hamming radius. This work presents a solution employing adversarial learning of a deep neural semantic hashing network for fashion inventory retrieval. It consists of a feature extracting convolutional neural network (CNN) learned to (i) minimize error in classifying type of clothing, (ii) minimize hamming distance between semantic neighbors and maximize distance between semantically dissimilar images, (iii) maximally scramble a discriminator's ability to identify the corresponding hash code-image pair when processing a semantically similar query-gallery image pair. Experimental validation for fashion inventory search yields a mean average precision (mAP) of 90.65% in finding the closest match as compared to 53.26% obtained by the prior art of deep Cauchy hashing for hamming space retrieval.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.00382](http://arxiv.org/abs/1907.00382)

##### PDF
[http://arxiv.org/pdf/1907.00382](http://arxiv.org/pdf/1907.00382)

