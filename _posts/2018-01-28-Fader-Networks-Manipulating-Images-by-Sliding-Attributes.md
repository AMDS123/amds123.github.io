---
layout: post
title: "Fader Networks: Manipulating Images by Sliding Attributes"
date: 2018-01-28 16:12:14
categories: arXiv_CV
tags: arXiv_CV Salient Adversarial
author: Guillaume Lample, Neil Zeghidour, Nicolas Usunier, Antoine Bordes, Ludovic Denoyer, Marc&#x27;Aurelio Ranzato
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a new encoder-decoder architecture that is trained to reconstruct images by disentangling the salient information of the image and the values of attributes directly in the latent space. As a result, after training, our model can generate different realistic versions of an input image by varying the attribute values. By using continuous attribute values, we can choose how much a specific attribute is perceivable in the generated image. This property could allow for applications where users can modify an image using sliding knobs, like faders on a mixing console, to change the facial expression of a portrait, or to update the color of some objects. Compared to the state-of-the-art which mostly relies on training adversarial networks in pixel space by altering attribute values at train time, our approach results in much simpler training schemes and nicely scales to multiple attributes. We present evidence that our model can significantly change the perceived value of the attributes while preserving the naturalness of images.

##### Abstract (translated by Google)
本文介绍了一种新的编码器 - 解码器架构，通过解构图像的显着信息和直接在潜在空间中的属性的值来重建图像。因此，在训练之后，我们的模型可以通过改变属性值来生成输入图像的不同实际版本。通过使用连续的属性值，我们可以选择在生成的图像中特定属性是多少可感知的。该属性可以允许用户使用滑动旋钮修改图像的应用程序，例如混合控制台上的推子，改变肖像的面部表情或者更新某些对象的颜色。相比于最先进的技术，在训练时间通过改变属性值来训练像素空间中的对抗网络，我们的方法导致更简单的训练方案，并很好地扩展到多个属性。我们提出的证据表明，我们的模型可以显着改变属性的感知价值，同时保留图像的自然性。

##### URL
[http://arxiv.org/abs/1706.00409](http://arxiv.org/abs/1706.00409)

##### PDF
[http://arxiv.org/pdf/1706.00409](http://arxiv.org/pdf/1706.00409)

