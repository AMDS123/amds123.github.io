---
layout: post
title: "An Extended Framework for Marginalized Domain Adaptation"
date: 2017-02-20 15:00:13
categories: arXiv_CV
tags: arXiv_CV Regularization Classification Prediction
author: Gabriela Csurka, Boris Chidlovski, Stephane Clinchant, Sophia Michel
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an extended framework for marginalized domain adaptation, aimed at addressing unsupervised, supervised and semi-supervised scenarios. We argue that the denoising principle should be extended to explicitly promote domain-invariant features as well as help the classification task. Therefore we propose to jointly learn the data auto-encoders and the target classifiers. First, in order to make the denoised features domain-invariant, we propose a domain regularization that may be either a domain prediction loss or a maximum mean discrepancy between the source and target data. The noise marginalization in this case is reduced to solving the linear matrix system $AX=B$ which has a closed-form solution. Second, in order to help the classification, we include a class regularization term. Adding this component reduces the learning problem to solving a Sylvester linear matrix equation $AX+BX=C$, for which an efficient iterative procedure exists as well. We did an extensive study to assess how these regularization terms improve the baseline performance in the three domain adaptation scenarios and present experimental results on two image and one text benchmark datasets, conventionally used for validating domain adaptation methods. We report our findings and comparison with state-of-the-art methods.

##### Abstract (translated by Google)
我们提出了一个边缘化领域适应的扩展框架，旨在解决无监督，监督和半监督的情况。我们认为，应该扩展去噪原理，明确提升领域不变特征以及帮助分类任务。因此，我们建议联合学习数据自动编码器和目标分类器。首先，为了使去噪特征域不变，我们提出一个域的正则化，可能是域预测损失或源和目标数据之间的最大平均差异。在这种情况下的噪声边缘化被减少到求解具有封闭形式解的线性矩阵系统$ AX = B $。其次，为了帮助分类，我们包含一个类正则化术语。增加这个分量减少了学习问题，解决一个Sylvester线性矩阵方程$ AX + BX = C $，为此也存在一个有效的迭代过程。我们进行了广泛的研究，以评估这些正则化术语如何改善三个领域适应情景中的基线性能，并且在两个图像和一个文本基准数据集上呈现实验结果，这些数据集通常用于验证领域适应方法。我们报告我们的研究结果，并与最先进的方法进行比较。

##### URL
[https://arxiv.org/abs/1702.05993](https://arxiv.org/abs/1702.05993)

##### PDF
[https://arxiv.org/pdf/1702.05993](https://arxiv.org/pdf/1702.05993)

