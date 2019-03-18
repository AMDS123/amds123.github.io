---
layout: post
title: "Bringing Blurry Alive at High Frame-Rate with an Event Camera"
date: 2019-03-12 02:34:23
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Liyuan Pan, Richard Hartley, Cedric Scheerlinck, Miaomiao Liu, Xin Yu, Yuchao Dai
mathjax: true
---

* content
{:toc}

##### Abstract
Event-based cameras can measure intensity changes (called `{\it events}') with microsecond accuracy under high-speed motion and challenging lighting conditions. With the active pixel sensor (APS), the event camera allows simultaneous output of the intensity frames. However, the output images are captured at a relatively low frame-rate and often suffer from motion blur. A blurry image can be regarded as the integral of a sequence of latent images, while the events indicate the changes between the latent images. Therefore, we are able to model the blur-generation process by associating event data to a latent image. Based on the abundant event data and the low frame-rate easily blurred images, we propose a simple and effective approach to reconstruct a high-quality and high frame-rate shape video. Starting with a single blurry frame and its event data, we propose the \textbf{Event-based Double Integral (EDI)} model. Then, we extend it to \textbf{ multiple Event-based Double Integral (mEDI)} model to get more smooth and convincing results based on multiple images and their events. We also provide an efficient solver to minimize the proposed energy model. By optimizing the energy model, we achieve significant improvements in removing general blurs and reconstructing high temporal resolution video. The video generation is based on solving a simple non-convex optimization problem in a single scalar variable. Experimental results on both synthetic and real images demonstrate the superiority of our mEDI model and optimization method in comparison to the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06531](http://arxiv.org/abs/1903.06531)

##### PDF
[http://arxiv.org/pdf/1903.06531](http://arxiv.org/pdf/1903.06531)

