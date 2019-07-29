---
layout: post
title: "Image Enhancement by Recurrently-trained Super-resolution Network"
date: 2019-07-26 00:30:36
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Image_Enhancement
author: Saem Park, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new learning strategy for image enhancement by recurrently training the same simple superresolution (SR) network multiple times. After initially training an SR network by using pairs of a corrupted low resolution (LR) image and an original image, the proposed method makes use of the trained SR network to generate new high resolution (HR) images with a doubled resolution from the original uncorrupted images. Then, the new HR images are downscaled to the original resolution, which work as target images for the SR network in the next stage. The newly generated HR images by the repeatedly trained SR network show better image quality and this strategy of training LR to mimic new HR can lead to a more efficient SR network. Up to a certain point, by repeating this process multiple times, better and better images are obtained. This recurrent leaning strategy for SR can be a good solution for downsizing convolution networks and making a more efficient SR network. To measure the enhanced image quality, for the first time in this area of super-resolution and image enhancement, we use VIQET MOS score which reflects human visual quality more accurately than the conventional MSE measure.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11341](http://arxiv.org/abs/1907.11341)

##### PDF
[http://arxiv.org/pdf/1907.11341](http://arxiv.org/pdf/1907.11341)

