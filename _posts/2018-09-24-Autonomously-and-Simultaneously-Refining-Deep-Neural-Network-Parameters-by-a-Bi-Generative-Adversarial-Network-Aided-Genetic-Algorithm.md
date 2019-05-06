---
layout: post
title: "Autonomously and Simultaneously Refining Deep Neural Network Parameters by a Bi-Generative Adversarial Network Aided Genetic Algorithm"
date: 2018-09-24 15:43:17
categories: arXiv_CV
tags: arXiv_CV Adversarial GAN CNN
author: Yantao Lu, Burak Kakillioglu, Senem Velipasalar
mathjax: true
---

* content
{:toc}

##### Abstract
The choice of parameters, and the design of the network architecture are important factors affecting the performance of deep neural networks. Genetic Algorithms (GA) have been used before to determine parameters of a network. Yet, GAs perform a finite search over a discrete set of pre-defined candidates, and cannot, in general, generate unseen configurations. In this paper, to move from exploration to exploitation, we propose a novel and systematic method that autonomously and simultaneously optimizes multiple parameters of any deep neural network by using a GA aided by a bi-generative adversarial network (Bi-GAN). The proposed Bi-GAN allows the autonomous exploitation and choice of the number of neurons, for fully-connected layers, and number of filters, for convolutional layers, from a large range of values. Our proposed Bi-GAN involves two generators, and two different models compete and improve each other progressively with a GAN-based strategy to optimize the networks during GA evolution. Our proposed approach can be used to autonomously refine the number of convolutional layers and dense layers, number and size of kernels, and the number of neurons for the dense layers; choose the type of the activation function; and decide whether to use dropout and batch normalization or not, to improve the accuracy of different deep neural network architectures. Without loss of generality, the proposed method has been tested with the ModelNet database, and compared with the 3D Shapenets and two GA-only methods. The results show that the presented approach can simultaneously and successfully optimize multiple neural network parameters, and achieve higher accuracy even with shallower networks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.10244](https://arxiv.org/abs/1809.10244)

##### PDF
[https://arxiv.org/pdf/1809.10244](https://arxiv.org/pdf/1809.10244)

