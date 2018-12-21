---
layout: post
title: "Multichannel Online Dereverberation based on Spectral Magnitude Inverse Filtering"
date: 2018-12-20 10:35:01
categories: arXiv_SD
tags: arXiv_SD Speech_Recognition Gradient_Descent Relation Recognition
author: Xiaofei Li, Laurent Girin, Sharon Gannot, Radu Horaud
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of multichannel online dereverberation. The proposed method is carried out in the short-time Fourier transform (STFT) domain, and for each frequency band independently. In the STFT domain, the time-domain room impulse response is approximately represented by the convolutive transfer function (CTF). The multichannel CTFs are adaptively identified based on the cross-relation method, and using the recursive least square criterion. Instead of the complex-valued CTF convolution model, we use a nonnegative convolution model between the STFT magnitude of the source signal and the CTF magnitude, which is just a coarse approximation of the former model, but is shown to be more robust against the CTF perturbations. Based on this nonnegative model, we propose an online STFT magnitude inverse filtering method. The inverse filters of the CTF magnitude are formulated based on the multiple-input/output inverse theorem (MINT), and adaptively estimated based on the gradient descent criterion. Finally, the inverse filtering is applied to the STFT magnitude of the microphone signals, obtaining an estimate of the STFT magnitude of the source signal. Experiments regarding both speech enhancement and automatic speech recognition are conducted, which demonstrate that the proposed method can effectively suppress reverberation, even for the difficult case of a moving speaker.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08471](http://arxiv.org/abs/1812.08471)

##### PDF
[http://arxiv.org/pdf/1812.08471](http://arxiv.org/pdf/1812.08471)

