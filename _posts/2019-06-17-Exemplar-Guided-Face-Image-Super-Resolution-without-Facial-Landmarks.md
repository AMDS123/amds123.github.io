---
layout: post
title: "Exemplar Guided Face Image Super-Resolution without Facial Landmarks"
date: 2019-06-17 15:08:09
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution Face Embedding CNN Quantitative
author: Berk Dogan, Shuhang Gu, Radu Timofte
mathjax: true
---

* content
{:toc}

##### Abstract
Nowadays, due to the ubiquitous visual media there are vast amounts of already available high-resolution (HR) face images. Therefore, for super-resolving a given very low-resolution (LR) face image of a person it is very likely to find another HR face image of the same person which can be used to guide the process. In this paper, we propose a convolutional neural network (CNN)-based solution, namely GWAInet, which applies super-resolution (SR) by a factor 8x on face images guided by another unconstrained HR face image of the same person with possible differences in age, expression, pose or size. GWAInet is trained in an adversarial generative manner to produce the desired high quality perceptual image results. The utilization of the HR guiding image is realized via the use of a warper subnetwork that aligns its contents to the input image and the use of a feature fusion chain for the extracted features from the warped guiding image and the input image. In training, the identity loss further helps in preserving the identity related features by minimizing the distance between the embedding vectors of SR and HR ground truth images. Contrary to the current state-of-the-art in face super-resolution, our method does not require facial landmark points for its training, which helps its robustness and allows it to produce fine details also for the surrounding face region in a uniform manner. Our method GWAInet produces photo-realistic images in upscaling factor 8x and outperforms state-of-the-art in quantitative terms and perceptual quality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07078](http://arxiv.org/abs/1906.07078)

##### PDF
[http://arxiv.org/pdf/1906.07078](http://arxiv.org/pdf/1906.07078)

