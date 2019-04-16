---
layout: post
title: "Online Illumination Invariant Moving Object Detection by Generative Neural Network"
date: 2018-08-03 02:11:32
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Optimization Detection Gradient_Descent
author: Fateme Bahri, Moein Shakeri, Nilanjan Ray
mathjax: true
---

* content
{:toc}

##### Abstract
Moving object detection (MOD) is a significant problem in computer vision that has many real world applications. Different categories of methods have been proposed to solve MOD. One of the challenges is to separate moving objects from illumination changes and shadows that are present in most real world videos. State-of-the-art methods that can handle illumination changes and shadows work in a batch mode; thus, these methods are not suitable for long video sequences or real-time applications. In this paper, we propose an extension of a state-of-the-art batch MOD method (ILISD) to an online/incremental MOD using unsupervised and generative neural networks, which use illumination invariant image representations. For each image in a sequence, we use a low-dimensional representation of a background image by a neural network and then based on the illumination invariant representation, decompose the foreground image into: illumination change and moving objects. Optimization is performed by stochastic gradient descent in an end-to-end and unsupervised fashion. Our algorithm can work in both batch and online modes. In the batch mode, like other batch methods, optimizer uses all the images. In online mode, images can be incrementally fed into the optimizer. Based on our experimental evaluation on benchmark image sequences, both the online and the batch modes of our algorithm achieve state-of-the-art accuracy on most data sets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1808.01066](https://arxiv.org/abs/1808.01066)

##### PDF
[https://arxiv.org/pdf/1808.01066](https://arxiv.org/pdf/1808.01066)

