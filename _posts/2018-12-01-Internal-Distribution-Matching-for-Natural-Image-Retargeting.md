---
layout: post
title: "Internal Distribution Matching for Natural Image Retargeting"
date: 2018-12-01 17:48:02
categories: arXiv_CV
tags: arXiv_CV GAN
author: Assaf Shocher, Shai Bagon, Phillip Isola, Michal Irani
mathjax: true
---

* content
{:toc}

##### Abstract
Good Visual Retargeting changes the global size and aspect ratio of a natural image, while preserving the size and aspect ratio of all its local elements. We propose formulating this principle by requiring that the distribution of patches in the input matches the distribution of patches in the output. We introduce a Deep-Learning approach for retargeting, based on an "Internal GAN" (InGAN). InGAN is an image-specific GAN. It incorporates the Internal statistics of a single natural image in a GAN. It is trained on a single input image and learns the distribution of its patches. It is then able to synthesize natural looking target images composed from the input image patch-distribution. InGAN is totally unsupervised, and requires no additional data other than the input image itself. Moreover, once trained on the input image, it can generate target images of any specified size or aspect ratio in real-time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00231](http://arxiv.org/abs/1812.00231)

##### PDF
[http://arxiv.org/pdf/1812.00231](http://arxiv.org/pdf/1812.00231)

