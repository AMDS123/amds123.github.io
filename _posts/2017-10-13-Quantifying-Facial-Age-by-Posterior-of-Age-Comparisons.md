---
layout: post
title: "Quantifying Facial Age by Posterior of Age Comparisons"
date: 2017-10-13 00:50:36
categories: arXiv_CV
tags: arXiv_CV Face Classification
author: Yunxuan Zhang, Li Liu, Cheng Li, Chen change Loy
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel approach for annotating large quantity of in-the-wild facial images with high-quality posterior age distribution as labels. Each posterior provides a probability distribution of estimated ages for a face. Our approach is motivated by observations that it is easier to distinguish who is the older of two people than to determine the person's actual age. Given a reference database with samples of known ages and a dataset to label, we can transfer reliable annotations from the former to the latter via human-in-the-loop comparisons. We show an effective way to transform such comparisons to posterior via fully-connected and SoftMax layers, so as to permit end-to-end training in a deep network. Thanks to the efficient and effective annotation approach, we collect a new large-scale facial age dataset, dubbed `MegaAge', which consists of 41,941 images. Data can be downloaded from our project page mmlab.ie.cuhk.edu.hk/projects/MegaAge and github.com/zyx2012/Age_estimation_BMVC2017. With the dataset, we train a network that jointly performs ordinal hyperplane classification and posterior distribution learning. Our approach achieves state-of-the-art results on popular benchmarks such as MORPH2, Adience, and the newly proposed MegaAge.

##### Abstract (translated by Google)
我们引入了一种新颖的方法来标注具有高质量后验分布的大量的野外人脸图像。每个后验提供一个面部估计年龄的概率分布。我们的方法是受到观察的启发，比较容易区分谁是两个人的年龄大于确定人的实际年龄。给定具有已知年龄样本和数据集标签的参考数据库，我们可以通过人在回路比较将可靠的注释从前者转移到后者。我们展示了一种通过完全连接和SoftMax层将这种比较转化为后验的有效方法，从而允许在深度网络中进行端到端的训练。得益于高效有效的标注方法，我们收集了一个新的大型面部年龄数据集，名为“MegaAge”，由41941个图像组成。数据可以从我们的项目页面下载mmlab.ie.cuhk.edu.hk/projects/MegaAge和github.com/zyx2012/Age_estimation_BMVC2017。利用这个数据集，我们训练一个联合执行序超平面分类和后验分布学习的网络。我们的方法在流行的基准如MORPH2，Adience和新提出的MegaAge上达到了最新的成果。

##### URL
[https://arxiv.org/abs/1708.09687](https://arxiv.org/abs/1708.09687)

##### PDF
[https://arxiv.org/pdf/1708.09687](https://arxiv.org/pdf/1708.09687)

