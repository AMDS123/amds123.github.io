---
layout: post
title: "PasteGAN: A Semi-Parametric Method to Generate Image from Scene Graph"
date: 2019-05-05 05:16:09
categories: arXiv_CV
tags: arXiv_CV GAN Relation
author: Yikang Li, Tao Ma, Yeqi Bai, Nan Duan, Sining Wei, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Despite some exciting progress on high-quality image generation from structured~(scene graphs) or free-form~(sentences) descriptions, most of them only guarantee the image-level semantical consistency, \ie the generated image matching the semantic meaning of the description. However, it still lacks the investigations on synthesizing the images in a more controllable way, like finely manipulating the visual appearance of every object. Therefore, to generate the images with preferred objects and rich interactions, we propose a semi-parametric method, denoted as PasteGAN, for generating the image from the scene graph, where spatial arrangements of the objects and their pair-wise relationships are defined by the scene graph and the object appearances are determined by given object crops. To enhance the interactions of the objects in the output, we design a Crop Refining Network to embed the objects as well as their relationships into one map. Multiple losses work collaboratively to guarantee the generated images highly respecting the crops and complying with the scene graphs while maintaining excellent image quality. A crop selector is also proposed to pick the most-compatible crops from our external object tank by encoding the interactions around the objects in the scene graph if the crops are not provided. Evaluated on Visual Genome and COCO-Stuff, our proposed method significantly outperforms the SOTA methods on both Inception Score and Diversity Score with a huge margin. Extensive experiments also demonstrate our method's ability to generate complex and diverse images with given objects.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01608](http://arxiv.org/abs/1905.01608)

##### PDF
[http://arxiv.org/pdf/1905.01608](http://arxiv.org/pdf/1905.01608)

