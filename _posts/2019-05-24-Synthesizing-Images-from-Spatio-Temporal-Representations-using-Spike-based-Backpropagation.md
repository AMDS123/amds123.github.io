---
layout: post
title: "Synthesizing Images from Spatio-Temporal Representations using Spike-based Backpropagation"
date: 2019-05-24 01:33:15
categories: arXiv_CV
tags: arXiv_CV
author: Deboleena Roy, Priyadarshini Panda, Kaushik Roy
mathjax: true
---

* content
{:toc}

##### Abstract
Spiking neural networks (SNNs) offer a promising alternative to current artificial neural networks to enable low-power event-driven neuromorphic hardware. Spike-based neuromorphic applications require processing and extracting meaningful information from spatio-temporal data, represented as series of spike trains over time. In this paper, we propose a method to synthesize images from multiple modalities in a spike-based environment. We use spiking auto-encoders to convert image and audio inputs into compact spatio-temporal representations that is then decoded for image synthesis. For this, we use a direct training algorithm that computes loss on the membrane potential of the output layer and back-propagates it by using a sigmoid approximation of the neuron's activation function to enable differentiability. The spiking autoencoders are benchmarked on MNIST and Fashion-MNIST and achieve very low reconstruction loss, comparable to ANNs. Then, spiking autoencoders are trained to learn meaningful spatio-temporal representations of the data, across the two modalities - audio and visual. We synthesize images from audio in a spike-based environment by first generating, and then utilizing such shared multi-modal spatio-temporal representations. Our audio to image synthesis model is tested on the task of converting TI-46 digits audio samples to MNIST images. We are able to synthesize images with high fidelity and the model achieves competitive performance against ANNs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.08861](http://arxiv.org/abs/1906.08861)

##### PDF
[http://arxiv.org/pdf/1906.08861](http://arxiv.org/pdf/1906.08861)

