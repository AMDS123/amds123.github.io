---
layout: post
title: "Non-Local Video Denoising by CNN"
date: 2018-11-30 12:24:27
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Axel Davy, Thibaud Ehret, Gabriele Facciolo, Jean-Michel Morel, Pablo Arias
mathjax: true
---

* content
{:toc}

##### Abstract
Non-local patch based methods were until recently state-of-the-art for image denoising but are now outperformed by CNNs. Yet they are still the best ones for video denoising, as video redundancy is a key factor to attain high denoising performance. The problem is that CNN architectures are hardly compatible with the search for self-similarities. In this work we propose a new and efficient way to feed video self-similarities to a CNN. The non-locality is incorporated into the network via a first non-trainable layer which finds for each patch in the input image its most similar patches in a search region. The central values of these patches are then gathered in a feature vector which is assigned to each image pixel. This information is presented to a CNN which is trained to predict the clean image. We apply the proposed architecture to image and video denoising. For the latter patches are searched for in a 3D spatio-temporal volume. The proposed architecture achieves state-of-the-art results, specially in video denoising, where it outperforms most state-of-the-art methods. To the best of our knowledge, this is the first successful application of a CNN to video denoising.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12758](http://arxiv.org/abs/1811.12758)

##### PDF
[http://arxiv.org/pdf/1811.12758](http://arxiv.org/pdf/1811.12758)

