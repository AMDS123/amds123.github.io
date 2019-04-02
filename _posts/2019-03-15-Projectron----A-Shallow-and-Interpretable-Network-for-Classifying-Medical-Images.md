---
layout: post
title: "Projectron -- A Shallow and Interpretable Network for Classifying Medical Images"
date: 2019-03-15 12:13:23
categories: arXiv_CV
tags: arXiv_CV Classification
author: Aditya Sriram, Shivam Kalra, H.R. Tizhoosh
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces the `Projectron' as a new neural network architecture that uses Radon projections to both classify and represent medical images. The motivation is to build shallow networks which are more interpretable in the medical imaging domain. Radon transform is an established technique that can reconstruct images from parallel projections. The Projectron first applies global Radon transform to each image using equidistant angles and then feeds these transformations for encoding to a single layer of neurons followed by a layer of suitable kernels to facilitate a linear separation of projections. Finally, the Projectron provides the output of the encoding as an input to two more layers for final classification. We validate the Projectron on five publicly available datasets, a general dataset (namely MNIST) and four medical datasets (namely Emphysema, IDC, IRMA, and Pneumonia). The results are encouraging as we compared the Projectron's performance against MLPs with raw images and Radon projections as inputs, respectively. Experiments clearly demonstrate the potential of the proposed Projectron for representing/classifying medical images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00740](http://arxiv.org/abs/1904.00740)

##### PDF
[http://arxiv.org/pdf/1904.00740](http://arxiv.org/pdf/1904.00740)

