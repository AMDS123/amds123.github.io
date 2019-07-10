---
layout: post
title: "Fully Convolutional Network for Removing DCT Artefacts From Images"
date: 2019-07-08 18:31:11
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN Deep_Learning
author: Patryk Najgebauer, Rafal Scherer
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning methods achieve excellent results in image transformations as well as image noise reduction or super-resolution methods. Based on these solutions, we present a deep-learning method of block reconstruction of images compressed with the JPEG format. Images compressed with the discrete cosine transform (DCT) contain visible artefacts in the form of blocks, which in some cases spoil the aesthetics of the image mostly on the edges of the contrasting elements. This is unavoidable, and the discernibility of the block artefacts can be adjusted by the degree of image compression, which profoundly affects the output image size. We use a fully convolutional network which operates directly on 8x8-pixel blocks in the same way as the JPEG encoder. Thanks to that, we do not modify the input image; we only divide it into separately processed blocks. The purpose of our neural model is to modify the pixels in the blocks to reduce artefact visibility %against the background of the neighbouring image and to recreate the original pattern of the image distorted by the DCT transform. We trained our model on a dataset created from vector images transformed to the JPEG and PNG formats, as the input and output data, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.03798](http://arxiv.org/abs/1907.03798)

##### PDF
[http://arxiv.org/pdf/1907.03798](http://arxiv.org/pdf/1907.03798)

