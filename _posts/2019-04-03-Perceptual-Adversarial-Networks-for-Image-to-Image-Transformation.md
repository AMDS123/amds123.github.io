---
layout: post
title: "Perceptual Adversarial Networks for Image-to-Image Transformation"
date: 2019-04-03 02:44:53
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Relation
author: Chaoyue Wang, Chang Xu, Chaohui Wang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a principled Perceptual Adversarial Networks (PAN) for image-to-image transformation tasks. Unlike existing application-specific algorithms, PAN provides a generic framework of learning mapping relationship between paired images (Fig. 1), such as mapping a rainy image to its de-rained counterpart, object edges to its photo, semantic labels to a scenes image, etc. The proposed PAN consists of two feed-forward convolutional neural networks (CNNs), the image transformation network T and the discriminative network D. Through combining the generative adversarial loss and the proposed perceptual adversarial loss, these two networks can be trained alternately to solve image-to-image transformation tasks. Among them, the hidden layers and output of the discriminative network D are upgraded to continually and automatically discover the discrepancy between the transformed image and the corresponding ground-truth. Simultaneously, the image transformation network T is trained to minimize the discrepancy explored by the discriminative network D. Through the adversarial training process, the image transformation network T will continually narrow the gap between transformed images and ground-truth images. Experiments evaluated on several image-to-image transformation tasks (e.g., image de-raining, image inpainting, etc.) show that the proposed PAN outperforms many related state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1706.09138](http://arxiv.org/abs/1706.09138)

##### PDF
[http://arxiv.org/pdf/1706.09138](http://arxiv.org/pdf/1706.09138)

