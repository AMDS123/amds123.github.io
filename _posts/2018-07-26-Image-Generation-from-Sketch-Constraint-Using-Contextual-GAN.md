---
layout: post
title: "Image Generation from Sketch Constraint Using Contextual GAN"
date: 2018-07-26 03:01:01
categories: arXiv_CV
tags: arXiv_CV Image_Caption Adversarial GAN
author: Yongyi Lu, Shangzhe Wu, Yu-Wing Tai, Chi-Keung Tang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we investigate image generation guided by hand sketch. When the input sketch is badly drawn, the output of common image-to-image translation follows the input edges due to the hard condition imposed by the translation process. Instead, we propose to use sketch as weak constraint, where the output edges do not necessarily follow the input edges. We address this problem using a novel joint image completion approach, where the sketch provides the image context for completing, or generating the output image. We train a generated adversarial network, i.e, contextual GAN to learn the joint distribution of sketch and the corresponding image by using joint images. Our contextual GAN has several advantages. First, the simple joint image representation allows for simple and effective learning of joint distribution in the same image-sketch space, which avoids complicated issues in cross-domain learning. Second, while the output is related to its input overall, the generated features exhibit more freedom in appearance and do not strictly align with the input features as previous conditional GANs do. Third, from the joint image's point of view, image and sketch are of no difference, thus exactly the same deep joint image completion network can be used for image-to-sketch generation. Experiments evaluated on three different datasets show that our contextual GAN can generate more realistic images than state-of-the-art conditional GANs on challenging inputs and generalize well on common categories.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1711.08972](https://arxiv.org/abs/1711.08972)

##### PDF
[https://arxiv.org/pdf/1711.08972](https://arxiv.org/pdf/1711.08972)

