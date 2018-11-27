---
layout: post
title: "Unsupervised 3D Shape Learning from Image Collections in the Wild"
date: 2018-11-26 17:21:30
categories: arXiv_CV
tags: arXiv_CV Adversarial Face CNN
author: Attila Szaboó, Paolo Favaro
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to learn the 3D surface of objects directly from a collection of images. Previous work achieved this capability by exploiting additional manual annotation, such as object pose, 3D surface templates, temporal continuity of videos, manually selected landmarks, and foreground/background masks. In contrast, our method does not make use of any such annotation. Rather, it builds a generative model, a convolutional neural network, which, given a noise vector sample, outputs the 3D surface and texture of an object and a background image. These 3 components combined with an additional random viewpoint vector are then fed to a differential renderer to produce a view of the sampled object and background. Our general principle is that if the output of the renderer, the generated image, is realistic, then its input, the generated 3D and texture, should also be realistic. To achieve realism, the generative model is trained adversarially against a discriminator that tries to distinguish between the output of the renderer and real images from the given data set. Moreover, our generative model can be paired with an encoder and trained as an autoencoder, to automatically extract the 3D shape, texture and pose of the object in an image. Our trained generative model and encoder show promising results both on real and synthetic data, which demonstrate for the first time that fully unsupervised 3D learning from image collections is possible.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1811.10519](https://arxiv.org/abs/1811.10519)

##### PDF
[https://arxiv.org/pdf/1811.10519](https://arxiv.org/pdf/1811.10519)

