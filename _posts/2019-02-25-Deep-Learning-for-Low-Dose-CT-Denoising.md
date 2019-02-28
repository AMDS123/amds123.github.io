---
layout: post
title: "Deep Learning for Low-Dose CT Denoising"
date: 2019-02-25 21:14:45
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Detection
author: Maryam Gholizadeh-Ansari, Javad Alirezaie, Paul Babyn
mathjax: true
---

* content
{:toc}

##### Abstract
Low-dose CT denoising is a challenging task that has been studied by many researchers. Some studies have used deep neural networks to improve the quality of low-dose CT images and achieved fruitful results. In this paper, we propose a deep neural network that uses dilated convolutions with different dilation rates instead of standard convolution helping to capture more contextual information in fewer layers. Also, we have employed residual learning by creating shortcut connections to transmit image information from the early layers to later ones. To further improve the performance of the network, we have introduced a non-trainable edge detection layer that extracts edges in horizontal, vertical, and diagonal directions. Finally, we demonstrate that optimizing the network by a combination of mean-square error loss and perceptual loss preserves many structural details in the CT image. This objective function does not suffer from over smoothing and blurring effects caused by per-pixel loss and grid-like artifacts resulting from perceptual loss. The experiments show that each modification to the network improves the outcome while only minimally changing the complexity of the network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.10127](http://arxiv.org/abs/1902.10127)

##### PDF
[http://arxiv.org/pdf/1902.10127](http://arxiv.org/pdf/1902.10127)

