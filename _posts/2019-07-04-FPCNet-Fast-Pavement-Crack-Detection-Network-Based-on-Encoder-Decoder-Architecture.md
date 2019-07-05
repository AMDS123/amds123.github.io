---
layout: post
title: "FPCNet: Fast Pavement Crack Detection Network Based on Encoder-Decoder Architecture"
date: 2019-07-04 06:56:24
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Detection
author: Wenjun Liu, Yuchun Huang, Ying Li, Qi Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Timely, accurate and automatic detection of pavement cracks is necessary for making cost-effective decisions concerning road maintenance. Conventional crack detection algorithms focus on the design of single or multiple crack features and classifiers. However, complicated topological structures, varying degrees of damage and oil stains make the design of crack features difficult. In addition, the contextual information around a crack is not investigated extensively in the design process. Accordingly, these design features have limited discriminative adaptability and cannot fuse effectively with the classifiers. To solve these problems, this paper proposes a deep learning network for pavement crack detection. Using the Encoder-Decoder structure, crack characteristics with multiple contexts are automatically learned, and end-to-end crack detection is achieved. Specifically, we first propose the Multi-Dilation (MD) module, which can synthesize the crack features of multiple context sizes via dilated convolution with multiple rates. The crack MD features obtained in this module can describe cracks of different widths and topologies. Next, we propose the SE-Upsampling (SEU) module, which uses the Squeeze-and-Excitation learning operation to optimize the MD features. Finally, the above two modules are integrated to develop the fast crack detection network, namely, FPCNet. This network continuously optimizes the MD features step-by-step to realize fast pixel-level crack detection. Experiments are conducted on challenging public CFD datasets and G45 crack datasets involving various crack types under different shooting conditions. The distinct performance and speed improvements over all the datasets demonstrate that the proposed method outperforms other state-of-the-art crack detection methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02248](http://arxiv.org/abs/1907.02248)

##### PDF
[http://arxiv.org/pdf/1907.02248](http://arxiv.org/pdf/1907.02248)

