---
layout: post
title: "Attention routing between capsules"
date: 2019-07-03 06:01:16
categories: arXiv_CV
tags: arXiv_CV Attention Classification Prediction
author: Jaewoong Choi, Hyun Seo, Suee Im, Myungju Kang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a new capsule network architecture called Attention Routing CapsuleNet (AR CapsNet). We replace the dynamic routing and squash activation function of the capsule network with dynamic routing (CapsuleNet) with the attention routing and capsule activation. The attention routing is a routing between capsules through an attention module. The attention routing is a fast forward-pass while keeping spatial information. On the other hand, the intuitive interpretation of the dynamic routing is finding a centroid of the prediction capsules. Thus, the squash activation function and its variant focus on preserving a vector orientation. However, the capsule activation focuses on performing a capsule-scale activation function. 
 We evaluate our proposed model on the MNIST, affNIST, and CIFAR-10 classification tasks. The proposed model achieves higher accuracy with fewer parameters (x0.41 parameters in the MNIST, x0.45 parameters in the CIFAR-10) and less training time than CapsuleNet (x0.40 training time in the MNIST, x0.30 training time in the CIFAR-10). These results validate that designing a capsule-scale operation is a key factor to implement the capsule concept. 
 Also, our experiment shows that our proposed model is transformation equivariant as CapsuleNet. As we perturb each element of the output capsule, the decoder attached to the output capsules shows global variations. Further experiments show that the difference in the capsule features caused by applying affine transformations on an input image is significantly aligned in one direction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01750](http://arxiv.org/abs/1907.01750)

##### PDF
[http://arxiv.org/pdf/1907.01750](http://arxiv.org/pdf/1907.01750)

