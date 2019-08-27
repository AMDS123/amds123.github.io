---
layout: post
title: "Local Unsupervised Learning for Image Analysis"
date: 2019-08-14 17:42:11
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Leopold Grinberg, John Hopfield, Dmitry Krotov
mathjax: true
---

* content
{:toc}

##### Abstract
Local Hebbian learning is believed to be inferior in performance to end-to-end training using a backpropagation algorithm. We question this popular belief by designing a local algorithm that can learn convolutional filters at scale on large image datasets. These filters combined with patch normalization and very steep non-linearities result in a good classification accuracy for shallow networks trained locally, as opposed to end-to-end. The filters learned by our algorithm contain both orientation selective units and unoriented color units, resembling the responses of pyramidal neurons located in the cytochrome oxidase 'interblob' and 'blob' regions in the primary visual cortex of primates. It is shown that convolutional networks with patch normalization significantly outperform standard convolutional networks on the task of recovering the original classes when shadows are superimposed on top of standard CIFAR-10 images. Patch normalization approximates the retinal adaptation to the mean light intensity, important for human vision. We also demonstrate a successful transfer of learned representations between CIFAR-10 and ImageNet 32x32 datasets. All these results taken together hint at the possibility that local unsupervised training might be a powerful tool for learning general representations (without specifying the task) directly from unlabeled data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.08993](http://arxiv.org/abs/1908.08993)

##### PDF
[http://arxiv.org/pdf/1908.08993](http://arxiv.org/pdf/1908.08993)

