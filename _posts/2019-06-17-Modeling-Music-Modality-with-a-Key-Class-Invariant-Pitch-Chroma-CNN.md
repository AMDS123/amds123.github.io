---
layout: post
title: "Modeling Music Modality with a Key-Class Invariant Pitch Chroma CNN"
date: 2019-06-17 17:33:07
categories: arXiv_SD
tags: arXiv_SD CNN Prediction
author: Anders Elowsson, Anders Friberg
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a convolutional neural network (CNN) that uses input from a polyphonic pitch estimation system to predict perceived minor/major modality in music audio. The pitch activation input is structured to allow the first CNN layer to compute two pitch chromas focused on different octaves. The following layers perform harmony analysis across chroma and time scales. Through max pooling across pitch, the CNN becomes invariant with regards to the key class (i.e., key disregarding mode) of the music. A multilayer perceptron combines the modality activation output with spectral features for the final prediction. The study uses a dataset of 203 excerpts rated by around 20 listeners each, a small challenging data size requiring a carefully designed parameter sharing. With an R2 of about 0.71, the system clearly outperforms previous systems as well as individual human listeners. A final ablation study highlights the importance of using pitch activations processed across longer time scales, and using pooling to facilitate invariance with regards to the key class.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07145](http://arxiv.org/abs/1906.07145)

##### PDF
[http://arxiv.org/pdf/1906.07145](http://arxiv.org/pdf/1906.07145)

