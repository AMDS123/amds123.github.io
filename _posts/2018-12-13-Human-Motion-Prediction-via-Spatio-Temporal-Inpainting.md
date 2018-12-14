---
layout: post
title: "Human Motion Prediction via Spatio-Temporal Inpainting"
date: 2018-12-13 15:27:15
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Prediction
author: Alejandro Hernandez Ruiz, Juergen Gall, Francesc Moreno-Noguer
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a Generative Adversarial Network (GAN) to forecast 3D human motion given a sequence of observed 3D skeleton poses. While recent GANs have shown promising results, they can only forecast plausible human-like motion over relatively short periods of time, i.e. a few hundred milliseconds, and typically ignore the absolute position of the skeleton w.r.t. the camera. The GAN scheme we propose can reliably provide long term predictions of two seconds or more for both the non-rigid body pose and its absolute position, and can be trained in an self-supervised manner. Our approach builds upon three main contributions. First, we consider a data representation based on a spatio-temporal tensor of 3D skeleton coordinates which allows us to formulate the prediction problem as an inpainting one, for which GANs work particularly well. Secondly, we design a GAN architecture to learn the joint distribution of body poses and global motion, allowing us to hypothesize large chunks of the input 3D tensor with missing data. And finally, we argue that the L2 metric, which is considered so far by most approaches, fails to capture the actual distribution of long-term human motion. We therefore propose an alternative metric that is more correlated with human perception. Our experiments demonstrate that our approach achieves significant improvements over the state of the art for human motion forecasting and that it also handles situations in which past observations are corrupted by severe occlusions, noise and consecutive missing frames.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.05478](http://arxiv.org/abs/1812.05478)

##### PDF
[http://arxiv.org/pdf/1812.05478](http://arxiv.org/pdf/1812.05478)

