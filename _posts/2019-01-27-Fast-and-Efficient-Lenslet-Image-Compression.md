---
layout: post
title: "Fast and Efficient Lenslet Image Compression"
date: 2019-01-27 12:14:58
categories: arXiv_CV
tags: arXiv_CV Image_Caption GAN Prediction
author: Hadi Amirpour, Antonio Pinheiro, Manuela Pereira, Mohammad Ghanbari
mathjax: true
---

* content
{:toc}

##### Abstract
Light field imaging is characterized by capturing brightness, color, and directional information of light rays in a scene. This leads to image representations with huge amount of data that require efficient coding schemes. In this paper, lenslet images are rendered into sub-aperture images. These images are organized as a pseudo-sequence input for the HEVC video codec. To better exploit redundancy among the neighboring sub-aperture images and consequently decrease the distances between a sub-aperture image and its references used for prediction, sub-aperture images are divided into four smaller groups that are scanned in a serpentine order. The most central sub-aperture image, which has the highest similarity to all the other images, is used as the initial reference image for each of the four regions. Furthermore, a structure is defined that selects spatially adjacent sub-aperture images as prediction references with the highest similarity to the current image. In this way, encoding efficiency increases, and furthermore it leads to a higher similarity among the co-located Coding Three Units (CTUs). The similarities among the co-located CTUs are exploited to predict Coding Unit depths.Moreover, independent encoding of each group division enables parallel processing, that along with the proposed coding unit depth prediction decrease the encoding execution time by almost 80% on average. Simulation results show that Rate-Distortion performance of the proposed method has higher compression gain than the other state-of-the-art lenslet compression methods with lower computational complexity.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11396](http://arxiv.org/abs/1901.11396)

##### PDF
[http://arxiv.org/pdf/1901.11396](http://arxiv.org/pdf/1901.11396)

