---
layout: post
title: "DeepOtsu: Document Enhancement and Binarization using Iterative Deep Learning"
date: 2019-01-18 04:23:51
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Sheng He, Lambert Schomaker
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel iterative deep learning framework and apply it for document enhancement and binarization. Unlike the traditional methods which predict the binary label of each pixel on the input image, we train the neural network to learn the degradations in document images and produce the uniform images of the degraded input images, which allows the network to refine the output iteratively. Two different iterative methods have been studied in this paper: recurrent refinement (RR) which uses the same trained neural network in each iteration for document enhancement and stacked refinement (SR) which uses a stack of different neural networks for iterative output refinement. Given the learned uniform and enhanced image, the binarization map can be easy to obtain by a global or local threshold. The experimental results on several public benchmark data sets show that our proposed methods provide a new clean version of the degraded image which is suitable for visualization and promising results of binarization using the global Otsu's threshold based on the enhanced images learned iteratively by the neural network.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06081](http://arxiv.org/abs/1901.06081)

##### PDF
[http://arxiv.org/pdf/1901.06081](http://arxiv.org/pdf/1901.06081)

