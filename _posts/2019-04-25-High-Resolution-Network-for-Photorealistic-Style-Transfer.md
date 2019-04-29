---
layout: post
title: "High-Resolution Network for Photorealistic Style Transfer"
date: 2019-04-25 22:59:37
categories: arXiv_CV
tags: arXiv_CV Style_Transfer
author: Ming Li, Chunyang Ye, Wei Li
mathjax: true
---

* content
{:toc}

##### Abstract
Photorealistic style transfer aims to transfer the style of one image to another, but preserves the original structure and detail outline of the content image, which makes the content image still look like a real shot after the style transfer. Although some realistic image styling methods have been proposed, these methods are vulnerable to lose the details of the content image and produce some irregular distortion structures. In this paper, we use a high-resolution network as the image generation network. Compared to other methods, which reduce the resolution and then restore the high resolution, our generation network maintains high resolution throughout the process. By connecting high-resolution subnets to low-resolution subnets in parallel and repeatedly multi-scale fusion, high-resolution subnets can continuously receive information from low-resolution subnets. This allows our network to discard less information contained in the image, so the generated images may have a more elaborate structure and less distortion, which is crucial to the visual quality. We conducted extensive experiments and compared the results with existing methods. The experimental results show that our model is effective and produces better results than existing methods for photorealistic image stylization. Our source code with PyTorch framework will be publicly available at https://github.com/limingcv/Photorealistic-Style-Transfer

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11617](http://arxiv.org/abs/1904.11617)

##### PDF
[http://arxiv.org/pdf/1904.11617](http://arxiv.org/pdf/1904.11617)

