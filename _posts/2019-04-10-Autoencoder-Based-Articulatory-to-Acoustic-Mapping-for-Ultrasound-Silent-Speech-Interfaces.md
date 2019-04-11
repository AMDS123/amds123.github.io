---
layout: post
title: "Autoencoder-Based Articulatory-to-Acoustic Mapping for Ultrasound Silent Speech Interfaces"
date: 2019-04-10 15:57:07
categories: arXiv_SD
tags: arXiv_SD Face Relation
author: G&#xe1;bor Gosztolya, &#xc1;d&#xe1;m Pint&#xe9;r, L&#xe1;szl&#xf3; T&#xf3;th, Tam&#xe1;s Gr&#xf3;sz, Alexandra Mark&#xf3;, Tam&#xe1;s G&#xe1;bor Csap&#xf3;
mathjax: true
---

* content
{:toc}

##### Abstract
When using ultrasound video as input, Deep Neural Network-based Silent Speech Interfaces usually rely on the whole image to estimate the spectral parameters required for the speech synthesis step. Although this approach is quite straightforward, and it permits the synthesis of understandable speech, it has several disadvantages as well. Besides the inability to capture the relations between close regions (i.e. pixels) of the image, this pixel-by-pixel representation of the image is also quite uneconomical. It is easy to see that a significant part of the image is irrelevant for the spectral parameter estimation task as the information stored by the neighbouring pixels is redundant, and the neural network is quite large due to the large number of input features. To resolve these issues, in this study we train an autoencoder neural network on the ultrasound image; the estimation of the spectral speech parameters is done by a second DNN, using the activations of the bottleneck layer of the autoencoder network as features. In our experiments, the proposed method proved to be more efficient than the standard approach: the measured normalized mean squared error scores were lower, while the correlation values were higher in each case. Based on the result of a listening test, the synthesized utterances also sounded more natural to native speakers. A further advantage of our proposed approach is that, due to the (relatively) small size of the bottleneck layer, we can utilize several consecutive ultrasound images during estimation without a significant increase in the network size, while significantly increasing the accuracy of parameter estimation.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.05259](http://arxiv.org/abs/1904.05259)

##### PDF
[http://arxiv.org/pdf/1904.05259](http://arxiv.org/pdf/1904.05259)

