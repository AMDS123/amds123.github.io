---
layout: post
title: "Higher-Order Function Networks for Learning Composable 3D Object Representations"
date: 2019-07-24 12:31:16
categories: arXiv_CV
tags: arXiv_CV
author: Eric Mitchell, Selim Engin, Volkan Isler, Daniel D Lee
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to represent 3D objects using higher order functions, where an object is encoded directly into the weights and biases of a small `mapping' network by a larger encoder network. This mapping network can be used to reconstruct 3D objects by applying its encoded transformation to points sampled from a simple canonical space. We first demonstrate that an encoder network can produce mappings that reconstruct objects from single images more accurately than state of the art point set reconstruction methods. Next, we show that our method yields meaningful gains for robot motion planning problems that use this object representation for collision avoidance. We also demonstrate that our formulation allows for a novel method of object interpolation in a latent function space, where we compose the roots of the reconstruction functions for various objects to generate new, coherent objects. Finally, we demonstrate the coding efficiency of our approach: encoding objects directly as a neural network is highly parameter efficient when compared with object representations that encode the object of interest as a latent vector `codeword'. Our smallest reconstruction network has only about 7000 parameters and shows reconstruction quality generally better than state-of-the-art codeword-based object representation architectures with millions of parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.10388](http://arxiv.org/abs/1907.10388)

##### PDF
[http://arxiv.org/pdf/1907.10388](http://arxiv.org/pdf/1907.10388)

