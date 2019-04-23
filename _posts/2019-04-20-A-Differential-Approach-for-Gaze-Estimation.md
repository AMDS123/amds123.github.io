---
layout: post
title: "A Differential Approach for Gaze Estimation"
date: 2019-04-20 15:17:45
categories: arXiv_CV
tags: arXiv_CV Face CNN Prediction
author: Gang Liu, Yu Yu, Kenneth A. Funes Mora, Jean-Marc Odobez
mathjax: true
---

* content
{:toc}

##### Abstract
Non-invasive gaze estimation methods usually regress gaze directions directly from a single face or eye image. However, due to important variabilities in eye shapes and inner eye structures amongst individuals, universal models obtain limited accuracies and their output usually exhibit high variance as well as biases which are subject dependent. Therefore, increasing accuracy is usually done through calibration, allowing gaze predictions for a subject to be mapped to his/her actual gaze. In this paper, we introduce a novel image differential method for gaze estimation. We propose to directly train a differential convolutional neural network to predict the gaze differences between two eye input images of the same subject. Then, given a set of subject specific calibration images, we can use the inferred differences to predict the gaze direction of a novel eye sample. The assumption is that by allowing the comparison between two eye images, annoyance factors (alignment, eyelid closing, illumination perturbations) which usually plague single image prediction methods can be much reduced, allowing better prediction altogether. Experiments on 3 public datasets validate our approach which constantly outperforms state-of-the-art methods even when using only one calibration sample or when the latter methods are followed by subject specific gaze adaptation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09459](http://arxiv.org/abs/1904.09459)

##### PDF
[http://arxiv.org/pdf/1904.09459](http://arxiv.org/pdf/1904.09459)

