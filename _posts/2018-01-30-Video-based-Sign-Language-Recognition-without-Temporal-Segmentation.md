---
layout: post
title: "Video-based Sign Language Recognition without Temporal Segmentation"
date: 2018-01-30 17:37:42
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention CNN Recognition
author: Jie Huang, Wengang Zhou, Qilin Zhang, Houqiang Li, Weiping Li
mathjax: true
---

* content
{:toc}

##### Abstract
Millions of hearing impaired people around the world routinely use some variants of sign languages to communicate, thus the automatic translation of a sign language is meaningful and important. Currently, there are two sub-problems in Sign Language Recognition (SLR), i.e., isolated SLR that recognizes word by word and continuous SLR that translates entire sentences. Existing continuous SLR methods typically utilize isolated SLRs as building blocks, with an extra layer of preprocessing (temporal segmentation) and another layer of post-processing (sentence synthesis). Unfortunately, temporal segmentation itself is non-trivial and inevitably propagates errors into subsequent steps. Worse still, isolated SLR methods typically require strenuous labeling of each word separately in a sentence, severely limiting the amount of attainable training data. To address these challenges, we propose a novel continuous sign recognition framework, the Hierarchical Attention Network with Latent Space (LS-HAN), which eliminates the preprocessing of temporal segmentation. The proposed LS-HAN consists of three components: a two-stream Convolutional Neural Network (CNN) for video feature representation generation, a Latent Space (LS) for semantic gap bridging, and a Hierarchical Attention Network (HAN) for latent space based recognition. Experiments are carried out on two large scale datasets. Experimental results demonstrate the effectiveness of the proposed framework.

##### Abstract (translated by Google)
世界各地数以百万计的听力障碍人士经常使用一些手语的变体进行交流，因此手语的自动翻译是有意义和重要的。目前，手语识别（SLR）中存在两个子问题，即单独识别单个SLR和翻译整个句子的连续SLR。现有的连续SLR方法通常利用孤立的SLR作为构建块，具有额外的预处理层（时间分割）和另一层后处理（句子合成）。不幸的是，时间分割本身是不平凡的，并不可避免地将错误传播到随后的步骤中。更糟糕的是，单独的单反方法通常需要在句子中分别严格标注每个单词，严重限制了可获得的训练数据量。针对这些挑战，提出了一种新的连续符号识别框架 - 隐层空间层次注意网络（LS-HAN），消除了时间分割的预处理。所提出的LS-HAN由三部分组成：用于视频特征表示生成的两流卷积神经网络（CNN），用于语义间隙桥接的潜在空间（LS）以及用于基于潜在空间的层级注意网络（HAN） 。实验在两个大规模的数据集上进行。实验结果证明了所提出框架的有效性。

##### URL
[http://arxiv.org/abs/1801.10111](http://arxiv.org/abs/1801.10111)

##### PDF
[http://arxiv.org/pdf/1801.10111](http://arxiv.org/pdf/1801.10111)

