---
layout: post
title: "Areas of Attention for Image Captioning"
date: 2017-08-25 14:36:01
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Attention Caption CNN RNN Language_Model Detection
author: Marco Pedersoli, Thomas Lucas, Cordelia Schmid, Jakob Verbeek
mathjax: true
---

* content
{:toc}

##### Abstract
We propose "Areas of Attention", a novel attention-based model for automatic image captioning. Our approach models the dependencies between image regions, caption words, and the state of an RNN language model, using three pairwise interactions. In contrast to previous attention-based approaches that associate image regions only to the RNN state, our method allows a direct association between caption words and image regions. During training these associations are inferred from image-level captions, akin to weakly-supervised object detector training. These associations help to improve captioning by localizing the corresponding regions during testing. We also propose and compare different ways of generating attention areas: CNN activation grids, object proposals, and spatial transformers nets applied in a convolutional fashion. Spatial transformers give the best results. They allow for image specific attention areas, and can be trained jointly with the rest of the network. Our attention mechanism and spatial transformer attention areas together yield state-of-the-art results on the MSCOCO dataset.o meaningful latent semantic structure in the generated captions.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1612.01033](https://arxiv.org/abs/1612.01033)

##### PDF
[https://arxiv.org/pdf/1612.01033](https://arxiv.org/pdf/1612.01033)

