---
layout: post
title: "Coupled Learning for Facial Deblur"
date: 2019-04-18 10:24:15
categories: arXiv_CV
tags: arXiv_CV Face Recognition Face_Recognition
author: Dayong Tian, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Blur in facial images significantly impedes the efficiency of recognition approaches. However, most existing blind deconvolution methods cannot generate satisfactory results due to their dependence on strong edges, which are sufficient in natural images but not in facial images. In this paper, we represent point spread functions (PSFs) by the linear combination of a set of pre-defined orthogonal PSFs, and similarly, an estimated intrinsic (EI) sharp face image is represented by the linear combination of a set of pre-defined orthogonal face images. In doing so, PSF and EI estimation is simplified to discovering two sets of linear combination coefficients, which are simultaneously found by our proposed coupled learning algorithm. To make our method robust to different types of blurry face images, we generate several candidate PSFs and EIs for a test image, and then, a non-blind deconvolution method is adopted to generate more EIs by those candidate PSFs. Finally, we deploy a blind image quality assessment metric to automatically select the optimal EI. Thorough experiments on the facial recognition technology database, extended Yale face database B, CMU pose, illumination, and expression (PIE) database, and face recognition grand challenge database version 2.0 demonstrate that the proposed approach effectively restores intrinsic sharp face images and, consequently, improves the performance of face recognition.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08671](http://arxiv.org/abs/1904.08671)

##### PDF
[http://arxiv.org/pdf/1904.08671](http://arxiv.org/pdf/1904.08671)

