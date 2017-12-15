---
layout: post
title: "Joint Training of Generic CNN-CRF Models with Stochastic Optimization"
date: 2016-09-14 11:52:49
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Gradient_Descent
author: Alexander Kirillov, Dmitrij Schlesinger, Shuai Zheng, Bogdan Savchynskyy, Philip H.S. Torr, Carsten Rother
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new CNN-CRF end-to-end learning framework, which is based on joint stochastic optimization with respect to both Convolutional Neural Network (CNN) and Conditional Random Field (CRF) parameters. While stochastic gradient descent is a standard technique for CNN training, it was not used for joint models so far. We show that our learning method is (i) general, i.e. it applies to arbitrary CNN and CRF architectures and potential functions; (ii) scalable, i.e. it has a low memory footprint and straightforwardly parallelizes on GPUs; (iii) easy in implementation. Additionally, the unified CNN-CRF optimization approach simplifies a potential hardware implementation. We empirically evaluate our method on the task of semantic labeling of body parts in depth images and show that it compares favorably to competing techniques.

##### Abstract (translated by Google)
我们提出了一种新的CNN-CRF端到端学习框架，该框架基于卷积神经网络（CNN）和条件随机场（CRF）参数的联合随机优化。随机梯度下降是CNN训练的一种标准技术，到目前为止还没有用于联合模型。我们表明，我们的学习方法是（一）一般，即它适用于任意CNN和CRF架构和潜在的功能; （ii）可缩放，即其具有低内存占用量并且在GPU上直接并行化; （iii）易于执行。另外，统一的CNN-CRF优化方法简化了潜在的硬件实现。我们实验评估我们的方法在深度图像中的身体部位的语义标记的任务，并表明它比竞争技术的优势。

##### URL
[https://arxiv.org/abs/1511.05067](https://arxiv.org/abs/1511.05067)

##### PDF
[https://arxiv.org/pdf/1511.05067](https://arxiv.org/pdf/1511.05067)

