---
layout: post
title: "High Frame Rate Video Reconstruction based on an Event Camera"
date: 2019-04-23 04:46:16
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization
author: Liyuan Pan, Richard Hartley, Cedric Scheerlinck, Miaomiao Liu, Xin Yu, Yuchao Dai
mathjax: true
---

* content
{:toc}

##### Abstract
Event-based cameras measure intensity changes (called events) with microsecond accuracy under high-speed motion and challenging lighting conditions. With the active pixel sensor (APS), event cameras allow simultaneous output of intensity frames. However, the output images are captured at a relatively low frame rate and often suffer from motion blur. A blurred image can be regarded as the integral of a sequence of latent images, while events indicate changes between the latent images. Thus, we are able to model the blur-generation process by associating event data to a latent sharp image. Based on the abundant event data alongside low frame rate, easily blurred images, we propose a simple yet effective approach to reconstruct high-quality and high frame rate sharp videos. Starting with a single blurred frame and its event data, we propose the Event-based Double Integral (EDI) model and solve it by adding regularization terms. Then, we extend it to multiple Event-based Double Integral (mEDI) model to get more smooth results based on multiple images and their events. Furthermore, we provide a new and more efficient solver to minimize the proposed energy model. By optimizing the energy function, we achieve significant improvements in removing blur and the reconstruction of a high temporal resolution video. The video generation is based on solving a simple non-convex optimization problem in a single scalar variable. Experimental results on both synthetic and real sequences demonstrate the superiority of our mEDI model and optimization method compared to the state of the art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06531](http://arxiv.org/abs/1903.06531)

##### PDF
[http://arxiv.org/pdf/1903.06531](http://arxiv.org/pdf/1903.06531)

