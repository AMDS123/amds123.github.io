---
layout: post
title: "Authoring image decompositions with generative models"
date: 2016-12-05 18:59:53
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jason Rock, Theerasit Issaranon, Aditya Deshpande, David Forsyth
mathjax: true
---

* content
{:toc}

##### Abstract
We show how to extend traditional intrinsic image decompositions to incorporate further layers above albedo and shading. It is hard to obtain data to learn a multi-layer decomposition. Instead, we can learn to decompose an image into layers that are "like this" by authoring generative models for each layer using proxy examples that capture the Platonic ideal (Mondrian images for albedo; rendered 3D primitives for shading; material swatches for shading detail). Our method then generates image layers, one from each model, that explain the image. Our approach rests on innovation in generative models for images. We introduce a Convolutional Variational Auto Encoder (conv-VAE), a novel VAE architecture that can reconstruct high fidelity images. The approach is general, and does not require that layers admit a physical interpretation.

##### Abstract (translated by Google)
我们展示了如何扩展传统的固有图像分解，在反射和阴影之上加入更多的图层。学习多层分解很难获得数据。相反，我们可以通过使用代表柏拉图理想的代理示例（蒙德里安反照率图像;渲染用于阴影的3D图元;用于阴影细节的材质色板）创作每个图层的生成模型，来学习将图像分解为“像这样” 。然后，我们的方法生成图像层，每个模型一个，解释图像。我们的方法取决于图像生成模型的创新。我们引入了卷积变分自动编码器（conv-VAE），这是一种可以重建高保真图像的新型VAE架构。这种方法是一般的，并不要求层承认物理解释。

##### URL
[https://arxiv.org/abs/1612.01479](https://arxiv.org/abs/1612.01479)

##### PDF
[https://arxiv.org/pdf/1612.01479](https://arxiv.org/pdf/1612.01479)

