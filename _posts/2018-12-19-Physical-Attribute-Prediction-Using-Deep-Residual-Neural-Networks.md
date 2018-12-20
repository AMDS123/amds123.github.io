---
layout: post
title: "Physical Attribute Prediction Using Deep Residual Neural Networks"
date: 2018-12-19 10:19:19
categories: arXiv_CV
tags: arXiv_CV Face CNN Deep_Learning Prediction Detection Face_Detection Recognition Face_Recognition
author: Rashidedin Jahandideh, Alireza Tavakoli Targhi, Maryam Tahmasbi
mathjax: true
---

* content
{:toc}

##### Abstract
Images taken from the Internet have been used alongside Deep Learning for many different tasks such as: smile detection, ethnicity, hair style, hair colour, gender and age prediction. After witnessing these usages, we were wondering what other attributes can be predicted from facial images available on the Internet. In this paper we tackle the prediction of physical attributes from face images using Convolutional Neural Networks trained on our dataset named FIRW. We crawled around 61, 000 images from the web, then use face detection to crop faces from these real world images. We choose ResNet-50 as our base network architecture. This network was pretrained for the task of face recognition by using the VGG-Face dataset, and we finetune it by using our own dataset to predict physical attributes. Separate networks are trained for the prediction of body type, ethnicity, gender, height and weight; our models achieve the following accuracies for theses tasks, respectively: 84.58%, 87.34%, 97.97%, 70.51%, 63.99%. To validate our choice of ResNet-50 as the base architecture, we also tackle the famous CelebA dataset. Our models achieve an averagy accuracy of 91.19% on CelebA, which is comparable to state-of-the-art approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.07857](http://arxiv.org/abs/1812.07857)

##### PDF
[http://arxiv.org/pdf/1812.07857](http://arxiv.org/pdf/1812.07857)

