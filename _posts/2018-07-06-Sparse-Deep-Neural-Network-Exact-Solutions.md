---
layout: post
title: "Sparse Deep Neural Network Exact Solutions"
date: 2018-07-06 00:47:12
categories: arXiv_CV
tags: arXiv_CV Sparse Inference
author: Jeremy Kepner, Vijay Gadepally, Hayden Jananthan, Lauren Milechin, Sid Samsi
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks (DNNs) have emerged as key enablers of machine learning. Applying larger DNNs to more diverse applications is an important challenge. The computations performed during DNN training and inference are dominated by operations on the weight matrices describing the DNN. As DNNs incorporate more layers and more neurons per layers, these weight matrices may be required to be sparse because of memory limitations. Sparse DNNs are one possible approach, but the underlying theory is in the early stages of development and presents a number of challenges, including determining the accuracy of inference and selecting nonzero weights for training. Associative array algebra has been developed by the big data community to combine and extend database, matrix, and graph/network concepts for use in large, sparse data problems. Applying this mathematics to DNNs simplifies the formulation of DNN mathematics and reveals that DNNs are linear over oscillating semirings. This work uses associative array DNNs to construct exact solutions and corresponding perturbation models to the rectified linear unit (ReLU) DNN equations that can be used to construct test vectors for sparse DNN implementations over various precisions. These solutions can be used for DNN verification, theoretical explorations of DNN properties, and a starting point for the challenge of sparse training.

##### Abstract (translated by Google)
深度神经网络（DNN）已成为机器学习的关键推动因素。将更大的DNN应用于更多样化的应用程序是一项重要挑战。在DNN训练和推理期间执行的计算由描述DNN的权重矩阵上的操作支配。由于DNN每层包含更多层和更多神经元，因此存储器限制可能要求这些权重矩阵稀疏。稀疏DNN是一种可能的方法，但基础理论处于开发的早期阶段，并提出了许多挑战，包括确定推理的准确性和选择非零权重进行培训。大数据社区已经开发了关联数组代数，用于组合和扩展数据库，矩阵和图形/网络概念，以用于大型稀疏数据问题。将这种数学应用于DNN简化了DNN数学的公式化，并揭示了DNN在振荡半环上是线性的。这项工作使用关联数组DNN来构造精确解和相应的扰动模型到整流线性单元（ReLU）DNN方程，可用于构建用于稀疏DNN实现的测试向量的各种精度。这些解决方案可用于DNN验证，DNN属性的理论探索，以及稀疏训练挑战的起点。

##### URL
[http://arxiv.org/abs/1807.03165](http://arxiv.org/abs/1807.03165)

##### PDF
[http://arxiv.org/pdf/1807.03165](http://arxiv.org/pdf/1807.03165)

