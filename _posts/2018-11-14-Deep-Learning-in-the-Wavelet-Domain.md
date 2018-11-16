---
layout: post
title: "Deep Learning in the Wavelet Domain"
date: 2018-11-14 23:33:09
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Fergal Cotter, Nick Kingsbury
mathjax: true
---

* content
{:toc}

##### Abstract
This paper examines the possibility of, and the possible advantages to learning the filters of convolutional neural networks (CNNs) for image analysis in the wavelet domain. We are stimulated by both Mallat's scattering transform and the idea of filtering in the Fourier domain. It is important to explore new spaces in which to learn, as these may provide inherent advantages that are not available in the pixel space. However, the scattering transform is limited by its inability to learn in between scattering orders, and any Fourier domain filtering is limited by the large number of filter parameters needed to get localized filters. Instead we consider filtering in the wavelet domain with learnable filters. The wavelet space allows us to have local, smooth filters with far fewer parameters, and learnability can give us flexibility. We present a novel layer which takes CNN activations into the wavelet space, learns parameters and returns to the pixel space. This allows it to be easily dropped in to any neural network without affecting the structure. As part of this work, we show how to pass gradients through a multirate system and give preliminary results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06115](http://arxiv.org/abs/1811.06115)

##### PDF
[http://arxiv.org/pdf/1811.06115](http://arxiv.org/pdf/1811.06115)

