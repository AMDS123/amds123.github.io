---
layout: post
title: "Photorealistic Video Super Resolution"
date: 2018-07-20 16:39:15
categories: arXiv_CV
tags: arXiv_CV Adversarial Super_Resolution
author: Eduardo P&#xe9;rez-Pellitero, Mehdi S. M. Sajjadi, Michael Hirsch, Bernhard Sch&#xf6;lkopf
mathjax: true
---

* content
{:toc}

##### Abstract
With the advent of perceptual loss functions, new possibilities in super-resolution have emerged, and we currently have models that successfully generate near-photorealistic high-resolution images from their low-resolution observations. Up to now, however, such approaches have been exclusively limited to single image super-resolution. The application of perceptual loss functions on video processing still entails several challenges, mostly related to the lack of temporal consistency of the generated images, i.e., flickering artifacts. In this work, we present a novel adversarial recurrent network for video upscaling that is able to produce realistic textures in a temporally consistent way. The proposed architecture naturally leverages information from previous frames due to its recurrent architecture, i.e. the input to the generator is composed of the low-resolution image and, additionally, the warped output of the network at the previous step. We also propose an additional loss function to further reinforce temporal consistency in the generated sequences. The experimental validation of our algorithm shows the effectiveness of our approach which obtains competitive samples in terms of perceptual quality with improved temporal consistency.

##### Abstract (translated by Google)
随着感知损失函数的出现，超分辨率的新可能性已经出现，我们目前拥有的模型可以通过低分辨率观测成功生成近真实感的高分辨率图像。然而，到目前为止，这种方法仅限于单图像超分辨率。感知损失函数在视频处理上的应用仍然带来若干挑战，主要涉及所生成图像的时间一致性缺乏，即闪烁伪像。在这项工作中，我们提出了一种新颖的对抗性循环网络，用于视频放大，能够以时间一致的方式生成逼真的纹理。由于其重复架构，所提出的架构自然地利用来自先前帧的信息，即，对发生器的输入由低分辨率图像组成，并且另外，在前一步骤中由网络的翘曲输出组成。我们还提出了额外的损失函数，以进一步加强所生成序列的时间一致性。我们的算法的实验验证表明了我们的方法的有效性，该方法在感知质量方面获得竞争性样本，同时提高了时间一致性。

##### URL
[http://arxiv.org/abs/1807.07930](http://arxiv.org/abs/1807.07930)

##### PDF
[http://arxiv.org/pdf/1807.07930](http://arxiv.org/pdf/1807.07930)

