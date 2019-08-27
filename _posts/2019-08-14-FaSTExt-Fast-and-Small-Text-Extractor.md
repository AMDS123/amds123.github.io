---
layout: post
title: "FaSTExt: Fast and Small Text Extractor"
date: 2019-08-14 15:25:24
categories: arXiv_CV
tags: arXiv_CV CNN Detection Relation
author: Alexander Filonenko, Konstantin Gudkov, Aleksei Lebedev, Nikita Orlov, Ivan Zagaynov
mathjax: true
---

* content
{:toc}

##### Abstract
Text detection in natural images is a challenging but necessary task for many applications. Existing approaches utilize large deep convolutional neural networks making it difficult to use them in real-world tasks. We propose a small yet relatively precise text extraction method. The basic component of it is a convolutional neural network which works in a fully-convolutional manner and produces results at multiple scales. Each scale output predicts whether a pixel is a part of some word, its geometry, and its relation to neighbors at the same scale and between scales. The key factor of reducing the complexity of the model was the utilization of depthwise separable convolution, linear bottlenecks, and inverted residuals. Experiments on public datasets show that the proposed network can effectively detect text while keeping the number of parameters in the range of 1.58 to 10.59 million in different configurations.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08994](http://arxiv.org/abs/1908.08994)

##### PDF
[http://arxiv.org/pdf/1908.08994](http://arxiv.org/pdf/1908.08994)

