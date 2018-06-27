---
layout: post
title: "Online Signature Verification using Deep Representation: A new Descriptor"
date: 2018-06-24 03:15:39
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Mohammad Hajizadeh Saffar, Mohsen Fayyaz, Mohammad Sabokrou, Mahmood Fathy
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an accurate method for verifying online signatures. The main difficulty of signature verification come from: (1) Lacking enough training samples (2) The methods must be spatial change invariant. To deal with these difficulties and modeling the signatures efficiently, we propose a method that a one-class classifier per each user is built on discriminative features. First, we pre-train a sparse auto-encoder using a large number of unlabeled signatures, then we applied the discriminative features, which are learned by auto-encoder to represent the training and testing signatures as a self-thought learning method (i.e. we have introduced a signature descriptor). Finally, user's signatures are modeled and classified using a one-class classifier. The proposed method is independent on signature datasets thanks to self-taught learning. The experimental results indicate significant error reduction and accuracy enhancement in comparison with state-of-the-art methods on SVC2004 and SUSIG datasets.

##### Abstract (translated by Google)
本文提出了一种用于验证在线签名的准确方法。签名验证的主要困难来自：（1）缺乏足够的训练样本（2）方法必须是空间变化不变的。为了处理这些困难并有效地对签名进行建模，我们提出了一种方法，即每个用户的单类分类器都建立在判别特征上。首先，我们使用大量的未标记签名来预训练一个稀疏自动编码器，然后我们应用自动编码器学习的判别特征来表示训练和测试签名为一种自我思考的学习方法（即我们已经引入了签名描述符）。最后，用户的签名使用一个一级分类器进行建模和分类。由于自学教学，所提出的方法独立于签名数据集。实验结果表明，与SVC2004和SUSIG数据集上的最新方法相比，显着降低了错误并提高了准确性。

##### URL
[http://arxiv.org/abs/1806.09986](http://arxiv.org/abs/1806.09986)

##### PDF
[http://arxiv.org/pdf/1806.09986](http://arxiv.org/pdf/1806.09986)

