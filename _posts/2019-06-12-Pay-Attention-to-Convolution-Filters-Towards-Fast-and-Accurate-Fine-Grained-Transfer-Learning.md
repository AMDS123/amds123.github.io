---
layout: post
title: "Pay Attention to Convolution Filters: Towards Fast and Accurate Fine-Grained Transfer Learning"
date: 2019-06-12 05:38:24
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN Image_Classification Transfer_Learning Classification
author: Xiangxi Mo, Ruizhe Cheng, Tianyi Fang
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an efficient transfer learning method for adapting ImageNet pre-trained Convolutional Neural Network (CNN) to fine-grained image classification task. Conventional transfer learning methods typically face the trade-off between training time and accuracy. By adding "attention module" to each convolutional filters of the pre-trained network, we are able to rank and adjust the importance of each convolutional signal in an end-to-end pipeline. In this report, we show our method can adapt a pre-trianed ResNet50 for a fine-grained transfer learning task within few epochs and achieve accuracy above conventional transfer learning methods and close to models trained from scratch. Our model also offer interpretable result because the rank of the convolutional signal shows which convolution channels are utilized and amplified to achieve better classification result, as well as which signal should be treated as noise for the specific transfer learning task, which could be pruned to lower model size.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04950](http://arxiv.org/abs/1906.04950)

##### PDF
[http://arxiv.org/pdf/1906.04950](http://arxiv.org/pdf/1906.04950)

