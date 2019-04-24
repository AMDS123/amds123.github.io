---
layout: post
title: "Multiview Hessian Regularization for Image Annotation"
date: 2019-04-23 00:08:43
categories: arXiv_CV
tags: arXiv_CV Regularization Attention Classification
author: Weifeng Liu, Dacheng Tao
mathjax: true
---

* content
{:toc}

##### Abstract
The rapid development of computer hardware and Internet technology makes large scale data dependent models computationally tractable, and opens a bright avenue for annotating images through innovative machine learning algorithms. Semi-supervised learning (SSL) has consequently received intensive attention in recent years and has been successfully deployed in image annotation. One representative work in SSL is Laplacian regularization (LR), which smoothes the conditional distribution for classification along the manifold encoded in the graph Laplacian, however, it has been observed that LR biases the classification function towards a constant function which possibly results in poor generalization. In addition, LR is developed to handle uniformly distributed data (or single view data), although instances or objects, such as images and videos, are usually represented by multiview features, such as color, shape and texture. In this paper, we present multiview Hessian regularization (mHR) to address the above two problems in LR-based image annotation. In particular, mHR optimally combines multiple Hessian regularizations, each of which is obtained from a particular view of instances, and steers the classification function which varies linearly along the data manifold. We apply mHR to kernel least squares and support vector machines as two examples for image annotation. Extensive experiments on the PASCAL VOC'07 dataset validate the effectiveness of mHR by comparing it with baseline algorithms, including LR and HR.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10100](http://arxiv.org/abs/1904.10100)

##### PDF
[http://arxiv.org/pdf/1904.10100](http://arxiv.org/pdf/1904.10100)

