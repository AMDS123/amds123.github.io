---
layout: post
title: "ELEGANT: Exchanging Latent Encodings with GAN for Transferring Multiple Face Attributes"
date: 2018-07-25 06:13:06
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face
author: Taihong Xiao, Jiapeng Hong, Jinwen Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Recent studies on face attribute transfer have achieved great success. A lot of models are able to transfer face attributes with an input image. However, they suffer from three limitations: (1) incapability of generating image by exemplars; (2) being unable to transfer multiple face attributes simultaneously; (3) low quality of generated images, such as low-resolution or artifacts. To address these limitations, we propose a novel model which receives two images of opposite attributes as inputs. Our model can transfer exactly the same type of attributes from one image to another by exchanging certain part of their encodings. All the attributes are encoded in a disentangled manner in the latent space, which enables us to manipulate several attributes simultaneously. Besides, our model learns the residual images so as to facilitate training on higher resolution images. With the help of multi-scale discriminators for adversarial training, it can even generate high-quality images with finer details and less artifacts. We demonstrate the effectiveness of our model on overcoming the above three limitations by comparing with other methods on the CelebA face database. A pytorch implementation is available at this https URL.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.10562](https://arxiv.org/abs/1803.10562)

##### PDF
[https://arxiv.org/pdf/1803.10562](https://arxiv.org/pdf/1803.10562)

