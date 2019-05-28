---
layout: post
title: "Cross-Resolution Face Recognition via Prior-Aided Face Hallucination and Residual Knowledge Distillation"
date: 2019-05-26 10:08:17
categories: arXiv_CV
tags: arXiv_CV Adversarial Knowledge GAN Face CNN Deep_Learning Quantitative Recognition Face_Recognition
author: Hanyang Kong, Jian Zhao, Xiaoguang Tu, Junliang Xing, Shengmei Shen, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Recent deep learning based face recognition methods have achieved great performance, but it still remains challenging to recognize very low-resolution query face like 28x28 pixels when CCTV camera is far from the captured subject. Such face with very low-resolution is totally out of detail information of the face identity compared to normal resolution in a gallery and hard to find corresponding faces therein. To this end, we propose a Resolution Invariant Model (RIM) for addressing such cross-resolution face recognition problems, with three distinct novelties. First, RIM is a novel and unified deep architecture, containing a Face Hallucination sub-Net (FHN) and a Heterogeneous Recognition sub-Net (HRN), which are jointly learned end to end. Second, FHN is a well-designed tri-path Generative Adversarial Network (GAN) which simultaneously perceives facial structure and geometry prior information, i.e. landmark heatmaps and parsing maps, incorporated with an unsupervised cross-domain adversarial training strategy to super-resolve very low-resolution query image to its 8x larger ones without requiring them to be well aligned. Third, HRN is a generic Convolutional Neural Network (CNN) for heterogeneous face recognition with our proposed residual knowledge distillation strategy for learning discriminative yet generalized feature representation. Quantitative and qualitative experiments on several benchmarks demonstrate the superiority of the proposed model over the state-of-the-arts. Codes and models will be released upon acceptance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10777](http://arxiv.org/abs/1905.10777)

##### PDF
[http://arxiv.org/pdf/1905.10777](http://arxiv.org/pdf/1905.10777)

