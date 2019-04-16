---
layout: post
title: "Attention-GAN for Object Transfiguration in Wild Images"
date: 2018-03-19 04:00:13
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Attention GAN
author: Xinyuan Chen, Chang Xu, Xiaokang Yang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the object transfiguration problem in wild images. The generative network in classical GANs for object transfiguration often undertakes a dual responsibility: to detect the objects of interests and to convert the object from source domain to target domain. In contrast, we decompose the generative network into two separat networks, each of which is only dedicated to one particular sub-task. The attention network predicts spatial attention maps of images, and the transformation network focuses on translating objects. Attention maps produced by attention network are encouraged to be sparse, so that major attention can be paid to objects of interests. No matter before or after object transfiguration, attention maps should remain constant. In addition, learning attention network can receive more instructions, given the available segmentation annotations of images. Experimental results demonstrate the necessity of investigating attention in object transfiguration, and that the proposed algorithm can learn accurate attention to improve quality of generated images.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1803.06798](https://arxiv.org/abs/1803.06798)

##### PDF
[https://arxiv.org/pdf/1803.06798](https://arxiv.org/pdf/1803.06798)

