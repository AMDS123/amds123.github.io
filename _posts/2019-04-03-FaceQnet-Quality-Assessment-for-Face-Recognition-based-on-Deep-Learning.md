---
layout: post
title: "FaceQnet: Quality Assessment for Face Recognition based on Deep Learning"
date: 2019-04-03 02:12:31
categories: arXiv_CV
tags: arXiv_CV Face CNN Deep_Learning Prediction Recognition Face_Recognition
author: Javier Hernandez-Ortega, Javier Galbally, Julian Fierrez, Rudolf Haraksim, Laurent Beslay
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we develop a Quality Assessment approach for face recognition based on deep learning. The method consists of a Convolutional Neural Network, FaceQnet, that is used to predict the suitability of a specific input image for face recognition purposes. The training of FaceQnet is done using the VGGFace2 database. We employ the BioLab-ICAO framework for labeling the VGGFace2 images with quality information related to their ICAO compliance level. The groundtruth quality labels are obtained using FaceNet to generate comparison scores. We employ the groundtruth data to fine-tune a ResNet-based CNN, making it capable of returning a numerical quality measure for each input image. Finally, we verify if the FaceQnet scores are suitable to predict the expected performance when employing a specific image for face recognition with a COTS face recognition system. Several conclusions can be drawn from this work, most notably: 1) we managed to employ an existing ICAO compliance framework and a pretrained CNN to automatically label data with quality information, 2) we trained FaceQnet for quality estimation by fine-tuning a pre-trained face recognition network (ResNet-50), and 3) we have shown that the predictions from FaceQnet are highly correlated with the face recognition accuracy of a state-of-the-art commercial system not used during development. FaceQnet is publicly available in GitHub.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.01740](https://arxiv.org/abs/1904.01740)

##### PDF
[https://arxiv.org/pdf/1904.01740](https://arxiv.org/pdf/1904.01740)

