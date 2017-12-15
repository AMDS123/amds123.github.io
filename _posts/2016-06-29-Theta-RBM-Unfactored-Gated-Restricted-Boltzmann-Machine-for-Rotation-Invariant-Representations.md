---
layout: post
title: "Theta-RBM: Unfactored Gated Restricted Boltzmann Machine for Rotation-Invariant Representations"
date: 2016-06-29 09:57:08
categories: arXiv_CV
tags: arXiv_CV
author: Mario Valerio Giuffrida, Sotirios A. Tsaftaris
mathjax: true
---

* content
{:toc}

##### Abstract
Learning invariant representations is a critical task in computer vision. In this paper, we propose the Theta-Restricted Boltzmann Machine ({\theta}-RBM in short), which builds upon the original RBM formulation and injects the notion of rotation-invariance during the learning procedure. In contrast to previous approaches, we do not transform the training set with all possible rotations. Instead, we rotate the gradient filters when they are computed during the Contrastive Divergence algorithm. We formulate our model as an unfactored gated Boltzmann machine, where another input layer is used to modulate the input visible layer to drive the optimisation procedure. Among our contributions is a mathematical proof that demonstrates that {\theta}-RBM is able to learn rotation-invariant features according to a recently proposed invariance measure. Our method reaches an invariance score of ~90% on mnist-rot dataset, which is the highest result compared with the baseline methods and the current state of the art in transformation-invariant feature learning in RBM. Using an SVM classifier, we also showed that our network learns discriminative features as well, obtaining ~10% of testing error.

##### Abstract (translated by Google)
学习不变表示是计算机视觉中的关键任务。在本文中，我们提出了Theta限制玻尔兹曼机器（简称{\​​ theta} -RBM），它建立在原始RBM公式的基础上，并在学习过程中注入旋转不变性的概念。与以前的方法相比，我们不会对所有可能的旋转进行训练集合。相反，我们在对比散度算法期间计算梯度滤波器时旋转它们。我们将我们的模型制定成一个不受限制的门控波尔兹曼（Boltzmann）机器，其中另一个输入层用于调制输入可见层以驱动优化过程。我们的贡献是一个数学证明，证明{\θ} -RBM能够根据最近提出的不变量度量学习旋转不变特征。我们的方法在mnist-rot数据集上达到约90％的不变性得分，这是与基线方法相比最高的结果，也是RBM中变换不变特征学习的最新技术。使用支持向量机分类器，我们也表明，我们的网络学习歧视性的特征，获得~10％的测试错误。

##### URL
[https://arxiv.org/abs/1606.08805](https://arxiv.org/abs/1606.08805)

##### PDF
[https://arxiv.org/pdf/1606.08805](https://arxiv.org/pdf/1606.08805)

