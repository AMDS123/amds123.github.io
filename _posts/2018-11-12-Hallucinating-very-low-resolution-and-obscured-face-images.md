---
layout: post
title: "Hallucinating very low-resolution and obscured face images"
date: 2018-11-12 10:40:09
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning Detection
author: Lianping Yang, Bin Shao, Ting Sun, Song Ding, Xiangde Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the face hallucination methods are often designed for complete inputs. They cannot work well if the inputs are very tiny and contaminated by large occlusion. Inspired by this fact, we propose a novel obscured face hallucination network(OFHNet) using deep learning. Our OFHNet consists of four parts: an inpainting network, an upsampling network, a discriminative network, and a fixed facial landmark detection network. Firstly, we use the inpainting network restores the low-resolution(LR) obscured face images. Secondly, we employ the upsampling network to upsample outputs of the inpainting network. To ensure the generated high-resolution(HR) face images more photo-realistic, we use the discriminative network and the facial landmark detection network to help upsampling network. In addition, we present a new semantic structure loss, which can make the generated HR face images more pleasing. Extensive experiments show that our framework can restore the appealing HR face images from 1/4 missing area LR face images with a challenging scaling factor of 8x.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.04645](http://arxiv.org/abs/1811.04645)

##### PDF
[http://arxiv.org/pdf/1811.04645](http://arxiv.org/pdf/1811.04645)

