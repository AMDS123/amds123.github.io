---
layout: post
title: "Learning From Noisy Labels By Regularized Estimation Of Annotator Confusion"
date: 2019-02-10 23:01:33
categories: arXiv_CV
tags: arXiv_CV Regularization Image_Classification Classification Prediction
author: Ryutaro Tanno, Ardavan Saeedi, Swami Sankaranarayanan, Daniel C. Alexander, Nathan Silberman
mathjax: true
---

* content
{:toc}

##### Abstract
The predictive performance of supervised learning algorithms depends on the quality of labels. In a typical label collection process, multiple annotators provide subjective noisy estimates of the "truth" under the influence of their varying skill-levels and biases. Blindly treating these noisy labels as the ground truth limits the accuracy of learning algorithms in the presence of strong disagreement. This problem is critical for applications in domains such as medical imaging where both the annotation cost and inter-observer variability are high. In this work, we present a method for simultaneously learning the individual annotator model and the underlying true label distribution, using only noisy observations. Each annotator is modeled by a confusion matrix that is jointly estimated along with the classifier predictions. We propose to add a regularization term to the loss function that encourages convergence to the true annotator confusion matrix. We provide a theoretical argument as to how the regularization is essential to our approach both for the case of single annotator and multiple annotators. Despite the simplicity of the idea, experiments on image classification tasks with both simulated and real labels show that our method either outperforms or performs on par with the state-of-the-art methods and is capable of estimating the skills of annotators even with a single label available per image.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03680](http://arxiv.org/abs/1902.03680)

##### PDF
[http://arxiv.org/pdf/1902.03680](http://arxiv.org/pdf/1902.03680)

