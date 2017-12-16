---
layout: post
title: "Extraction of airway trees using multiple hypothesis tracking and template matching"
date: 2016-11-24 10:42:07
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Tracking
author: Raghavendra Selvan, Jens Petersen, Jesper H. Pedersen, Marleen de Bruijne
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge of airway tree morphology has important clinical applications in diagnosis of chronic obstructive pulmonary disease. We present an automatic tree extraction method based on multiple hypothesis tracking and template matching for this purpose and evaluate its performance on chest CT images. The method is adapted from a semi-automatic method devised for vessel segmentation. Idealized tubular templates are constructed that match airway probability obtained from a trained classifier and ranked based on their relative significance. Several such regularly spaced templates form the local hypotheses used in constructing a multiple hypothesis tree, which is then traversed to reach decisions. The proposed modifications remove the need for local thresholding of hypotheses as decisions are made entirely based on statistical comparisons involving the hypothesis tree. The results show improvements in performance when compared to the original method and region growing on intensity images. We also compare the method with region growing on the probability images, where the presented method does not show substantial improvement, but we expect it to be less sensitive to local anomalies in the data.

##### Abstract (translated by Google)
气道树形态学知识在慢性阻塞性肺疾病诊断中具有重要的临床应用价值。我们提出了一种基于多重假设跟踪和模板匹配的自动树提取方法，以此评估其在胸部CT图像上的表现。该方法适用于为血管分割设计的半自动方法。构建理想化的管状模板，其匹配从经训练的分类器获得的气道概率，并基于其相对重要性进行排序。几个这种规则间隔的模板构成了用于构建多重假设树的局部假设，然后遍历它们以作出决定。所提出的修改不需要对假设进行局部阈值化，因为完全基于涉及假设树的统计比较来做出决定。与原始方法和区域在强度图像上的增长相比，结果表现出性能的改善。我们还将该方法与区域增长的概率图像进行比较，其中所提出的方法没有显示出实质性的改善，但是我们预期它对数据中的局部异常不那么敏感。

##### URL
[https://arxiv.org/abs/1611.08131](https://arxiv.org/abs/1611.08131)

##### PDF
[https://arxiv.org/pdf/1611.08131](https://arxiv.org/pdf/1611.08131)

