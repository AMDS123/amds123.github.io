---
layout: post
title: "Processsing Simple Geometric Attributes with Autoencoders"
date: 2019-04-15 15:01:27
categories: arXiv_AI
tags: arXiv_AI Adversarial GAN Face Deep_Learning
author: Alasdair Newson, Andr&#xe9;s Almansa, Yann Gousseau, Sa&#xef;d Ladjal
mathjax: true
---

* content
{:toc}

##### Abstract
Image synthesis is a core problem in modern deep learning, and many recent architectures such as autoencoders and Generative Adversarial networks produce spectacular results on highly complex data, such as images of faces or landscapes. While these results open up a wide range of new, advanced synthesis applications, there is also a severe lack of theoretical understanding of how these networks work. This results in a wide range of practical problems, such as difficulties in training, the tendency to sample images with little or no variability, and generalisation problems. In this paper, we propose to analyse the ability of the simplest generative network, the autoencoder, to encode and decode two simple geometric attributes : size and position. We believe that, in order to understand more complicated tasks, it is necessary to first understand how these networks process simple attributes. For the first property, we analyse the case of images of centred disks with variable radii. We explain how the autoencoder projects these images to and from a latent space of smallest possible dimension, a scalar. In particular, we describe a closed-form solution to the decoding training problem in a network without biases, and show that during training, the network indeed finds this solution. We then investigate the best regularisation approaches which yield networks that generalise well. For the second property, position, we look at the encoding and decoding of Dirac delta functions, also known as `one-hot' vectors. We describe a hand-crafted filter that achieves encoding perfectly, and show that the network naturally finds this filter during training. We also show experimentally that the decoding can be achieved if the dataset is sampled in an appropriate manner.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.07099](http://arxiv.org/abs/1904.07099)

##### PDF
[http://arxiv.org/pdf/1904.07099](http://arxiv.org/pdf/1904.07099)

