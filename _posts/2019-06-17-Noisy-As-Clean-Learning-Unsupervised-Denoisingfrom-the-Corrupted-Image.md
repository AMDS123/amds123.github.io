---
layout: post
title: "Noisy-As-Clean: Learning Unsupervised Denoisingfrom the Corrupted Image"
date: 2019-06-17 07:39:00
categories: arXiv_CV
tags: arXiv_CV
author: Jun Xu, Yuan Huang, Li Liu, Fan Zhu, Xingsong Hou, Ling Shao
mathjax: true
---

* content
{:toc}

##### Abstract
In the past few years, supervised networks have achieved promising performance on image denoising. These methods learn image priors and synthetic noise statistics from plenty pairs of noisy and clean images. Recently, several unsupervised denoising networks are proposed only using external noisy images for training. However, the networks learned from external data inherently suffer from the domain gap dilemma, i.e., the image priors and noise statistics are very different between the training data and the corrupted test images. This dilemma becomes more clear when dealing with the signal dependent realistic noise in real photographs. In this work, we provide a statistically useful conclusion: it is possible to learn an unsupervised network only with the corrupted image, approximating the optimal parameters of a supervised network learned with pairs of noisy and clean images. This is achieved by proposing a "Noisy-As-Clean" strategy: taking the corrupted image as "clean" target and the simulated noisy images (based on the corrupted image) as inputs. Extensive experiments show that the unsupervised denoising networks learned with our "Noisy-As-Clean" strategy surprisingly outperforms previous supervised networks on removing several typical synthetic noise and realistic noise. The code will be publicly released.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06878](http://arxiv.org/abs/1906.06878)

##### PDF
[http://arxiv.org/pdf/1906.06878](http://arxiv.org/pdf/1906.06878)

