---
layout: post
title: "Mixed-precision training of deep neural networks using computational memory"
date: 2017-12-04 16:54:12
categories: arXiv_CV
tags: arXiv_CV GAN Speech_Recognition Classification Recognition
author: Nandakumar S. R., Manuel Le Gallo, Irem Boybat, Bipin Rajendran, Abu Sebastian, Evangelos Eleftheriou
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have revolutionized the field of machine learning by providing unprecedented human-like performance in solving many real-world problems such as image and speech recognition. Training of large DNNs, however, is a computationally intensive task, and this necessitates the development of novel computing architectures targeting this application. A computational memory unit where resistive memory devices are organized in crossbar arrays can be used to locally store the synaptic weights in their conductance states. The expensive multiply accumulate operations can be performed in place using Kirchhoff's circuit laws in a non-von Neumann manner. However, a key challenge remains the inability to alter the conductance states of the devices in a reliable manner during the weight update process. We propose a mixed-precision architecture that combines a computational memory unit storing the synaptic weights with a digital processing unit and an additional memory unit accumulating weight updates in high precision. The new architecture delivers classification accuracies comparable to those of floating-point implementations without being constrained by challenges associated with the non-ideal weight update characteristics of emerging resistive memories. A two layer neural network in which the computational memory unit is realized using non-linear stochastic models of phase-change memory devices achieves a test accuracy of 97.40% on the MNIST handwritten digit classification problem.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.01192](https://arxiv.org/abs/1712.01192)

##### PDF
[https://arxiv.org/pdf/1712.01192](https://arxiv.org/pdf/1712.01192)

