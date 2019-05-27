---
layout: post
title: "Large Batch Optimization for Deep Learning: Training BERT in 76 minutes"
date: 2019-05-24 17:09:47
categories: arXiv_AI
tags: arXiv_AI Optimization Deep_Learning
author: Yang You, Jing Li, Sashank Reddi, Jonathan Hseu, Sanjiv Kumar, Srinadh Bhojanapalli, Xiaodan Song, James Demmel, Cho-Jui Hsieh
mathjax: true
---

* content
{:toc}

##### Abstract
Training large deep neural networks on massive datasets is very challenging. One promising approach to tackle this issue is through the use of large batch stochastic optimization. However, our understanding of this approach in the context of deep learning is still very limited. Furthermore, the current approaches in this direction are heavily hand-tuned. To this end, we first study a general adaptation strategy to accelerate training of deep neural networks using large minibatches. Using this strategy, we develop a new layer-wise adaptive large batch optimization technique called LAMB. We also provide a formal convergence analysis of LAMB as well as the previous published layerwise optimizer LARS, showing convergence to a stationary point in general nonconvex settings. Our empirical results demonstrate the superior performance of LAMB for BERT and ResNet-50 training. In particular, for BERT training, our optimization technique enables use of very large batches sizes of 32868; thereby, requiring just 8599 iterations to train (as opposed to 1 million iterations in the original paper). By increasing the batch size to the memory limit of a TPUv3 pod, BERT training time can be reduced from 3 days to 76 minutes. Finally, we also demonstrate that LAMB outperforms previous large-batch training algorithms for ResNet-50 on ImageNet; obtaining state-of-the-art performance in just a few minutes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.00962](http://arxiv.org/abs/1904.00962)

##### PDF
[http://arxiv.org/pdf/1904.00962](http://arxiv.org/pdf/1904.00962)

