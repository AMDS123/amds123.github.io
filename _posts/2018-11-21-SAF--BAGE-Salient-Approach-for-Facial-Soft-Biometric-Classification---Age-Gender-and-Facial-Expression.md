---
layout: post
title: "SAF- BAGE: Salient Approach for Facial Soft-Biometric Classification - Age, Gender, and Facial Expression"
date: 2018-11-21 07:50:13
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Face CNN Classification Prediction Detection
author: Ayesha Gurnani, Kenil Shah, Vandit Gajjar, Viraj Mavani, Yash Khandhediya
mathjax: true
---

* content
{:toc}

##### Abstract
How can we improve the facial soft-biometric classification with help of the human visual system? This paper explores the use of saliency which is equivalent to the human visual system to classify Age, Gender and Facial Expression soft-biometric for facial images. Using the Deep Multi-level Network (ML-Net) [1] and off-the-shelf face detector [2], we propose our approach - SAF-BAGE, which first detects the face in the test image, increases the Bounding Box (B-Box) margin by 30%, finds the saliency map using ML-Net, with 30% reweighted ratio of saliency map, it multiplies with the input cropped face and extracts the Convolutional Neural Networks (CNN) predictions on the multiplied reweighted salient face. Our CNN uses the model AlexNet [3], which is pre-trained on ImageNet. The proposed approach surpasses the performance of other approaches, increasing the state-of-the-art by approximately 0.8% on the widely-used Adience [28] dataset for Age and Gender classification and by nearly 3% on the recent AffectNet [36] dataset for Facial Expression classification. We hope our simple, reproducible and effective approach will help ease future research in facial soft-biometric classification using saliency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.05719](http://arxiv.org/abs/1803.05719)

##### PDF
[http://arxiv.org/pdf/1803.05719](http://arxiv.org/pdf/1803.05719)

