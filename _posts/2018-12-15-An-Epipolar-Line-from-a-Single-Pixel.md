---
layout: post
title: "An Epipolar Line from a Single Pixel"
date: 2018-12-15 17:48:59
categories: arXiv_CV
tags: arXiv_CV
author: Tavi Halperin, Michael Werman
mathjax: true
---

* content
{:toc}

##### Abstract
Computing the epipolar geometry from feature points between cameras with very different viewpoints is often error prone, as an object's appearance can vary greatly between images. For such cases, it has been shown that using motion extracted from video can achieve much better results than using a static image. This paper extends these earlier works based on the scene dynamics. In this paper we propose a new method to compute the epipolar geometry from a video stream, by exploiting the following observation: For a pixel p in Image A, all pixels corresponding to p in Image B are on the same epipolar line. Equivalently, the image of the line going through camera A's center and p is an epipolar line in B. Therefore, when cameras A and B are synchronized, the momentary images of two objects projecting to the same pixel, p, in camera A at times t1 and t2, lie on an epipolar line in camera B. Based on this observation we achieve fast and precise computation of epipolar lines. Calibrating cameras based on our method of finding epipolar lines is much faster and more robust than previous methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1703.09725](http://arxiv.org/abs/1703.09725)

##### PDF
[http://arxiv.org/pdf/1703.09725](http://arxiv.org/pdf/1703.09725)

