---
layout: post
title: "Mocycle-GAN: Unpaired Video-to-Video Translation"
date: 2019-08-26 07:51:17
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN
author: Yang Chen, Yingwei Pan, Ting Yao, Xinmei Tian, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised image-to-image translation is the task of translating an image from one domain to another in the absence of any paired training examples and tends to be more applicable to practical applications. Nevertheless, the extension of such synthesis from image-to-image to video-to-video is not trivial especially when capturing spatio-temporal structures in videos. The difficulty originates from the aspect that not only the visual appearance in each frame but also motion between consecutive frames should be realistic and consistent across transformation. This motivates us to explore both appearance structure and temporal continuity in video synthesis. In this paper, we present a new Motion-guided Cycle GAN, dubbed as Mocycle-GAN, that novelly integrates motion estimation into unpaired video translator. Technically, Mocycle-GAN capitalizes on three types of constrains: adversarial constraint discriminating between synthetic and real frame, cycle consistency encouraging an inverse translation on both frame and motion, and motion translation validating the transfer of motion between consecutive frames. Extensive experiments are conducted on video-to-labels and labels-to-video translation, and superior results are reported when comparing to state-of-the-art methods. More remarkably, we qualitatively demonstrate our Mocycle-GAN for both flower-to-flower and ambient condition transfer.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09514](http://arxiv.org/abs/1908.09514)

##### PDF
[http://arxiv.org/pdf/1908.09514](http://arxiv.org/pdf/1908.09514)

