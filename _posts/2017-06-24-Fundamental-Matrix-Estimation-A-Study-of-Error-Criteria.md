---
layout: post
title: "Fundamental Matrix Estimation: A Study of Error Criteria"
date: 2017-06-24 00:13:29
categories: arXiv_CV
tags: arXiv_CV Relation
author: Mohammed E. Fathy, Ashraf S. Hussein, Mohammed F. Tolba
mathjax: true
---

* content
{:toc}

##### Abstract
The fundamental matrix (FM) describes the geometric relations that exist between two images of the same scene. Different error criteria are used for estimating FMs from an input set of correspondences. In this paper, the accuracy and efficiency aspects of the different error criteria were studied. We mathematically and experimentally proved that the most popular error criterion, the symmetric epipolar distance, is biased. It was also shown that despite the similarity between the algebraic expressions of the symmetric epipolar distance and Sampson distance, they have different accuracy properties. In addition, a new error criterion, Kanatani distance, was proposed and was proved to be the most effective for use during the outlier removal phase from accuracy and efficiency perspectives. To thoroughly test the accuracy of the different error criteria, we proposed a randomized algorithm for Reprojection Error-based Correspondence Generation (RE-CG). As input, RE-CG takes an FM and a desired reprojection error value $d$. As output, RE-CG generates a random correspondence having that error value. Mathematical analysis of this algorithm revealed that the success probability for any given trial is 1 - (2/3)^2 at best and is 1 - (6/7)^2 at worst while experiments demonstrated that the algorithm often succeeds after only one trial.

##### Abstract (translated by Google)
基本矩阵（FM）描述了同一场景的两幅图像之间存在的几何关系。不同的错误标准被用于从输入的对应关系中估计FM。本文研究了不同误差准则的准确性和效率。我们在数学上和实验上证明，最流行的误差准则，即对称的极线距离是有偏差的。也表明，尽管对称极距与桑普森距离的代数表达式相似，但它们具有不同的精度特性。此外，还提出了一个新的误差准则，即Kanatani距离，并从精确度和效率的角度证明了在异常值清除阶段最有效的使用。为了彻底检验不同误差准则的准确性，我们提出了基于重投影误差的对应生成（RE-CG）的随机算法。作为输入，RE-CG采用FM和期望的再投影误差值$ d $。作为输出，RE-CG生成具有该错误值的随机对应关系。该算法的数学分析显示，任何给定试验的成功概率最多为1（2/3）^ 2，最差为1  - （6/7）^ 2，而实验表明该算法经过一次审判。

##### URL
[https://arxiv.org/abs/1706.07886](https://arxiv.org/abs/1706.07886)

##### PDF
[https://arxiv.org/pdf/1706.07886](https://arxiv.org/pdf/1706.07886)

