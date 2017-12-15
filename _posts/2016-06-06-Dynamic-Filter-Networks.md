---
layout: post
title: "Dynamic Filter Networks"
date: 2016-06-06 15:39:10
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Bert De Brabandere, Xu Jia, Tinne Tuytelaars, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
In a traditional convolutional layer, the learned filters stay fixed after training. In contrast, we introduce a new framework, the Dynamic Filter Network, where filters are generated dynamically conditioned on an input. We show that this architecture is a powerful one, with increased flexibility thanks to its adaptive nature, yet without an excessive increase in the number of model parameters. A wide variety of filtering operations can be learned this way, including local spatial transformations, but also others like selective (de)blurring or adaptive feature extraction. Moreover, multiple such layers can be combined, e.g. in a recurrent architecture. We demonstrate the effectiveness of the dynamic filter network on the tasks of video and stereo prediction, and reach state-of-the-art performance on the moving MNIST dataset with a much smaller model. By visualizing the learned filters, we illustrate that the network has picked up flow information by only looking at unlabelled training data. This suggests that the network can be used to pretrain networks for various supervised tasks in an unsupervised way, like optical flow and depth estimation.

##### Abstract (translated by Google)
在传统的卷积层中，学习过滤器在训练后保持固定。相比之下，我们引入了一个新的框架，动态过滤器网络，其中过滤器动态生成条件的输入。我们表明，这个架构是一个强大的架构，由于其适应性，增加了灵活性，但没有过多增加模型参数。可以以这种方式学习各种各样的滤波操作，包括局部空间变换，还有其他的如选择性（去）模糊或自适应特征提取。而且，可以组合多个这样的层，例如，在一个经常性的架构。我们展示了动态滤波网络在视频和立体声预测任务上的有效性，并且用更小的模型在移动的MNIST数据集上达到了最先进的性能。通过对学习过滤器进行可视化，我们可以说明，网络只通过查看未标记的训练数据来获取流量信息。这表明网络可以用于以无监督的方式预先训练网络的各种监督任务，如光流和深度估计。

##### URL
[https://arxiv.org/abs/1605.09673](https://arxiv.org/abs/1605.09673)

##### PDF
[https://arxiv.org/pdf/1605.09673](https://arxiv.org/pdf/1605.09673)

