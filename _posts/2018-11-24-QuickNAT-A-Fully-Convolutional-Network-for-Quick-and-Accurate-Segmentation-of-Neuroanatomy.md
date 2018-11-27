---
layout: post
title: "QuickNAT: A Fully Convolutional Network for Quick and Accurate Segmentation of Neuroanatomy"
date: 2018-11-24 09:12:31
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Abhijit Guha Roy, Sailesh Conjeti, Nassir Navab, Christian Wachinger
mathjax: true
---

* content
{:toc}

##### Abstract
Whole brain segmentation from structural magnetic resonance imaging (MRI) is a prerequisite for most morphological analyses, but is computationally intense and can therefore delay the availability of image markers after scan acquisition. We introduce QuickNAT, a fully convolutional, densely connected neural network that segments a \revision{MRI brain scan} in 20 seconds. To enable training of the complex network with millions of learnable parameters using limited annotated data, we propose to first pre-train on auxiliary labels created from existing segmentation software. Subsequently, the pre-trained model is fine-tuned on manual labels to rectify errors in auxiliary labels. With this learning strategy, we are able to use large neuroimaging repositories without manual annotations for training. In an extensive set of evaluations on eight datasets that cover a wide age range, pathology, and different scanners, we demonstrate that QuickNAT achieves superior segmentation accuracy and reliability in comparison to state-of-the-art methods, while being orders of magnitude faster. The speed up facilitates processing of large data repositories and supports translation of imaging biomarkers by making them available within seconds for fast clinical decision making.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1801.04161](http://arxiv.org/abs/1801.04161)

##### PDF
[http://arxiv.org/pdf/1801.04161](http://arxiv.org/pdf/1801.04161)

