---
layout: post
title: "Adaptive Image Sampling using Deep Learning and its Application on X-Ray Fluorescence Image Reconstruction"
date: 2018-12-27 21:53:14
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Detection
author: Qiqin Dai, Henry Chopp, Emeline Pouyet, Oliver Cossairt, Marc Walton, Aggelos K. Katsaggelos
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an adaptive image sampling algorithm based on Deep Learning (DL). The adaptive sampling mask generation network is jointly trained with an image inpainting network. The sampling rate is controlled in the mask generation network, and a binarization strategy is investigated to make the sampling mask binary. Besides the image sampling and reconstruction application, we show that the proposed adaptive sampling algorithm is able to speed up raster scan processes such as the X-Ray fluorescence (XRF) image scanning process. Recently XRF laboratory-based systems have evolved to lightweight and portable instruments thanks to technological advancements in both X-Ray generation and detection. However, the scanning time of an XRF image is usually long due to the long exposures requires (e.g., $100 \mu s-1ms$ per point). We propose an XRF image inpainting approach to address the issue of long scanning time, thus speeding up the scanning process while still maintaining the possibility to reconstruct a high quality XRF image. The proposed adaptive image sampling algorithm is applied to the RGB image of the scanning target to generate the sampling mask. The XRF scanner is then driven according to the sampling mask to scan a subset of the total image pixels. Finally, we inpaint the scanned XRF image by fusing the RGB image to reconstruct the full scan XRF image. The experiments show that the proposed adaptive sampling algorithm is able to effectively sample the image and achieve a better reconstruction accuracy than that of the existing methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.10836](http://arxiv.org/abs/1812.10836)

##### PDF
[http://arxiv.org/pdf/1812.10836](http://arxiv.org/pdf/1812.10836)

