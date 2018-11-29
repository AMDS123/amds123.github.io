---
layout: post
title: "CrowdCam: Dynamic Region Segmentation"
date: 2018-11-28 09:19:42
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Nir Zarrabi, Shai Avidan, Yael Moses
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of segmenting dynamic regions in CrowdCam images, where a dynamic region is the projection of a moving 3D object on the image plane. Quite often, these regions are the most interesting parts of an image. CrowdCam images is a set of images of the same dynamic event, captured by a group of non-collaborating users. Almost every event of interest today is captured this way. This new type of images raises the need to develop new algorithms tailored specifically for it. We propose an algorithm that segments the dynamic regions in CrowdCam images. The proposed algorithm combines cues that are based on geometry, appearance and proximity. First, geometric reasoning is used to produce rough score maps that determine, for every pixel, how likely it is to be the projection of a static or dynamic scene point. These maps are noisy because CrowdCam images are usually few and far apart both in space and in time. Then, we use similarity in appearance space and proximity in the image plane to encourage neighboring pixels to be labeled similarly as either static or dynamic. We define an objective function that combines all the cues and solves it using an MRF solver. The proposed method was tested on publicly available CrowdCam datasets, as well as a new and challenging dataset we collected. Our results are better than the current state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11455](http://arxiv.org/abs/1811.11455)

##### PDF
[http://arxiv.org/pdf/1811.11455](http://arxiv.org/pdf/1811.11455)

