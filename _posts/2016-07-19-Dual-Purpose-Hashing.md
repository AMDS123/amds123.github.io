---
layout: post
title: "Dual Purpose Hashing"
date: 2016-07-19 11:37:00
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval CNN Relation
author: Haomiao Liu, Ruiping Wang, Shiguang Shan, Xilin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have seen more and more demand for a unified framework to address multiple realistic image retrieval tasks concerning both category and attributes. Considering the scale of modern datasets, hashing is favorable for its low complexity. However, most existing hashing methods are designed to preserve one single kind of similarity, thus improper for dealing with the different tasks simultaneously. To overcome this limitation, we propose a new hashing method, named Dual Purpose Hashing (DPH), which jointly preserves the category and attribute similarities by exploiting the Convolutional Neural Network (CNN) models to hierarchically capture the correlations between category and attributes. Since images with both category and attribute labels are scarce, our method is designed to take the abundant partially labelled images on the Internet as training inputs. With such a framework, the binary codes of new-coming images can be readily obtained by quantizing the network outputs of a binary-like layer, and the attributes can be recovered from the codes easily. Experiments on two large-scale datasets show that our dual purpose hash codes can achieve comparable or even better performance than those state-of-the-art methods specifically designed for each individual retrieval task, while being more compact than the compared methods.

##### Abstract (translated by Google)
近年来，越来越多的人需要一个统一的框架来处理涉及类别和属性的多个真实的图像检索任务。考虑到现代数据集的规模，散列有利于低复杂度。但是，大多数现有的哈希方法被设计为保持单一类型的相似性，因此不适合同时处理不同的任务。为了克服这个局限性，我们提出了一种新的哈希方法，称为双目哈希（DPH），它通过利用卷积神经网络（CNN）模型来分类地捕获类别和属性之间的相关性，从而共同保留类别和属性的相似性。由于具有类别和属性标签的图像是稀缺的，我们的方法被设计成将互联网上丰富的部分标记的图像作为训练输入。利用这种框架，通过对二进制层的网络输出进行量化，可以容易地获得新到图像的二进制码，并且可以容易地从这些码恢复属性。在两个大规模数据集上的实验表明，与比较方法相比，我们的双重目的哈希码可以达到与为每个单独检索任务专门设计的最先进的方法相比甚至更好的性能。

##### URL
[https://arxiv.org/abs/1607.05529](https://arxiv.org/abs/1607.05529)

##### PDF
[https://arxiv.org/pdf/1607.05529](https://arxiv.org/pdf/1607.05529)

