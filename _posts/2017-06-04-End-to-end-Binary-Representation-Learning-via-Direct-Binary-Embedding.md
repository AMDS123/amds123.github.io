---
layout: post
title: "End-to-end Binary Representation Learning via Direct Binary Embedding"
date: 2017-06-04 04:44:40
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding CNN Represenation_Learning Relation Recognition
author: Liu Liu, Alireza Rahimpour, Ali Taalimi, Hairong Qi
mathjax: true
---

* content
{:toc}

##### Abstract
Learning binary representation is essential to large-scale computer vision tasks. Most existing algorithms require a separate quantization constraint to learn effective hashing functions. In this work, we present Direct Binary Embedding (DBE), a simple yet very effective algorithm to learn binary representation in an end-to-end fashion. By appending an ingeniously designed DBE layer to the deep convolutional neural network (DCNN), DBE learns binary code directly from the continuous DBE layer activation without quantization error. By employing the deep residual network (ResNet) as DCNN component, DBE captures rich semantics from images. Furthermore, in the effort of handling multilabel images, we design a joint cross entropy loss that includes both softmax cross entropy and weighted binary cross entropy in consideration of the correlation and independence of labels, respectively. Extensive experiments demonstrate the significant superiority of DBE over state-of-the-art methods on tasks of natural object recognition, image retrieval and image annotation.

##### Abstract (translated by Google)
学习二进制表示对于大规模计算机视觉任务是必不可少的。大多数现有算法需要单独的量化约束来学习有效的散列函数。在这项工作中，我们提出了直接二进制嵌入（DBE），一种简单但非常有效的算法，以端到端的方式学习二进制表示。通过在深度卷积神经网络（DCNN）上附加一个巧妙设计的DBE层，DBE直接从连续的DBE层激活中学习二进制代码，而不会产生量化误差。通过采用深度残差网络（ResNet）作为DCNN组件，DBE从图像中捕捉丰富的语义。此外，为了处理多标记图像，我们设计了一个包含softmax交叉熵和加权二叉交叉熵的联合交叉熵损失，分别考虑了标签的相关性和独立性。大量的实验表明DBE相对于最先进的方法在自然物体识别，图像检索和图像注释等任务上具有显着的优越性。

##### URL
[https://arxiv.org/abs/1703.04960](https://arxiv.org/abs/1703.04960)

##### PDF
[https://arxiv.org/pdf/1703.04960](https://arxiv.org/pdf/1703.04960)

