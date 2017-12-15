---
layout: post
title: "A constrained clustering based approach for matching a collection of feature sets"
date: 2016-06-12 15:40:30
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Junchi Yan, Zhe Ren, Hongyuan Zha, Stephen Chu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider the problem of finding the feature correspondences among a collection of feature sets, by using their point-wise unary features. This is a fundamental problem in computer vision and pattern recognition, which also closely relates to other areas such as operational research. Different from two-set matching which can be transformed to a quadratic assignment programming task that is known NP-hard, inclusion of merely unary attributes leads to a linear assignment problem for matching two feature sets. This problem has been well studied and there are effective polynomial global optimum solvers such as the Hungarian method. However, it becomes ill-posed when the unary attributes are (heavily) corrupted. The global optimal correspondence concerning the best score defined by the attribute affinity/cost between the two sets can be distinct to the ground truth correspondence since the score function is biased by noises. To combat this issue, we devise a method for matching a collection of feature sets by synergetically exploring the information across the sets. In general, our method can be perceived from a (constrained) clustering perspective: in each iteration, it assigns the features of one set to the clusters formed by the rest of feature sets, and updates the cluster centers in turn. Results on both synthetic data and real images suggest the efficacy of our method against state-of-the-arts.

##### Abstract (translated by Google)
在本文中，我们考虑通过使用它们的一元特征来寻找特征集合之间的特征对应关系的问题。这是计算机视觉和模式识别的一个基本问题，也与运筹学等其他领域密切相关。不同于可以变换为已知NP-hard的二次分配编程任务的二集合匹配，仅包含一元属性导致用于匹配两个特征集合的线性分配问题。这个问题已经得到很好的研究，并且存在有效的多项式全局最优解，如匈牙利法。然而，当一元属性（严重）损坏时，它就变得不适当了。由于得分函数受噪声偏差，关于由两个集合之间的属性亲和度/成本所定义的最佳分数的全局最优对应关系可能与地面真值对应关系不同。为了解决这个问题，我们设计了一种通过协同探索集合中的信息来匹配一组特征集合的方法。一般而言，我们的方法可以从（约束）聚类的角度来看待：在每次迭代中，将一个集合的特征分配给其余特征集合形成的集群，并依次更新聚类中心。对合成数据和真实图像的结果表明了我们的方法对艺术水平的有效性。

##### URL
[https://arxiv.org/abs/1606.03731](https://arxiv.org/abs/1606.03731)

##### PDF
[https://arxiv.org/pdf/1606.03731](https://arxiv.org/pdf/1606.03731)

