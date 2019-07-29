---
layout: post
title: "DeepCMB: Lensing Reconstruction of the Cosmic Microwave Background with Deep Neural Networks"
date: 2019-07-26 14:56:24
categories: arXiv_CV
tags: arXiv_CV CNN
author: J. Caldeira, W. L. K. Wu, B. Nord, C. Avestruz, S. Trivedi, K. T. Story
mathjax: true
---

* content
{:toc}

##### Abstract
Next-generation cosmic microwave background (CMB) experiments will have lower noise and therefore increased sensitivity, enabling improved constraints on fundamental physics parameters such as the sum of neutrino masses and the tensor-to-scalar ratio r. Achieving competitive constraints on these parameters requires high signal-to-noise extraction of the projected gravitational potential from the CMB maps. Standard methods for reconstructing the lensing potential employ the quadratic estimator (QE). However, the QE performs suboptimally at the low noise levels expected in upcoming experiments. Other methods, like maximum likelihood estimators (MLE), are under active development. In this work, we demonstrate reconstruction of the CMB lensing potential with deep convolutional neural networks (CNN) - ie, a ResUNet. The network is trained and tested on simulated data, and otherwise has no physical parametrization related to the physical processes of the CMB and gravitational lensing. We show that, over a wide range of angular scales, ResUNets recover the input gravitational potential with a higher signal-to-noise ratio than the QE method, reaching levels comparable to analytic approximations of MLE methods. We demonstrate that the network outputs quantifiably different lensing maps when given input CMB maps generated with different cosmologies. We also show we can use the reconstructed lensing map for cosmological parameter estimation. This application of CNN provides a few innovations at the intersection of cosmology and machine learning. First, while training and regressing on images, we predict a continuous-variable field rather than discrete classes. Second, we are able to establish uncertainty measures for the network output that are analogous to standard methods. We expect this approach to excel in capturing hard-to-model non-Gaussian astrophysical foreground and noise contributions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.01483](http://arxiv.org/abs/1810.01483)

##### PDF
[http://arxiv.org/pdf/1810.01483](http://arxiv.org/pdf/1810.01483)

