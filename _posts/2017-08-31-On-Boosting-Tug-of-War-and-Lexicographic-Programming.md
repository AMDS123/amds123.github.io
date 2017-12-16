---
layout: post
title: "On Boosting, Tug of War, and Lexicographic Programming"
date: 2017-08-31 12:41:29
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Shounak Datta, Sayak Nag, Swagatam Das
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the large amount of research effort dedicated to adapting boosting for imbalanced classification, boosting methods are yet to be satisfactorily immune to class imbalance, especially for multi-class problems, due to the long-standing reliance on expensive cost set tuning. We show that the assignment of weights to the component classifiers of a boosted ensemble can be thought of as a game of Tug of War between the classes in the margin space. We then demonstrate how this insight can be used to attain a good compromise between the rare and abundant classes without having to resort to cost set tuning, which has long been the norm for imbalanced classification. The solution is based on a lexicographic linear programming framework which requires two stages. Initially, class-specific component weight combinations are found so as to minimize a hinge loss individually for each of the classes. Subsequently, the final component weights are assigned so that the maximum deviation from the class-specific minimum loss values (obtained in the previous stage) is minimized. Hence, the proposal is not only restricted to two-class situations, but is also readily applicable to multi-class problems. We also derive the dual formulation corresponding to the proposed framework. Experiments conducted on artificial and real-world imbalanced datasets as well as challenging applications such as hyperspectral image classification and ImageNet classification establish the efficacy of the proposal.

##### Abstract (translated by Google)
尽管大量的研究努力致力于适应不平衡分类的提升，但由于长期依赖于昂贵的成本集调整，提升方法仍然不能满足类不平衡的要求，尤其是对于多类问题。我们表明，权重的分配组合分类器可以被认为是在边缘空间的类之间的拉锯战游戏。然后，我们将展示如何利用这种洞察力，在罕见和丰富的阶级之间达成良好的妥协，而不必诉诸于长期以来一直是不平衡分类的常态的成本集调整。该解决方案基于一个需要两个阶段的字典式线性编程框架。最初，发现类别特定的部件重量组合，以便使每个类别的铰链损失最小化。随后，分配最终分量权重，以使与类别特定最小损失值（在前一阶段中获得）的最大偏差最小化。因此，这个建议不仅限于两类情况，而且也适用于多类问题。我们也推导出与拟议框架相对应的双重表述。对人造和现实世界的不平衡数据集进行的实验以及高光谱图像分类和ImageNet分类等具有挑战性的应用程序确定了提议的功效。

##### URL
[https://arxiv.org/abs/1708.09684](https://arxiv.org/abs/1708.09684)

##### PDF
[https://arxiv.org/pdf/1708.09684](https://arxiv.org/pdf/1708.09684)

