---
layout: post
title: "Online local pool generation for dynamic classifier selection: an extended version"
date: 2018-09-05 17:13:02
categories: arXiv_AI
tags: arXiv_AI Classification Relation Recognition
author: Mariana A. Souza, George D. C. Cavalcanti, Rafael M. O. Cruz, Robert Sabourin
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic Classifier Selection (DCS) techniques have difficulty in selecting the most competent classifier in a pool, even when its presence is assured. Since the DCS techniques rely only on local data to estimate a classifier's competence, the manner in which the pool is generated could affect the choice of the best classifier for a given sample. That is, the global perspective in which pools are generated may not help the DCS techniques in selecting a competent classifier for samples that are likely to be mislabelled. Thus, we propose in this work an online pool generation method that produces a locally accurate pool for test samples in difficult regions of the feature space. The difficulty of a given area is determined by the classification difficulty of the samples in it. That way, by using classifiers that were generated in a local scope, it could be easier for the DCS techniques to select the best one for the difficult samples. For the query samples in easy regions, a simple nearest neighbors rule is used. In the extended version of this work, a deep analysis on the correlation between instance hardness and the performance of DCS techniques is presented. An instance hardness measure that conveys the degree of local class overlap is then used to decide when the local pool is used in the proposed scheme. The proposed method yielded significantly greater recognition rates in comparison to a Bagging-generated pool and two other global pool generation schemes for all DCS techniques evaluated. The proposed scheme's performance was also significantly superior to three state-of-the-art classification models and statistically equivalent to five of them. Moreover, an extended analysis on the computational complexity of the proposed method and of several DS techniques is presented in this version. We also provide the implementation of the proposed technique using the DESLib library on GitHub.

##### Abstract (translated by Google)
动态分类器选择（DCS）技术难以选择池中最有能力的分类器，即使其存在得到保证。由于DCS技术仅依赖于本地数据来估计分类器的能力，因此生成池的方式可能影响给定样本的最佳分类器的选择。也就是说，生成池的全局视角可能无助于DCS技术为可能被错误标记的样本选择合格的分类器。因此，我们在这项工作中提出了一种在线池生成方法，该方法为特征空间的困难区域中的测试样本生成局部精确池。给定区域的难度取决于其中样本的分类难度。这样，通过使用在局部范围内生成的分类器，DCS技术可以更容易地为困难样本选择最佳的分类器。对于简易区域中的查询样本，使用简单的最近邻规则。在这项工作的扩展版本中，深入分析了实例硬度与DCS技术性能之间的相关性。然后使用传达本地类重叠程度的实例硬度度量来确定何时在所提出的方案中使用本地池。与Bagging生成的池和所有评估的所有DCS技术的其他两个全局池生成方案相比，所提出的方法产生了显着更高的识别率。拟议方案的表现也明显优于三种最先进的分类模型，统计上相当于其中五种。此外，本版本还提供了对所提方法和几种DS技术的计算复杂性的扩展分析。我们还使用GitHub上的DESLib库提供了所提议技术的实现。

##### URL
[http://arxiv.org/abs/1809.01628](http://arxiv.org/abs/1809.01628)

##### PDF
[http://arxiv.org/pdf/1809.01628](http://arxiv.org/pdf/1809.01628)

