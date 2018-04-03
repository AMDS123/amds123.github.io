---
layout: post
title: "Iterative Learning with Open-set Noisy Labels"
date: 2018-03-31 00:27:30
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Detection
author: Yisen Wang, Weiyang Liu, Xingjun Ma, James Bailey, Hongyuan Zha, Le Song, Shu-Tao Xia
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale datasets possessing clean label annotations are crucial for training Convolutional Neural Networks (CNNs). However, labeling large-scale data can be very costly and error-prone, and even high-quality datasets are likely to contain noisy (incorrect) labels. Existing works usually employ a closed-set assumption, whereby the samples associated with noisy labels possess a true class contained within the set of known classes in the training data. However, such an assumption is too restrictive for many applications, since samples associated with noisy labels might in fact possess a true class that is not present in the training data. We refer to this more complex scenario as the \textbf{open-set noisy label} problem and show that it is nontrivial in order to make accurate predictions. To address this problem, we propose a novel iterative learning framework for training CNNs on datasets with open-set noisy labels. Our approach detects noisy labels and learns deep discriminative features in an iterative fashion. To benefit from the noisy label detection, we design a Siamese network to encourage clean labels and noisy labels to be dissimilar. A reweighting module is also applied to simultaneously emphasize the learning from clean labels and reduce the effect caused by noisy labels. Experiments on CIFAR-10, ImageNet and real-world noisy (web-search) datasets demonstrate that our proposed model can robustly train CNNs in the presence of a high proportion of open-set as well as closed-set noisy labels.

##### Abstract (translated by Google)
拥有干净标签注释的大规模数据集对于训练卷积神经网络（CNN）至关重要。但是，标注大规模数据可能非常昂贵并且容易出错，甚至高质量数据集可能包含嘈杂（不正确）的标签。现有作品通常采用封闭假设，即与噪音标签相关的样本拥有包含在训练数据中已知类别集合中的真实类别。然而，对于许多应用来说，这样的假设太严格了，因为与嘈杂标签相关联的样本实际上可能拥有真实的类别，这在训练数据中不存在。我们将这个更复杂的场景称为\ textbf {open-set noisy label}问题，并表明它是非常重要的，以便做出准确的预测。为了解决这个问题，我们提出了一种新颖的迭代学习框架，用于在开放式噪声标签的数据集上训练CNN。我们的方法检测嘈杂的标签，并以迭代的方式学习深度区分特征。为了从嘈杂的标签检测中受益，我们设计了一个连体网络，以鼓励干净的标签和嘈杂的标签不相同。一个重新加权模块也被用来同时强调从干净的标签学习和减少由嘈杂的标签造成的影响。在CIFAR-10，ImageNet和真实世界噪声（网络搜索）数据集上的实验表明，我们提出的模型可以在高比例的开集和闭集噪声标签的情况下强大地训练CNN。

##### URL
[http://arxiv.org/abs/1804.00092](http://arxiv.org/abs/1804.00092)

##### PDF
[http://arxiv.org/pdf/1804.00092](http://arxiv.org/pdf/1804.00092)

