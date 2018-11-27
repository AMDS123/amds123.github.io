---
layout: post
title: "Geometry-Consistent Generative Adversarial Networks for One-Sided Unsupervised Domain Mapping"
date: 2018-11-26 00:49:30
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN Quantitative
author: Huan Fu, Mingming Gong, Chaohui Wang, Kayhan Batmanghelich, Kun Zhang, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised domain mapping aims to learn a function to translate domain X to Y by a function GXY in the absence of paired examples. Finding the optimal GXY without paired data is an ill-posed problem, so appropriate constraints are required to obtain reasonable solutions. One of the most prominent constraints is cycle consistency, which enforces the translated image by GXY to be translated back to the input image by an inverse mapping GYX. While cycle consistency requires the simultaneous training of GXY and GY X, recent studies have shown that one-sided domain mapping can be achieved by preserving pairwise distances between images. Although cycle consistency and distance preservation successfully constrain the solution space, they overlook the special properties that simple geometric transformations do not change the semantic structure of images. Based on this special property, we develop a geometry-consistent generative adversarial network (GcGAN), which enables one-sided unsupervised domain mapping. GcGAN takes the original image and its counterpart image transformed by a predefined geometric transformation as inputs and generates two images in the new domain coupled with the corresponding geometry-consistency constraint. The geometry-consistency constraint reduces the space of possible solutions while keep the correct solutions in the search space. Quantitative and qualitative comparisons with the baseline (GAN alone) and the state-of-the-art methods including CycleGAN and DistanceGAN demonstrate the effectiveness of our method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.05852](http://arxiv.org/abs/1809.05852)

##### PDF
[http://arxiv.org/pdf/1809.05852](http://arxiv.org/pdf/1809.05852)

