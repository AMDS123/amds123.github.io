---
layout: post
title: "Spatial-Winograd Pruning Enabling Sparse Winograd Convolution"
date: 2019-01-08 02:17:44
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Jiecao Yu, Jongsoo Park, Maxim Naumov
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) are deployed in various applications but demand immense computational requirements. Pruning techniques and Winograd convolution are two typical methods to reduce the CNN computation. However, they cannot be directly combined because Winograd transformation fills in the sparsity resulting from pruning. Li et al. (2017) propose sparse Winograd convolution in which weights are directly pruned in the Winograd domain, but this technique is not very practical because Winograd-domain retraining requires low learning rates and hence significantly longer training time. Besides, Liu et al. (2018) move the ReLU function into the Winograd domain, which can help increase the weight sparsity but requires changes in the network structure. To achieve a high Winograd-domain weight sparsity without changing network structures, we propose a new pruning method, spatial-Winograd pruning. As the first step, spatial-domain weights are pruned in a structured way, which efficiently transfers the spatial-domain sparsity into the Winograd domain and avoids Winograd-domain retraining. For the next step, we also perform pruning and retraining directly in the Winograd domain but propose to use an importance factor matrix to adjust weight importance and weight gradients. This adjustment makes it possible to effectively retrain the pruned Winograd-domain network without changing the network structure. For the three models on the datasets of CIFAR10, CIFAR-100, and ImageNet, our proposed method can achieve the Winograd domain sparsities of 63%, 50%, and 74%, respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02132](http://arxiv.org/abs/1901.02132)

##### PDF
[http://arxiv.org/pdf/1901.02132](http://arxiv.org/pdf/1901.02132)

