---
layout: post
title: "Hydra: an Ensemble of Convolutional Neural Networks for Geospatial Land Classification"
date: 2019-03-20 18:03:28
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Classification
author: Rodrigo Minetto, Mauricio Pamplona Segundo, Sudeep Sarkar
mathjax: true
---

* content
{:toc}

##### Abstract
We describe in this paper Hydra, an ensemble of convolutional neural networks (CNN) for geospatial land classification. The idea behind Hydra is to create an initial CNN that is coarsely optimized but provides a good starting pointing for further optimization, which will serve as the Hydra's body. Then, the obtained weights are fine-tuned multiple times with different augmentation techniques, crop styles, and classes weights to form an ensemble of CNNs that represent the Hydra's heads. By doing so, we prompt convergence to different endpoints, which is a desirable aspect for ensembles. With this framework, we were able to reduce the training time while maintaining the classification performance of the ensemble. We created ensembles for our experiments using two state-of-the-art CNN architectures, ResNet and DenseNet. We have demonstrated the application of our Hydra framework in two datasets, FMOW and NWPU-RESISC45, achieving results comparable to the state-of-the-art for the former and the best reported performance so far for the latter. Code and CNN models are available at https://github.com/maups/hydra-fmow

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1802.03518](http://arxiv.org/abs/1802.03518)

##### PDF
[http://arxiv.org/pdf/1802.03518](http://arxiv.org/pdf/1802.03518)

