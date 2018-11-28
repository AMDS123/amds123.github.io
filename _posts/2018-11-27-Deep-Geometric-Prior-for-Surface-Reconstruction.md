---
layout: post
title: "Deep Geometric Prior for Surface Reconstruction"
date: 2018-11-27 12:50:46
categories: arXiv_CV
tags: arXiv_CV Regularization GAN Face
author: Francis Williams, Teseo Schneider, Claudio Silva, Denis Zorin, Joan Bruna, Daniele Panozzo
mathjax: true
---

* content
{:toc}

##### Abstract
The reconstruction of a discrete surface from a point cloud is a fundamental geometry processing problem that has been studied for decades, with many methods developed. We propose the use of a deep neural network as a geometric prior for surface reconstruction. Specifically, we overfit a neural network representing a local chart parameterization to part of an input point cloud using the Wasserstein distance as a measure of approximation. By jointly fitting many such networks to overlapping parts of the point cloud, while enforcing a consistency condition, we compute a manifold atlas. By sampling this atlas, we can produce a dense reconstruction of the surface approximating the input cloud. The entire procedure does not require any training data or explicit regularization, yet, we show that it is able to perform remarkably well: not introducing typical overfitting artifacts, and approximating sharp features closely at the same time. We experimentally show that this geometric prior produces good results for both man-made objects containing sharp features and smoother organic objects, as well as noisy inputs. We compare our method with a number of well-known reconstruction methods on a standard surface reconstruction benchmark.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10943](http://arxiv.org/abs/1811.10943)

##### PDF
[http://arxiv.org/pdf/1811.10943](http://arxiv.org/pdf/1811.10943)

