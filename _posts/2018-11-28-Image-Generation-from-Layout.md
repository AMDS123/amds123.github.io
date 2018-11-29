---
layout: post
title: "Image Generation from Layout"
date: 2018-11-28 05:11:14
categories: arXiv_CV
tags: arXiv_CV Embedding CNN RNN
author: Bo Zhao, Lili Meng, Weidong Yin, Leonid Sigal
mathjax: true
---

* content
{:toc}

##### Abstract
Despite significant recent progress on generative models, controlled generation of images depicting multiple and complex object layouts is still a difficult problem. Among the core challenges are the diversity of appearance a given object may possess and, as a result, exponential set of images consistent with a specified layout. To address these challenges, we propose a novel approach for layout-based image generation; we call it Layout2Im. Given the coarse spatial layout (bounding boxes + object categories), our model can generate a set of realistic images which have the correct objects in the desired locations. The representation of each object is disentangled into a specified/certain part (category) and an unspecified/uncertain part (appearance). The category is encoded using a word embedding and the appearance is distilled into a low-dimensional vector sampled from a normal distribution. Individual object representations are composed together using convolutional LSTM, to obtain an encoding of the complete layout, and then decoded to an image. Several loss terms are introduced to encourage accurate and diverse generation. The proposed Layout2Im model significantly outperforms the previous state of the art, boosting the best reported inception score by 24.66% and 28.57% on the very challenging COCO-Stuff and Visual Genome datasets, respectively. Extensive experiments also demonstrate our method's ability to generate complex and diverse images with multiple objects.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.11389](http://arxiv.org/abs/1811.11389)

##### PDF
[http://arxiv.org/pdf/1811.11389](http://arxiv.org/pdf/1811.11389)

