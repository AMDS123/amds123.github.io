---
layout: post
title: "Deep Faster Detection of Faint Edges in Noisy Images"
date: 2019-01-07 06:12:52
categories: arXiv_CV
tags: arXiv_CV Detection
author: Nati Ofir, Yosi Keller
mathjax: true
---

* content
{:toc}

##### Abstract
Detection of faint edges in noisy images is a challenging problem studied in the last decades. \cite{ofir2016fast} introduced a fast method to detect faint edges in the highest accuracy among all the existing approaches. Their complexity is nearly linear in the image's pixels and their runtime is seconds for a noisy image. Their approach utilizes a multi-scale binary partitioning of the image. By utilizing the multi-scale U-net architecture \cite{unet}, we show in this paper that their method can be dramatically improved in both aspects of run time and accuracy. By training the network on a dataset of binary images, we developed an approach for faint edge detection that works in a linear complexity. Our runtime of a noisy image in milliseconds on a GPU. Even though our method is orders of magnitude faster, we still achieve higher accuracy of detection under many challenging scenarios. In addition, we show that our approach to performing multi-scale preprocessing of noisy images using U-net improves the ability to perform other vision tasks under the presence of noise. We prove this point by the resnet 20 \cite{resnet} classifier and the CIFAR 10 \cite{cifar} dataset.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1803.09420](http://arxiv.org/abs/1803.09420)

##### PDF
[http://arxiv.org/pdf/1803.09420](http://arxiv.org/pdf/1803.09420)

