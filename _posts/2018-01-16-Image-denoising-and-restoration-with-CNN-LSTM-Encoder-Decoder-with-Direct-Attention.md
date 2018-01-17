---
layout: post
title: "Image denoising and restoration with CNN-LSTM Encoder Decoder with Direct Attention"
date: 2018-01-16 07:27:46
categories: arXiv_CV
tags: arXiv_CV Attention CNN RNN
author: Kazi Nazmul Haque, Mohammad Abu Yousuf, Rajib Rana
mathjax: true
---

* content
{:toc}

##### Abstract
Image denoising is always a challenging task in the field of computer vision and image processing. In this paper, we have proposed an encoder-decoder model with direct attention, which is capable of denoising and reconstruct highly corrupted images. Our model consists of an encoder and a decoder, where the encoder is a convolutional neural network and decoder is a multilayer Long Short-Term memory network. In the proposed model, the encoder reads an image and catches the abstraction of that image in a vector, where decoder takes that vector as well as the corrupted image to reconstruct a clean image. We have trained our model on MNIST handwritten digit database after making lower half of every image as black as well as adding noise top of that. After a massive destruction of the images where it is hard for a human to understand the content of those images, our model can retrieve that image with minimal error. Our proposed model has been compared with convolutional encoder-decoder, where our model has performed better at generating missing part of the images than convolutional autoencoder.

##### Abstract (translated by Google)
图像去噪在计算机视觉和图像处理领域一直是一个具有挑战性的任务。在本文中，我们提出了一个直接关注的编码器 - 解码器模型，它能够去噪和重构高度损坏的图像。我们的模型由一个编码器和一个解码器组成，编码器是一个卷积神经网络，解码器是一个多层的长期短期记忆网络。在所提出的模型中，编码器读取图像并捕获矢量中该图像的抽象，其中解码器将该矢量以及损坏的图像重构为干净的图像。我们已经在MNIST手写数字数据库上训练了我们的模型，使每个图像的下半部分为黑色，并且增加了噪声顶部。在人们难以理解这些图像的内容的图像的大量破坏之后，我们的模型可以以最小的错误检索该图像。我们提出的模型已经与卷积编码器 - 解码器比较，其中我们的模型比卷积自动编码器在生成图像的缺失部分方面表现更好。

##### URL
[http://arxiv.org/abs/1801.05141](http://arxiv.org/abs/1801.05141)

##### PDF
[http://arxiv.org/pdf/1801.05141](http://arxiv.org/pdf/1801.05141)

