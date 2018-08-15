---
layout: post
title: "Treepedia 2.0: Applying Deep Learning for Large-scale Quantification of Urban Tree Cover"
date: 2018-08-14 15:34:22
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Deep_Learning
author: Bill Yang Cai, Xiaojiang Li, Ian Seiferling, Carlo Ratti
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in deep learning have made it possible to quantify urban metrics at fine resolution, and over large extents using street-level images. Here, we focus on measuring urban tree cover using Google Street View (GSV) images. First, we provide a small-scale labelled validation dataset and propose standard metrics to compare the performance of automated estimations of street tree cover using GSV. We apply state-of-the-art deep learning models, and compare their performance to a previously established benchmark of an unsupervised method. Our training procedure for deep learning models is novel; we utilize the abundance of openly available and similarly labelled street-level image datasets to pre-train our model. We then perform additional training on a small training dataset consisting of GSV images. We find that deep learning models significantly outperform the unsupervised benchmark method. Our semantic segmentation model increased mean intersection-over-union (IoU) from 44.10% to 60.42% relative to the unsupervised method and our end-to-end model decreased Mean Absolute Error from 10.04% to 4.67%. We also employ a recently developed method called gradient-weighted class activation map (Grad-CAM) to interpret the features learned by the end-to-end model. This technique confirms that the end-to-end model has accurately learned to identify tree cover area as key features for predicting percentage tree cover. Our paper provides an example of applying advanced deep learning techniques on a large-scale, geo-tagged and image-based dataset to efficiently estimate important urban metrics. The results demonstrate that deep learning models are highly accurate, can be interpretable, and can also be efficient in terms of data-labelling effort and computational resources.

##### Abstract (translated by Google)
深度学习的最新进展使得以精细分辨率和使用街道级图像在很大程度上量化城市度量成为可能。在这里，我们专注于使用谷歌街景（GSV）图像测量城市树木覆盖。首先，我们提供一个小规模的标记验证数据集，并提出标准指标，以比较使用GSV自动估算街道树木覆盖的性能。我们应用最先进的深度学习模型，并将其性能与之前建立的无监督方法基准进行比较。我们深度学习模型的培训程序是新颖的;我们利用丰富的公开可用和类似标记的街道级图像数据集来预先训练我们的模型。然后，我们对由GSV图像组成的小型训练数据集进行额外培训。我们发现深度学习模型明显优于无监督基准方法。我们的语义分割模型相对于无监督方法将平均交叉联合（IoU）从44.10％增加到60.42％，并且我们的端到端模型将平均绝对误差从10.04％降低到4.67％。我们还采用了最近开发的一种称为梯度加权类激活图（Grad-CAM）的方法来解释端到端模型所学习的特征。该技术证实端到端模型已经准确地学习识别树木覆盖区域作为预测百分比树木覆盖的关键特征。我们的论文提供了一个在大规模，地理标记和基于图像的数据集上应用高级深度学习技术的示例，以有效地估计重要的城市指标。结果表明，深度学习模型非常准确，可以解释，并且在数据标记工作和计算资源方面也可以是高效的。

##### URL
[http://arxiv.org/abs/1808.04754](http://arxiv.org/abs/1808.04754)

##### PDF
[http://arxiv.org/pdf/1808.04754](http://arxiv.org/pdf/1808.04754)

