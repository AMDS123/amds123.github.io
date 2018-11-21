---
layout: post
title: "Multi-layer Pruning Framework for Compressing Single Shot MultiBox Detector"
date: 2018-11-20 16:19:44
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Classification Detection Recognition
author: Pravendra Singh, Manikandan R, Neeraj Matiyali, Vinay P. Namboodiri
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a framework for compressing state-of-the-art Single Shot MultiBox Detector (SSD). The framework addresses compression in the following stages: Sparsity Induction, Filter Selection, and Filter Pruning. In the Sparsity Induction stage, the object detector model is sparsified via an improved global threshold. In Filter Selection &amp; Pruning stage, we select and remove filters using sparsity statistics of filter weights in two consecutive convolutional layers. This results in the model with the size smaller than most existing compact architectures. We evaluate the performance of our framework with multiple datasets and compare over multiple methods. Experimental results show that our method achieves state-of-the-art compression of 6.7X and 4.9X on PASCAL VOC dataset on models SSD300 and SSD512 respectively. We further show that the method produces maximum compression of 26X with SSD512 on German Traffic Sign Detection Benchmark (GTSDB). Additionally, we also empirically show our method's adaptability for classification based architecture VGG16 on datasets CIFAR and German Traffic Sign Recognition Benchmark (GTSRB) achieving a compression rate of 125X and 200X with the reduction in flops by 90.50% and 96.6% respectively with no loss of accuracy. In addition to this, our method does not require any special libraries or hardware support for the resulting compressed models.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.08342](http://arxiv.org/abs/1811.08342)

##### PDF
[http://arxiv.org/pdf/1811.08342](http://arxiv.org/pdf/1811.08342)

