---
layout: post
title: "3DRegNet: A Deep Neural Network for 3D Point Registration"
date: 2019-04-02 22:59:46
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning
author: G. Dias Pais, Pedro Miraldo, Srikumar Ramalingam, Venu Madhav Govindu, Jacinto C. Nascimento, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
We present 3DRegNet, a deep learning algorithm for the registration of 3D scans. With the recent emergence of inexpensive 3D commodity sensors, it would be beneficial to develop a learning based 3D registration algorithm. Given a set of 3D point correspondences, we build a deep neural network using deep residual layers and convolutional layers to achieve two tasks: (1) classification of the point correspondences into correct/incorrect ones, and (2) regression of the motion parameters that can align the scans into a common reference frame. 3DRegNet has several advantages over classical methods. First, since 3DRegNet works on point correspondences and not on the original scans, our approach is significantly faster than many conventional approaches. Second, we show that the algorithm can be extended for multi-view scenarios, i.e., simultaneous handling of the registration for more than two scans. In contrast to pose regression networks that employ four variables to represent rotation using quaternions, we use Lie algebra to represent the rotation using only three variables. Extensive experiments on two challenging datasets (i.e. ICL-NUIM and SUN3D) demonstrate that we outperform other methods and achieve state-of-the-art results. The code will be made available.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.01701](https://arxiv.org/abs/1904.01701)

##### PDF
[https://arxiv.org/pdf/1904.01701](https://arxiv.org/pdf/1904.01701)

