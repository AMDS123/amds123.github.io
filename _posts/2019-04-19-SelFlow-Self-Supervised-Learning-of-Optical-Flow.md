---
layout: post
title: "SelFlow: Self-Supervised Learning of Optical Flow"
date: 2019-04-19 08:21:16
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Pengpeng Liu, Michael Lyu, Irwin King, Jia Xu
mathjax: true
---

* content
{:toc}

##### Abstract
We present a self-supervised learning approach for optical flow. Our method distills reliable flow estimations from non-occluded pixels, and uses these predictions as ground truth to learn optical flow for hallucinated occlusions. We further design a simple CNN to utilize temporal information from multiple frames for better flow estimation. These two principles lead to an approach that yields the best performance for unsupervised optical flow learning on the challenging benchmarks including MPI Sintel, KITTI 2012 and 2015. More notably, our self-supervised pre-trained model provides an excellent initialization for supervised fine-tuning. Our fine-tuned models achieve state-of-the-art results on all three datasets. At the time of writing, we achieve EPE=4.26 on the Sintel benchmark, outperforming all submitted methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09117](http://arxiv.org/abs/1904.09117)

##### PDF
[http://arxiv.org/pdf/1904.09117](http://arxiv.org/pdf/1904.09117)

