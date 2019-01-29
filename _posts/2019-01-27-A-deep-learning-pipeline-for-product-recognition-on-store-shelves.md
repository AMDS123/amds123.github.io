---
layout: post
title: "A deep learning pipeline for product recognition on store shelves"
date: 2019-01-27 08:52:17
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Object_Detection Embedding Deep_Learning Detection Recognition
author: Alessio Tonioni, Eugenio Serra, Luigi Di Stefano
mathjax: true
---

* content
{:toc}

##### Abstract
Recognition of grocery products in store shelves poses peculiar challenges. Firstly, the task mandates the recognition of an extremely high number of different items, in the order of several thousands for medium-small shops, with many of them featuring small inter and intra class variability. Then, available product databases usually include just one or a few studio-quality images per product (referred to herein as reference images), whilst at test time recognition is performed on pictures displaying a portion of a shelf containing several products and taken in the store by cheap cameras (referred to as query images). Moreover, as the items on sale in a store as well as their appearance change frequently over time, a practical recognition system should handle seamlessly new products/packages. Inspired by recent advances in object detection and image retrieval, we propose to leverage on state of the art object detectors based on deep learning to obtain an initial productagnostic item detection. Then, we pursue product recognition through a similarity search between global descriptors computed on reference and cropped query images. To maximize performance, we learn an ad-hoc global descriptor by a CNN trained on reference images based on an image embedding loss. Our system is computationally expensive at training time but can perform recognition rapidly and accurately at test time.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.01733](http://arxiv.org/abs/1810.01733)

##### PDF
[http://arxiv.org/pdf/1810.01733](http://arxiv.org/pdf/1810.01733)

