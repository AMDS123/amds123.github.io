---
layout: post
title: "Semi-Supervised Learning for Face Sketch Synthesis in the Wild"
date: 2018-12-12 13:13:02
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning
author: Chaofeng Chen, Wei Liu, Xiao Tan, Kwan-Yee K. Wong
mathjax: true
---

* content
{:toc}

##### Abstract
Face sketch synthesis has made great progress in the past few years. Recent methods based on deep neural networks are able to generate high quality sketches from face photos. However, due to the lack of training data (photo-sketch pairs), none of such deep learning based methods can be applied successfully to face photos in the wild. In this paper, we propose a semi-supervised deep learning architecture which extends face sketch synthesis to handle face photos in the wild by exploiting additional face photos in training. Instead of supervising the network with ground truth sketches, we first perform patch matching in feature space between the input photo and photos in a small reference set of photo-sketch pairs. We then compose a pseudo sketch feature representation using the corresponding sketch feature patches to supervise our network. With the proposed approach, we can train our networks using a small reference set of photo-sketch pairs together with a large face photo dataset without ground truth sketches. Experiments show that our method achieve state-of-the-art performance both on public benchmarks and face photos in the wild. Codes are available at https://github.com/chaofengc/Face-Sketch-Wild.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.04929](http://arxiv.org/abs/1812.04929)

##### PDF
[http://arxiv.org/pdf/1812.04929](http://arxiv.org/pdf/1812.04929)

