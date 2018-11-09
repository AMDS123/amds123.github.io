---
layout: post
title: "ColorUNet: A convolutional classification approach to colorization"
date: 2018-11-07 19:20:59
categories: arXiv_CV
tags: arXiv_CV CNN Classification Prediction
author: Vincent Billaut, Matthieu de Rochemonteix, Marc Thibault
mathjax: true
---

* content
{:toc}

##### Abstract
This paper tackles the challenge of colorizing grayscale images. We take a deep convolutional neural network approach, and choose to take the angle of classification, working on a finite set of possible colors. Similarly to a recent paper, we implement a loss and a prediction function that favor realistic, colorful images rather than "true" ones. 
 We show that a rather lightweight architecture inspired by the U-Net, and trained on a reasonable amount of pictures of landscapes, achieves satisfactory results on this specific subset of pictures. We show that data augmentation significantly improves the performance and robustness of the model, and provide visual analysis of the prediction confidence. 
 We show an application of our model, extending the task to video colorization. We suggest a way to smooth color predictions across frames, without the need to train a recurrent network designed for sequential inputs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.03120](http://arxiv.org/abs/1811.03120)

##### PDF
[http://arxiv.org/pdf/1811.03120](http://arxiv.org/pdf/1811.03120)

