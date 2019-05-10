---
layout: post
title: "Handheld Multi-Frame Super-Resolution"
date: 2019-05-08 18:09:15
categories: arXiv_CV
tags: arXiv_CV Super_Resolution
author: Bartlomiej Wronski, Ignacio Garcia-Dorado, Manfred Ernst, Damien Kelly, Michael Krainin, Chia-Kai Liang, Marc Levoy, Peyman Milanfar
mathjax: true
---

* content
{:toc}

##### Abstract
Compared to DSLR cameras, smartphone cameras have smaller sensors, which limits their spatial resolution; smaller apertures, which limits their light gathering ability; and smaller pixels, which reduces their signal-to noise ratio. The use of color filter arrays (CFAs) requires demosaicing, which further degrades resolution. In this paper, we supplant the use of traditional demosaicing in single-frame and burst photography pipelines with a multiframe super-resolution algorithm that creates a complete RGB image directly from a burst of CFA raw images. We harness natural hand tremor, typical in handheld photography, to acquire a burst of raw frames with small offsets. These frames are then aligned and merged to form a single image with red, green, and blue values at every pixel site. This approach, which includes no explicit demosaicing step, serves to both increase image resolution and boost signal to noise ratio. Our algorithm is robust to challenging scene conditions: local motion, occlusion, or scene changes. It runs at 100 milliseconds per 12-megapixel RAW input burst frame on mass-produced mobile phones. Specifically, the algorithm is the basis of the Super-Res Zoom feature, as well as the default merge method in Night Sight mode (whether zooming or not) on Google's flagship phone.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.03277](http://arxiv.org/abs/1905.03277)

##### PDF
[http://arxiv.org/pdf/1905.03277](http://arxiv.org/pdf/1905.03277)

