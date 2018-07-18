---
layout: post
title: "Reconstructing Subject-Specific Effect Maps"
date: 2018-07-17 10:18:58
categories: arXiv_CV
tags: arXiv_CV Inference Detection Relation
author: Ender Konukoglu, Ben Glocker
mathjax: true
---

* content
{:toc}

##### Abstract
Predictive models allow subject-specific inference when analyzing disease related alterations in neuroimaging data. Given a subject's data, inference can be made at two levels: global, i.e. identifiying condition presence for the subject, and local, i.e. detecting condition effect on each individual measurement extracted from the subject's data. While global inference is widely used, local inference, which can be used to form subject-specific effect maps, is rarely used because existing models often yield noisy detections composed of dispersed isolated islands. In this article, we propose a reconstruction method, named RSM, to improve subject-specific detections of predictive modeling approaches and in particular, binary classifiers. RSM specifically aims to reduce noise due to sampling error associated with using a finite sample of examples to train classifiers. The proposed method is a wrapper-type algorithm that can be used with different binary classifiers in a diagnostic manner, i.e. without information on condition presence. Reconstruction is posed as a Maximum-A-Posteriori problem with a prior model whose parameters are estimated from training data in a classifier-specific fashion. Experimental evaluation is performed on synthetically generated data and data from the Alzheimer's Disease Neuroimaging Initiative (ADNI) database. Results on synthetic data demonstrate that using RSM yields higher detection accuracy compared to using models directly or with bootstrap averaging. Analyses on the ADNI dataset show that RSM can also improve correlation between subject-specific detections in cortical thickness data and non-imaging markers of Alzheimer's Disease (AD), such as the Mini Mental State Examination Score and Cerebrospinal Fluid amyloid-$\beta$ levels. Further reliability studies on the longitudinal ADNI dataset show improvement on detection reliability when RSM is used.

##### Abstract (translated by Google)
当分析神经成像数据中与疾病相关的改变时，预测模型允许特定于受试者的推断。给定受试者的数据，可以在两个水平上进行推断：全局，即对象的识别条件存在，以及局部，即检测对从受试者数据中提取的每个单独测量的条件影响。虽然广泛使用全局推断，但是很少使用可用于形成特定于主题的效果图的局部推断，因为现有模型经常产生由分散的孤立岛组成的噪声检测。在本文中，我们提出了一种名为RSM的重建方法，以改进预测建模方法的主题特定检测，特别是二元分类器。 RSM专门旨在降低由于使用有限的示例样本来训练分类器而产生的采样误差引起的噪声。所提出的方法是包装类型算法，其可以以诊断方式与不同的二进制分类器一起使用，即，没有关于条件存在的信息。重建作为具有先验模型的最大后验问题提出，其参数是以分类器特定的方式从训练数据估计的。对来自阿尔茨海默氏病神经影像学倡议（ADNI）数据库的合成生成的数据和数据进行实验评估。合成数据的结果表明，与直接使用模型或使用自举平均值相比，使用RSM可以获得更高的检测精度。对ADNI数据集的分析表明，RSM还可以改善皮质厚度数据中特定受试者检测与阿尔茨海默病（AD）非成像标志物之间的相关性，如迷你精神状态检查评分和脑脊液淀粉样蛋白 -  $ \ beta $水平。对纵向ADNI数据集的进一步可靠性研究表明，当使用RSM时，检测可靠性有所提高。

##### URL
[http://arxiv.org/abs/1701.02610](http://arxiv.org/abs/1701.02610)

##### PDF
[http://arxiv.org/pdf/1701.02610](http://arxiv.org/pdf/1701.02610)

