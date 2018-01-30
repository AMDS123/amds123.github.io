---
layout: post
title: "Deep Neural Networks In Fully Connected CRF For Image Labeling With Social Network Metadata"
date: 2018-01-27 16:13:22
categories: arXiv_CV
tags: arXiv_CV CNN Optimization Inference RNN Prediction
author: Chengjiang Long, Roddy Collins, Eran Swears, Anthony Hoogs
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel method for predicting image labels by fusing image content descriptors with the social media context of each image. An image uploaded to a social media site such as Flickr often has meaningful, associated information, such as comments and other images the user has uploaded, that is complementary to pixel content and helpful in predicting labels. Prediction challenges such as ImageNet~\cite{imagenet_cvpr09} and MSCOCO~\cite{LinMBHPRDZ:ECCV14} use only pixels, while other methods make predictions purely from social media context \cite{McAuleyECCV12}. Our method is based on a novel fully connected Conditional Random Field (CRF) framework, where each node is an image, and consists of two deep Convolutional Neural Networks (CNN) and one Recurrent Neural Network (RNN) that model both textual and visual node/image information. The edge weights of the CRF graph represent textual similarity and link-based metadata such as user sets and image groups. We model the CRF as an RNN for both learning and inference, and incorporate the weighted ranking loss and cross entropy loss into the CRF parameter optimization to handle the training data imbalance issue. Our proposed approach is evaluated on the MIR-9K dataset and experimentally outperforms current state-of-the-art approaches.

##### Abstract (translated by Google)
我们提出了一种新的方法来预测图像标签融合图像内容描述符与每个图像的社交媒体上下文。上传到社交媒体网站（例如Flickr）的图片通常具有有意义的相关信息，例如用户上传的评论和其他图片，这与像素内容互补，有助于预测标签。诸如ImageNet_cite {imagenet_cvpr09}和MSCOCO_cite {LinMBHPRDZ：ECCV14}的预测挑战仅使用像素，而其他方法纯粹来自社交媒体环境\ cite {McAuleyECCV12}的预测。我们的方法是基于一个新颖的全连接的条件随机场（CRF）框架，其中每个节点是一个图像，由两个深度卷积神经网络（CNN）和一个循环神经网络（RNN）组成， /图像信息。 CRF图的边权重表示文本相似性和基于链接的元数据，例如用户集和图像组。我们将CRF建模为学习和推理的RNN，并将加权排序损失和交叉熵损失纳入CRF参数优化处理训练数据不平衡问题。我们提出的方法在MIR-9K数据集上进行评估，并在实验上胜过当前最新的方法。

##### URL
[http://arxiv.org/abs/1801.09108](http://arxiv.org/abs/1801.09108)

##### PDF
[http://arxiv.org/pdf/1801.09108](http://arxiv.org/pdf/1801.09108)

