---
layout: post
title: "Margin Matters: Towards More Discriminative Deep Neural Network Embeddings for Speaker Recognition"
date: 2019-06-18 00:31:04
categories: arXiv_CL
tags: arXiv_CL Embedding Recognition
author: Xu Xiang, Shuai Wang, Houjun Huang, Yanmin Qian, Kai Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, speaker embeddings extracted from a speaker discriminative deep neural network (DNN) yield better performance than the conventional methods such as i-vector. In most cases, the DNN speaker classifier is trained using cross entropy loss with softmax. However, this kind of loss function does not explicitly encourage inter-class separability and intra-class compactness. As a result, the embeddings are not optimal for speaker recognition tasks. In this paper, to address this issue, three different margin based losses which not only separate classes but also demand a fixed margin between classes are introduced to deep speaker embedding learning. It could be demonstrated that the margin is the key to obtain more discriminative speaker embeddings. Experiments are conducted on two public text independent tasks: VoxCeleb1 and Speaker in The Wild (SITW). The proposed approach can achieve the state-of-the-art performance, with 25% ~ 30% equal error rate (EER) reduction on both tasks when compared to strong baselines using cross entropy loss with softmax, obtaining 2.238% EER on VoxCeleb1 test set and 2.761% EER on SITW core-core test set, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07317](http://arxiv.org/abs/1906.07317)

##### PDF
[http://arxiv.org/pdf/1906.07317](http://arxiv.org/pdf/1906.07317)

