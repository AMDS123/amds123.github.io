---
layout: post
title: "Multi-Stage Prediction Networks for Data Harmonization"
date: 2019-07-26 15:29:46
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Stefano B. Blumberg, Marco Palombo, Can Son Khoo, Chantal M. W. Tax, Ryutaro Tanno, Daniel C. Alexander
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we introduce multi-task learning (MTL) to data harmonization (DH); where we aim to harmonize images across different acquisition platforms and sites. This allows us to integrate information from multiple acquisitions and improve the predictive performance and learning efficiency of the harmonization model. Specifically, we introduce the Multi Stage Prediction (MSP) Network, a MTL framework that incorporates neural networks of potentially disparate architectures, trained for different individual acquisition platforms, into a larger architecture that is refined in unison. The MSP utilizes high-level features of single networks for individual tasks, as inputs of additional neural networks to inform the final prediction, therefore exploiting redundancy across tasks to make the most of limited training data. We validate our methods on a dMRI harmonization challenge dataset, where we predict three modern platform types, from one obtained from an old scanner. We show how MTL architectures, such as the MSP, produce around 20\% improvement of patch-based mean-squared error over current state-of-the-art methods and that our MSP outperforms off-the-shelf MTL networks. Our code is available https://github.com/sbb-gh/ .

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.11629](http://arxiv.org/abs/1907.11629)

##### PDF
[http://arxiv.org/pdf/1907.11629](http://arxiv.org/pdf/1907.11629)

