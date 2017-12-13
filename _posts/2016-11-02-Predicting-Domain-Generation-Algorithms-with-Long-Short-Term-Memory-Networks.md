---
layout: post
title: "Predicting Domain Generation Algorithms with Long Short-Term Memory Networks"
date: 2016-11-02 20:34:56
categories: arXiv_CV
tags: arXiv_CV GAN RNN Classification Detection Memory_Networks
author: Jonathan Woodbridge, Hyrum S. Anderson, Anjum Ahuja, Daniel Grant
mathjax: true
---

* content
{:toc}

##### Abstract
Various families of malware use domain generation algorithms (DGAs) to generate a large number of pseudo-random domain names to connect to a command and control (C&C) server. In order to block DGA C&C traffic, security organizations must first discover the algorithm by reverse engineering malware samples, then generating a list of domains for a given seed. The domains are then either preregistered or published in a DNS blacklist. This process is not only tedious, but can be readily circumvented by malware authors using a large number of seeds in algorithms with multivariate recurrence properties (e.g., banjori) or by using a dynamic list of seeds (e.g., bedep). Another technique to stop malware from using DGAs is to intercept DNS queries on a network and predict whether domains are DGA generated. Such a technique will alert network administrators to the presence of malware on their networks. In addition, if the predictor can also accurately predict the family of DGAs, then network administrators can also be alerted to the type of malware that is on their networks. This paper presents a DGA classifier that leverages long short-term memory (LSTM) networks to predict DGAs and their respective families without the need for a priori feature extraction. Results are significantly better than state-of-the-art techniques, providing 0.9993 area under the receiver operating characteristic curve for binary classification and a micro-averaged F1 score of 0.9906. In other terms, the LSTM technique can provide a 90% detection rate with a 1:10000 false positive (FP) rate---a twenty times FP improvement over comparable methods. Experiments in this paper are run on open datasets and code snippets are provided to reproduce the results.

##### Abstract (translated by Google)
恶意软件的各种家族使用域生成算法（DGAs）来生成大量的伪随机域名以连接到命令和控制（C＆C）服务器。为了阻止DGA C＆C流量，安全组织必须首先通过对恶意软件样本进行逆向工程来发现算法，然后生成给定种子的域列表。然后域名被预先注册或发布在DNS黑名单中。这个过程不仅枯燥乏味，而且可以被恶意软件作者利用具有多变量递归属性的算法（例如banjori）中的大量种子或通过使用动态种子列表（例如，bedep）而容易地避开。阻止恶意软件使用DGAs的另一种技术是拦截网络上的DNS查询，并预测域是否是DGA生成的。这种技术会提醒网络管理员在他们的网络上存在恶意软件。此外，如果预测器还可以准确预测DGA族，那么网络管理员也可以收到网络上恶意软件的类型警报。本文提出了一种利用长期短期记忆（LSTM）网络来预测DGAs及其相应系列的DGA分类器，而不需要先验特征提取。结果显着优于现有技术，在二元分类的受试者操作特征曲线下提供0.9993面积，微平均F1得分为0.9906。换句话说，LSTM技术可以提供90％的检测率和1：10000的假阳性率（FP），这是FP比同类方法提高了20倍。本文中的实验运行在开放的数据集上，并提供代码片段来重现结果。

##### URL
[https://arxiv.org/abs/1611.00791](https://arxiv.org/abs/1611.00791)

##### PDF
[https://arxiv.org/pdf/1611.00791](https://arxiv.org/pdf/1611.00791)

