---
layout: post
title: "Dictionary Learning for Adaptive GPR Target Classification"
date: 2018-05-24 14:42:42
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Classification Detection Relation
author: Fabio Giovanneschi, Kumar Vijay Mishra, Maria Antonia Gonzalez-Huici, Yonina C. Eldar, Joachim H. G. Ender
mathjax: true
---

* content
{:toc}

##### Abstract
Ground penetrating radar (GPR) target detection and classification is a challenging task. Here, we consider various online dictionary learning (DL) methods to obtain sparse representation (SR) of the GPR data to enhance feature extraction for target classification via support vector machine. Online methods are preferred because traditional batch DL like K-SVD is not scalable to high-dimensional training sets and infeasible for real-time operation. We also develop Drop-Off MINi-batch Online Dictionary Learning (DOMINODL) which exploits the fact that a lot of the training data may be correlated. The DOMINODL algorithm iteratively considers elements of the training set in small batches and drops off samples which become less relevant. For the case of abandoned anti-personnel landmines classification, we compare the performance of K-SVD with three online algorithms: classical Online Dictionary Learning, its correlation-based variant and DOMINODL. Our experiments with real data from L-band GPR show that online DL methods reduce learning time by 36-93% and increase mine detection by 4-28% over K-SVD. Our DOMINODL is the fastest and retains similar classification performance as the other two online DL approaches. We use a Kolmogorov-Smirnoff test distance and the Dvoretzky-Kiefer-Wolfowitz inequality for the selection of DL input parameters leading to enhanced classification results. To further compare with state-of-the art classification approaches, we evaluate a convolutional neural network (CNN) classifier which performs worse than the proposed approach. Moreover, when the acquired samples are randomly reduced by 25%, 50% and 75%, sparse decomposition based classification with DL remains robust while the CNN accuracy is drastically compromised.

##### Abstract (translated by Google)
地面穿透雷达（GPR）目标检测和分类是一项具有挑战性的任务。在这里，我们考虑各种在线字典学习（DL）方法来获取GPR数据的稀疏表示（SR），以通过支持向量机增强用于目标分类的特征提取。在线方法是首选，因为像K-SVD这样的传统批量DL不能扩展到高维训练集，并且不适合实时操作。我们还开发Drop-Off MINi批量在线词典学习（DOMINODL），它利用了许多训练数据可能相关的事实。 DOMINODL算法以小批次迭代地考虑训练集的元素，并丢弃变得不太相关的样本。对于遗弃的杀伤人员地雷分类案例，我们比较了K-SVD与三种在线算法的性能：经典在线词典学习，基于相关的变体和多米诺德。我们对来自L波段GPR的实际数据进行的实验表明，在线DL方法比K-SVD减少了36-93％的学习时间，并将探雷增加了4-28％。我们的DOMINODL是最快的，并保留与其他两种在线DL方法类似的分类性能。我们使用Kolmogorov-Smirnoff测试距离和Dvoretzky-Kiefer-Wolfowitz不等式来选择DL输入参数，从而增强分类结果。为了进一步与现有技术的分类方法进行比较，我们评估了一种卷积神经网络（CNN）分类器，其性能比所提​​出的方法差。此外，当采集的样本随机减少25％，50％和75％时，基于稀疏分解的DL分类仍然健壮，同时CNN精度大幅下降。

##### URL
[http://arxiv.org/abs/1806.04599](http://arxiv.org/abs/1806.04599)

##### PDF
[http://arxiv.org/pdf/1806.04599](http://arxiv.org/pdf/1806.04599)

