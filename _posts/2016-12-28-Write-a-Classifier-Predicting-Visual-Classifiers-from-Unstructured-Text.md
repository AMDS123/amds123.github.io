---
layout: post
title: "Write a Classifier: Predicting Visual Classifiers from Unstructured Text"
date: 2016-12-28 02:13:59
categories: arXiv_SD
tags: arXiv_SD Knowledge Optimization Prediction
author: Mohamed Elhoseiny, Ahmed Elgammal, Babak Saleh
mathjax: true
---

* content
{:toc}

##### Abstract
People typically learn through exposure to visual concepts associated with linguistic descriptions. For instance, teaching visual object categories to children is often accompanied by descriptions in text or speech. In a machine learning context, these observations motivates us to ask whether this learning process could be computationally modeled to learn visual classifiers. More specifically, the main question of this work is how to utilize purely textual description of visual classes with no training images, to learn explicit visual classifiers for them. We propose and investigate two baseline formulations, based on regression and domain transfer, that predict a linear classifier. Then, we propose a new constrained optimization formulation that combines a regression function and a knowledge transfer function with additional constraints to predict the parameters of a linear classifier. We also propose a generic kernelized models where a kernel classifier is predicted in the form defined by the representer theorem. The kernelized models allow defining and utilizing any two RKHS (Reproducing Kernel Hilbert Space) kernel functions in the visual space and text space, respectively. We finally propose a kernel function between unstructured text descriptions that builds on distributional semantics, which shows an advantage in our setting and could be useful for other applications. We applied all the studied models to predict visual classifiers on two fine-grained and challenging categorization datasets (CU Birds and Flower Datasets), and the results indicate successful predictions of our final model over several baselines that we designed.

##### Abstract (translated by Google)
人们通常通过接触与语言描述相关的视觉概念来学习。例如，向儿童教授视觉对象类别通常伴随着文字或语音的描述。在机器学习的情况下，这些观察激励我们问这个学习过程是否可以通过计算机模拟学习视觉分类器。更具体地说，这个工作的主要问题是如何利用没有训练图像的视觉类的纯文本描述来为它们学习显式视觉分类器。我们提出并研究了基于回归和域转移的两个预测线性分类器的基线公式。然后，我们提出了一个新的约束优化公式，将回归函数和知识传递函数与附加约束相结合，以预测线性分类器的参数。我们还提出了一个通用的核化模型，其中核心分类器以代表者定义的形式进行预测。核化模型允许在视觉空间和文本空间中分别定义和利用任意两个RKHS（再现核仁Hilbert空间）核函数。我们最后提出了基于分布式语义的非结构化文本描述之间的内核函数，它在我们的设置中显示出优势，并且可以用于其他应用程序。我们应用所有的研究模型来预测两个细粒度和具有挑战性的分类数据集（CU鸟类和花数据集）的视觉分类器，结果表明我们最终模型成功地预测了我们设计的几个基线。

##### URL
[https://arxiv.org/abs/1601.00025](https://arxiv.org/abs/1601.00025)

##### PDF
[https://arxiv.org/pdf/1601.00025](https://arxiv.org/pdf/1601.00025)

