---
layout: post
title: "Beyond Product Quantization: Deep Progressive Quantization for Image Retrieval"
date: 2019-06-16 14:23:01
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN
author: Lianli Gao, Xiaosu Zhu, Jingkuan Song, Zhou Zhao, Heng Tao Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Product Quantization (PQ) has long been a mainstream for generating an exponentially large codebook at very low memory/time cost. Despite its success, PQ is still tricky for the decomposition of high-dimensional vector space, and the retraining of model is usually unavoidable when the code length changes. In this work, we propose a deep progressive quantization (DPQ) model, as an alternative to PQ, for large scale image retrieval. DPQ learns the quantization codes sequentially and approximates the original feature space progressively. Therefore, we can train the quantization codes with different code lengths simultaneously. Specifically, we first utilize the label information for guiding the learning of visual features, and then apply several quantization blocks to progressively approach the visual features. Each quantization block is designed to be a layer of a convolutional neural network, and the whole framework can be trained in an end-to-end manner. Experimental results on the benchmark datasets show that our model significantly outperforms the state-of-the-art for image retrieval. Our model is trained once for different code lengths and therefore requires less computation time. Additional ablation study demonstrates the effect of each component of our proposed model. Our code is released at https://github.com/cfm-uestc/DPQ.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06698](http://arxiv.org/abs/1906.06698)

##### PDF
[http://arxiv.org/pdf/1906.06698](http://arxiv.org/pdf/1906.06698)

