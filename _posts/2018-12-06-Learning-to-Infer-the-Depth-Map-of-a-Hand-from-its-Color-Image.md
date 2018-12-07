---
layout: post
title: "Learning to Infer the Depth Map of a Hand from its Color Image"
date: 2018-12-06 12:16:37
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Inference
author: Vassilis C. Nicodemou, Iason Oikonomidis, Georgios Tzimiropoulos, Antonis Argyros
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the first approach to the problem of inferring the depth map of a human hand based on a single RGB image. We achieve this with a Convolutional Neural Network (CNN) that employs a stacked hourglass model as its main building block. Intermediate supervision is used in several outputs of the proposed architecture in a staged approach. To aid the process of training and inference, hand segmentation masks are also estimated in such an intermediate supervision step, and used to guide the subsequent depth estimation process. In order to train and evaluate the proposed method we compile and make publicly available HandRGBD, a new dataset of 20,601 views of hands, each consisting of an RGB image and an aligned depth map. Based on HandRGBD, we explore variants of the proposed approach in an ablative study and determine the best performing one. The results of an extensive experimental evaluation demonstrate that hand depth estimation from a single RGB frame can be achieved with an accuracy of 22mm, which is comparable to the accuracy achieved by contemporary low-cost depth cameras. Such a 3D reconstruction of hands based on RGB information is valuable as a final result on its own right, but also as an input to several other hand analysis and perception algorithms that require depth input. Essentially, in such a context, the proposed approach bridges the gap between RGB and RGBD, by making all existing RGBD-based methods applicable to RGB input.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02486](http://arxiv.org/abs/1812.02486)

##### PDF
[http://arxiv.org/pdf/1812.02486](http://arxiv.org/pdf/1812.02486)

