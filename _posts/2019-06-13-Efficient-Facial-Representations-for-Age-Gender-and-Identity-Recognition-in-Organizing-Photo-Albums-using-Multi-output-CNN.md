---
layout: post
title: "Efficient Facial Representations for Age, Gender and Identity Recognition in Organizing Photo Albums using Multi-output CNN"
date: 2019-06-13 07:59:42
categories: arXiv_CV
tags: arXiv_CV GAN Face CNN Prediction Recognition Face_Recognition
author: Andrey V. Savchenko
mathjax: true
---

* content
{:toc}

##### Abstract
This paper is focused on the automatic extraction of persons and their attributes (gender, year of born) from album of photos and videos. We propose the two-stage approach, in which, firstly, the convolutional neural network simultaneously predicts age/gender from all photos and additionally extracts facial representations suitable for face identification. We modified the MobileNet, which is preliminarily trained to perform face recognition, in order to additionally recognize age and gender. In the second stage of our approach, extracted faces are grouped using hierarchical agglomerative clustering techniques. The born year and gender of a person in each cluster are estimated using aggregation of predictions for individual photos. We experimentally demonstrated that our facial clustering quality is competitive with the state-of-the-art neural networks, though our implementation is much computationally cheaper. Moreover, our approach is characterized by more accurate video-based age/gender recognition when compared to the publicly available models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.07718](http://arxiv.org/abs/1807.07718)

##### PDF
[http://arxiv.org/pdf/1807.07718](http://arxiv.org/pdf/1807.07718)

