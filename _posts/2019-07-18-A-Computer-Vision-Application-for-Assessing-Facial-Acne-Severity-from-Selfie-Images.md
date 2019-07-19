---
layout: post
title: "A Computer Vision Application for Assessing Facial Acne Severity from Selfie Images"
date: 2019-07-18 06:51:33
categories: arXiv_CV
tags: arXiv_CV Knowledge Transfer_Learning Deep_Learning
author: Tingting Zhao, Hang Zhang, Jacob Spoelstra
mathjax: true
---

* content
{:toc}

##### Abstract
We worked with Nestle Skin Health SHIELD (Skin Health, Innovation, Education, and Longevity Development, NSH) to develop a deep learning model that is able to assess acne severity from selfie images as accurate as dermatologists. The model was deployed as a mobile application, providing patients an easy way to assess and track the progress of their acne treatment. NSH acquired 4,700 selfie images for this study and recruited 11 internal dermatologists to label them in five categories: 1-Clear, 2- Almost Clear, 3-Mild, 4-Moderate, 5-Severe. We developed a coupling approach of facial landmarks and OneEye OpenCV models to extract skin patches from the selfie images in order to minimize irrelevant background. To address the problem of spatial sensitivity of CNN models, we designed an innovative image rolling approach so that acne lesions appeared in more locations in the training images. This data augmentation approach addressed the label imbalance issue and improved the generalization of the CNN model on test images. We applied a transfer learning approach by extracting image features using a ResNet 152 pre-trained model, then added and trained a fully connected layer to approximate the desired severity rating. Our model outperformed a (junior) human dermatologist on test images. To our knowledge, this is the first deep learning-based solution for acne assessment using selfie images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.07901](http://arxiv.org/abs/1907.07901)

##### PDF
[http://arxiv.org/pdf/1907.07901](http://arxiv.org/pdf/1907.07901)

