---
layout: post
title: "Asymmetric Deep Semantic Quantization for Image Retrieval"
date: 2019-03-29 13:00:03
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN Deep_Learning
author: Zhan Yang, Osolo Ian Raymond, WuQing Sun, Jun Long
mathjax: true
---

* content
{:toc}

##### Abstract
Due to its fast retrieval and storage efficiency capabilities, hashing has been widely used in nearest neighbor retrieval tasks. By using deep learning based techniques, hashing can outperform non-learning based hashing in many applications. However, there are some limitations to previous learning based hashing methods (e.g., the learned hash codes are not discriminative due to the hashing methods being unable to discover rich semantic information and the training strategy having difficulty optimizing the discrete binary codes). In this paper, we propose a novel learning based hashing method, named \textbf{\underline{A}}symmetric \textbf{\underline{D}}eep \textbf{\underline{S}}emantic \textbf{\underline{Q}}uantization (\textbf{ADSQ}). \textbf{ADSQ} is implemented using three stream frameworks, which consists of one \emph{LabelNet} and two \emph{ImgNets}. The \emph{LabelNet} leverages three fully-connected layers, which is used to capture rich semantic information between image pairs. For the two \emph{ImgNets}, they each adopt the same convolutional neural network structure, but with different weights (i.e., asymmetric convolutional neural networks). The two \emph{ImgNets} are used to generate discriminative compact hash codes. Specifically, the function of the \emph{LabelNet} is to capture rich semantic information that is used to guide the two \emph{ImgNets} in minimizing the gap between the real-continuous features and discrete binary codes. By doing this, \textbf{ADSQ} can make full use of the most critical semantic information to guide the feature learning process and consider the consistency of the common semantic space and Hamming space. Results from our experiments demonstrate that \textbf{ADSQ} can generate high discriminative compact hash codes and it outperforms current state-of-the-art methods on three benchmark datasets, CIFAR-10, NUS-WIDE, and ImageNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12493](http://arxiv.org/abs/1903.12493)

##### PDF
[http://arxiv.org/pdf/1903.12493](http://arxiv.org/pdf/1903.12493)

