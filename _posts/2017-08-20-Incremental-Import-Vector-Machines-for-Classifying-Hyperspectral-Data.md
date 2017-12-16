---
layout: post
title: "Incremental Import Vector Machines for Classifying Hyperspectral Data"
date: 2017-08-20 13:59:00
categories: arXiv_CV
tags: arXiv_CV Sparse Classification
author: Ribana Roscher, Björn Waske, Wolfgang Förstner
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose an incremental learning strategy for import vector machines (IVM), which is a sparse kernel logistic regression approach. We use the procedure for the concept of self-training for sequential classification of hyperspectral data. The strategy comprises the inclusion of new training samples to increase the classification accuracy and the deletion of non-informative samples to be memory- and runtime-efficient. Moreover, we update the parameters in the incremental IVM model without re-training from scratch. Therefore, the incremental classifier is able to deal with large data sets. The performance of the IVM in comparison to support vector machines (SVM) is evaluated in terms of accuracy and experiments are conducted to assess the potential of the probabilistic outputs of the IVM. Experimental results demonstrate that the IVM and SVM perform similar in terms of classification accuracy. However, the number of import vectors is significantly lower when compared to the number of support vectors and thus, the computation time during classification can be decreased. Moreover, the probabilities provided by IVM are more reliable, when compared to the probabilistic information, derived from an SVM's output. In addition, the proposed self-training strategy can increase the classification accuracy. Overall, the IVM and the its incremental version is worthwhile for the classification of hyperspectral data.

##### Abstract (translated by Google)
在本文中，我们提出了一种进口向量机（IVM）的递增学习策略，这是一种稀疏的内核逻辑回归方法。我们使用自适应概念的程序进行高光谱数据的序列分类。该策略包括包含新的训练样本以提高分类准确性，删除非信息性样本以提高记忆和运行效率。此外，我们更新增量IVM模型中的参数，而无需从头开始重新培训。因此，增量分类器能够处理大型数据集。根据精度评估IVM与支持向量机（SVM）相比的性能，并且进行实验以评估IVM的概率输出的潜力。实验结果表明，IVM和SVM在分类准确性方面表现相似。但是，与支持矢量的数量相比，导入矢量的数量显着减少，因此可以减少分类过程中的计算时间。此外，与从支持向量机的输出得出的概率信息相比，由IVM提供的概率更可靠。另外，所提出的自我训练策略可以提高分类的准确性。总体而言，IVM及其增量版本对于高光谱数据的分类是值得的。

##### URL
[https://arxiv.org/abs/1708.05966](https://arxiv.org/abs/1708.05966)

##### PDF
[https://arxiv.org/pdf/1708.05966](https://arxiv.org/pdf/1708.05966)

