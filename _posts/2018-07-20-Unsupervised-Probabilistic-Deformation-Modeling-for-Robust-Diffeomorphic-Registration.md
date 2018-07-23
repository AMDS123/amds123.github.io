---
layout: post
title: "Unsupervised Probabilistic Deformation Modeling for Robust Diffeomorphic Registration"
date: 2018-07-20 13:03:25
categories: arXiv_CV
tags: arXiv_CV Classification
author: Julian Krebs, Tommaso Mansi, Boris Mailh&#xe9;, Nicholas Ayache, Herv&#xe9; Delingette
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deformable registration algorithm based on unsupervised learning of a low-dimensional probabilistic parameterization of deformations. We model registration in a probabilistic and generative fashion, by applying a conditional variational autoencoder (CVAE) network. This model enables to also generate normal or pathological deformations of any new image based on the probabilistic latent space. Most recent learning-based registration algorithms use supervised labels or deformation models, that miss important properties such as diffeomorphism and sufficiently regular deformation fields. In this work, we constrain transformations to be diffeomorphic by using a differentiable exponentiation layer with a symmetric loss function. We evaluated our method on 330 cardiac MR sequences and demonstrate robust intra-subject registration results comparable to two state-of-the-art methods but with more regular deformation fields compared to a recent learning-based algorithm. Our method reached a mean DICE score of 78.3% and a mean Hausdorff distance of 7.9mm. In two preliminary experiments, we illustrate the model's abilities to transport pathological deformations to healthy subjects and to cluster five diseases in the unsupervised deformation encoding space with a classification performance of 70%.

##### Abstract (translated by Google)
我们提出了一种基于无量纲学习变形的低维概率参数化的可变形配准算法。我们通过应用条件变分自动编码器（CVAE）网络以概率和生成方式对登记进行建模。该模型还能够基于概率潜在空间生成任何新图像的正常或病理变形。最近的基于学习的配准算法使用监督标签或变形模型，这些标签或变形模型错过了重要的属性，例如微分同胚和足够规则的变形场。在这项工作中，我们通过使用具有对称损失函数的可微分取层来将变换约束为微分形。我们在330心脏MR序列上评估了我们的方法，并证明了与两种最先进的方法相当的稳健的受试者内登记结果，但与最近的基于学习的算法相比具有更多的规则变形场。我们的方法达到平均DICE得分为78.3％，平均Hausdorff距离为7.9mm。在两个初步实验中，我们说明了模型将病理变形传递给健康受试者的能力，并在无监督变形编码空间中聚类五种疾病，分类性能为70％。

##### URL
[http://arxiv.org/abs/1804.07172](http://arxiv.org/abs/1804.07172)

##### PDF
[http://arxiv.org/pdf/1804.07172](http://arxiv.org/pdf/1804.07172)

