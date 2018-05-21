---
layout: post
title: "Cross-domain attribute representation based on convolutional neural network"
date: 2018-05-17 14:42:33
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Gradient_Descent
author: Guohui Zhang, Gaoyuan Liang, Fang Su, Fanxin Qu, Jing-Yan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In the problem of domain transfer learning, we learn a model for the predic-tion in a target domain from the data of both some source domains and the target domain, where the target domain is in lack of labels while the source domain has sufficient labels. Besides the instances of the data, recently the attributes of data shared across domains are also explored and proven to be very helpful to leverage the information of different domains. In this paper, we propose a novel learning framework for domain-transfer learning based on both instances and attributes. We proposed to embed the attributes of dif-ferent domains by a shared convolutional neural network (CNN), learn a domain-independent CNN model to represent the information shared by dif-ferent domains by matching across domains, and a domain-specific CNN model to represent the information of each domain. The concatenation of the three CNN model outputs is used to predict the class label. An iterative algo-rithm based on gradient descent method is developed to learn the parameters of the model. The experiments over benchmark datasets show the advantage of the proposed model.

##### Abstract (translated by Google)
在领域转移学习问题中，我们从一些源域和目标域的数据中学习了目标域中预测的模型，其中目标域缺少标签，而源域具有足够的标签。除了数据实例之外，最近还研究了跨域共享的数据属性，并证明对利用不同域的信息非常有帮助。在本文中，我们提出了一种基于实例和属性的领域迁移学习的新型学习框架。我们提出通过共享卷积神经网络（CNN）嵌入不同域的属性，学习一个域独立的CNN模型来表示不同域之间通过跨域匹配共享的信息，以及域特定的CNN模型来表示每个域的信息。三个CNN模型输出的连接用于预测类别标签。开发了基于梯度下降法的迭代算法来学习模型的参数。基准数据集上的实验显示了该模型的优点。

##### URL
[http://arxiv.org/abs/1805.07295](http://arxiv.org/abs/1805.07295)

##### PDF
[http://arxiv.org/pdf/1805.07295](http://arxiv.org/pdf/1805.07295)

