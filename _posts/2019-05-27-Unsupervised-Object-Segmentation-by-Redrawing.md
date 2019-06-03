---
layout: post
title: "Unsupervised Object Segmentation by Redrawing"
date: 2019-05-27 12:34:55
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation
author: Micka&#xeb;l Chen, Thierry Arti&#xe8;res, Ludovic Denoyer
mathjax: true
---

* content
{:toc}

##### Abstract
Object segmentation is a crucial problem that is usually solved by using supervised learning approaches over very large datasets composed of both images and corresponding object masks. Since the masks have to be provided at pixel level, building such a dataset for any new domain can be very costly. We present ReDO, a new model able to extract objects from images without any annotation in an unsupervised way. It relies on the idea that it should be possible to change the textures or colors of the objects without changing the overall distribution of the dataset. Following this assumption, our approach is based on an adversarial architecture where the generator is guided by an input sample: given an image, it extracts the object mask, then redraws a new object at the same location. The generator is controlled by a discriminator that ensures that the distribution of generated images is aligned to the original one. We experiment with this method on different datasets and demonstrate the good quality of extracted masks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13539](http://arxiv.org/abs/1905.13539)

##### PDF
[http://arxiv.org/pdf/1905.13539](http://arxiv.org/pdf/1905.13539)

