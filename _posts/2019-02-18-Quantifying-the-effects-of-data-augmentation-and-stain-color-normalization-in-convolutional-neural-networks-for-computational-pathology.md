---
layout: post
title: "Quantifying the effects of data augmentation and stain color normalization in convolutional neural networks for computational pathology"
date: 2019-02-18 12:36:58
categories: arXiv_CV
tags: arXiv_CV GAN CNN Classification
author: David Tellez, Geert Litjens, Peter Bandi, Wouter Bulten, John-Melle Bokhorst, Francesco Ciompi, Jeroen van der Laak
mathjax: true
---

* content
{:toc}

##### Abstract
Stain variation is a phenomenon observed when distinct pathology laboratories stain tissue slides that exhibit similar but not identical color appearance. Due to this color shift between laboratories, convolutional neural networks (CNNs) trained with images from one lab often underperform on unseen images from the other lab. Several techniques have been proposed to reduce the generalization error, mainly grouped into two categories: stain color augmentation and stain color normalization. The former simulates a wide variety of realistic stain variations during training, producing stain-invariant CNNs. The latter aims to match training and test color distributions in order to reduce stain variation. For the first time, we compared some of these techniques and quantified their effect on CNN classification performance using a heterogeneous dataset of hematoxylin and eosin histopathology images from 4 organs and 9 pathology laboratories. Additionally, we propose a novel unsupervised method to perform stain color normalization using a neural network. Based on our experimental results, we provide practical guidelines on how to use stain color augmentation and stain color normalization in future computational pathology applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.06543](http://arxiv.org/abs/1902.06543)

##### PDF
[http://arxiv.org/pdf/1902.06543](http://arxiv.org/pdf/1902.06543)

