---
layout: post
title: "Learning to Reconstruct People in Clothing from a Single RGB Camera"
date: 2019-03-14 09:55:44
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Thiemo Alldieck, Marcus Magnor, Bharat Lal Bhatnagar, Christian Theobalt, Gerard Pons-Moll
mathjax: true
---

* content
{:toc}

##### Abstract
We present a learning-based model to infer the personalized 3D shape of people from a few frames (1-8) of a monocular video in which the person is moving, in less than 10 seconds with a reconstruction accuracy of 5mm. Our model learns to predict the parameters of a statistical body model and instance displacements that add clothing and hair to the shape. The model achieves fast and accurate predictions based on two key design choices. First, by predicting shape in a canonical T-pose space, the network learns to encode the images of the person into pose-invariant latent codes, where the information is fused. Second, based on the observation that feed-forward predictions are fast but do not always align with the input images, we predict using both, bottom-up and top-down streams (one per view) allowing information to flow in both directions. Learning relies only on synthetic 3D data. Once learned, the model can take a variable number of frames as input, and is able to reconstruct shapes even from a single image with an accuracy of 6mm. Results on 3 different datasets demonstrate the efficacy and accuracy of our approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.05885](http://arxiv.org/abs/1903.05885)

##### PDF
[http://arxiv.org/pdf/1903.05885](http://arxiv.org/pdf/1903.05885)

