---
layout: post
title: "An Empirical Study of Dimensional Reduction Techniques for Facial Action Units Detection"
date: 2016-03-25 21:27:31
categories: arXiv_CV
tags: arXiv_CV Embedding Detection
author: Zhuo Hui, Wen-Sheng Chu
mathjax: true
---

* content
{:toc}

##### Abstract
Biologically inspired features, such as Gabor filters, result in very high dimensional measurement. Does reducing the dimensionality of the feature space afford advantages beyond computational efficiency? Do some approaches to dimensionality reduction (DR) yield improved action unit detection? To answer these questions, we compared DR approaches in two relatively large databases of spontaneous facial behavior (45 participants in total with over 2 minutes of FACS-coded video per participant). Facial features were tracked and aligned using active appearance models (AAM). SIFT and Gabor features were extracted from local facial regions. We compared linear (PCA and KPCA), manifold (LPP and LLE), supervised (LDA and KDA) and hybrid approaches (LSDA) to DR with respect to AU detection. For further comparison, a no-DR control condition was included as well. Linear support vector machine classifiers with independent train and test sets were used for AU detection. AU detection was quantified using area under the ROC curve and F1. Baseline results for PCA with Gabor features were comparable with previous research. With some notable exceptions, DR improved AU detection relative to no-DR. Locality embedding approaches proved vulnerable to \emph{out-of-sample} problems. Gradient-based SIFT lead to better AU detection than the filter-based Gabor features. For area under the curve, few differences were found between linear and other DR approaches. For F1, results were mixed. For both metrics, the pattern of results varied among action units. These findings suggest that action unit detection may be optimized by using specific DR for specific action units. PCA and LDA were the most efficient approaches; KDA was the least efficient.

##### Abstract (translated by Google)
生物启发的特征，如Gabor滤波器，可以得到非常高的尺寸测量结果。减少特征空间的维度是否能够提供超越计算效率的优势？降低维度（DR）产量的一些方法是否改进了动作单元检测？为了回答这些问题，我们比较了DR方法在两个相对较大的自发面部行为数据库（每个参与者超过2分钟的FACS编码的视频总共45名参与者）中。使用主动外观模型（AAM）追踪和对齐面部特征。 SIFT和Gabor特征是从当地的面部区域提取的。我们比较了线性（PCA和KPCA），流形（LPP和LLE），监督（LDA和KDA）和混合方法（LSDA）与DR的相对于AU检测。为了进一步比较，还包括了无DR控制条件。具有独立训练和测试集的线性支持向量机分类器被用于AU检测。使用ROC曲线下的面积和F1对AU检测进行量化。具有Gabor特征的PCA的基线结果与以前的研究相当。除了一些值得注意的例外，DR相对于无DR来改进AU检测。局部嵌入方法被证明容易受到\ emph {样本外的问题的影响。基于梯度的SIFT比基于滤波器的Gabor特征导致更好的AU检测。对于曲线下面积，线性和其他DR方法之间几乎没有差异。对于F1来说，结果是混合的。对于这两个度量标准，结果模式在不同的行动单位中是不同的这些发现表明，可以通过对特定的行动单位使用特定的DR来优化行动单位检测。 PCA和LDA是最有效的方法; KDA效率最低。

##### URL
[https://arxiv.org/abs/1603.08039](https://arxiv.org/abs/1603.08039)

##### PDF
[https://arxiv.org/pdf/1603.08039](https://arxiv.org/pdf/1603.08039)

