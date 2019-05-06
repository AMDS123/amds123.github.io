---
layout: post
title: "SinGAN: Learning a Generative Model from a Single Natural Image"
date: 2019-05-02 16:15:38
categories: arXiv_CV
tags: arXiv_CV GAN CNN
author: Tamar Rott Shaham, Tali Dekel, Tomer Michaeli
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce SinGAN, an unconditional generative model that can be learned from a single natural image. Our model is trained to capture the internal distribution of patches within the image, and is then able to generate high quality, diverse samples that carry the same visual content as the image. SinGAN contains a pyramid of fully convolutional GANs, each responsible for learning the patch distribution at a different scale of the image. This allows generating new samples of arbitrary size and aspect ratio, that have significant variability, yet maintain both the global structure and the fine textures of the training image. In contrast to previous single image GAN schemes, our approach is not limited to texture images, and is not conditional (i.e. it generates samples from noise). User studies confirm that the generated samples are commonly confused to be real images. We illustrate the utility of SinGAN in a wide range of image manipulation tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.01164](http://arxiv.org/abs/1905.01164)

##### PDF
[http://arxiv.org/pdf/1905.01164](http://arxiv.org/pdf/1905.01164)

