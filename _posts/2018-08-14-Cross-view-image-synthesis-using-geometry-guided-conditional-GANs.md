---
layout: post
title: "Cross-view image synthesis using geometry-guided conditional GANs"
date: 2018-08-14 21:24:26
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Image_Generation
author: Krishna Regmi, Ali Borji
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of generating images across two drastically different views, namely ground (street) and aerial (overhead) views. Image synthesis by itself is a very challenging computer vision task and is even more so when generation is conditioned on an image in another view. Due the difference in viewpoints, there is small overlapping field of view and little common content between these two views. Here, we try to preserve the pixel information between the views so that the generated image is a realistic representation of cross view input image. For this, we propose to use homography as a guide to map the images between the views based on the common field of view to preserve the details in the input image. We then use generative adversarial networks to inpaint the missing regions in the transformed image and add realism to it. Our exhaustive evaluation and model comparison demonstrate that utilizing geometry constraints adds fine details to the generated images and can be a better approach for cross view image synthesis than purely pixel based synthesis methods.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.05469](https://arxiv.org/abs/1808.05469)

##### PDF
[https://arxiv.org/pdf/1808.05469](https://arxiv.org/pdf/1808.05469)

