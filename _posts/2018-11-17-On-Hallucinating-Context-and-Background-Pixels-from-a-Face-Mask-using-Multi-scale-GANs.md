---
layout: post
title: "On Hallucinating Context and Background Pixels from a Face Mask using Multi-scale GANs"
date: 2018-11-17 05:52:13
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Face Recognition
author: Sandipan Banerjee, Walter J. Scheirer, Kevin W. Bowyer, Patrick J. Flynn
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a multi-scale GAN model to hallucinate realistic context (forehead, hair, neck, clothes) and background pixels automatically from a single input face mask. Instead of swapping a face on to an existing picture, our model directly generates realistic context and background pixels based on the features of the provided face mask. Unlike face inpainting algorithms, it can generate realistic hallucinations even for a large number of missing pixels. Our model is composed of a cascaded network of GAN blocks, each tasked with hallucination of missing pixels at a particular resolution while guiding the synthesis process of the next GAN block. The hallucinated full face image is made photo-realistic by using a combination of reconstruction, perceptual, adversarial and identity preserving losses at each block of the network. With a set of extensive experiments, we demonstrate the effectiveness of our model in hallucinating context and background pixels from face masks varying in facial pose, expression and lighting, collected from multiple datasets subject disjoint with our training data. We also compare our method with two popular face swapping and face completion methods in terms of visual quality and recognition performance. Additionally, we analyze our cascaded pipeline and compare it with the recently proposed progressive growing of GANs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07104](http://arxiv.org/abs/1811.07104)

##### PDF
[http://arxiv.org/pdf/1811.07104](http://arxiv.org/pdf/1811.07104)

