---
layout: post
title: "Unsupervised RGBD Video Object Segmentation Using GANs"
date: 2018-11-05 06:11:24
categories: arXiv_CV
tags: arXiv_CV Segmentation GAN
author: Maryam Sultana, Arif Mahmood, Sajid Javed, Soon Ki Jung
mathjax: true
---

* content
{:toc}

##### Abstract
Video object segmentation is a fundamental step in many advanced vision applications. Most existing algorithms are based on handcrafted features such as HOG, super-pixel segmentation or texture-based techniques, while recently deep features have been found to be more efficient. Existing algorithms observe performance degradation in the presence of challenges such as illumination variations, shadows, and color camouflage. To handle these challenges we propose a fusion based moving object segmentation algorithm which exploits color as well as depth information using GAN to achieve more accuracy. Our goal is to segment moving objects in the presence of challenging background scenes, in real environments. To address this problem, GAN is trained in an unsupervised manner on color and depth information independently with challenging video sequences. During testing, the trained GAN generates backgrounds similar to that in the test sample. The generated background samples are then compared with the test sample to segment moving objects. The final result is computed by fusion of object boundaries in both modalities, RGB and the depth. The comparison of our proposed algorithm with five state-of-the-art methods on publicly available dataset has shown the strength of our algorithm for moving object segmentation in videos in the presence of challenging real scenarios.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01526](http://arxiv.org/abs/1811.01526)

##### PDF
[http://arxiv.org/pdf/1811.01526](http://arxiv.org/pdf/1811.01526)

