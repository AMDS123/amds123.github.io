---
layout: post
title: "Beyond the Pixel-Wise Loss for Topology-Aware Delineation"
date: 2017-12-06 14:03:51
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Agata Mosinska, Pablo Marquez-Neila, Mateusz Kozinski, Pascal Fua
mathjax: true
---

* content
{:toc}

##### Abstract
Delineation of curvilinear structures is an important problem in Computer Vision with multiple practical applications. With the advent of Deep Learning, many current approaches on automatic delineation have focused on finding more powerful deep architectures, but have continued using the habitual pixel-wise losses such as binary cross-entropy. In this paper we claim that pixel-wise losses alone are unsuitable for this problem because of their inability to reflect the topological impact of mistakes in the final prediction. We propose a new loss term that is aware of the higher-order topological features of linear structures. We also introduce a refinement pipeline that iteratively applies the same model over the previous delineation to refine the predictions at each step while keeping the number of parameters and the complexity of the model constant. 
 When combined with the standard pixel-wise loss, both our new loss term and our iterative refinement boost the quality of the predicted delineations, in some cases almost doubling the accuracy as compared to the same classifier trained with the binary cross-entropy alone. We show that our approach outperforms state-of-the-art methods on a wide range of data, from microscopy to aerial images.

##### Abstract (translated by Google)
曲线结构的划分是计算机视觉中的一个重要问题，具有多种实际应用。随着深度学习的出现，许多目前的自动划分方法都集中在寻找更强大的深层架构，但是仍然继续使用像二进制交叉熵那样的习惯像素方面的损失。在本文中，我们声称像素方面的损失本身并不适合这个问题，因为它们无法反映最终预测中错误的拓扑效应。我们提出了一个新的损失项，意识到线性结构的高阶拓扑特征。我们还引入了一个细化流水线，该流水线迭代地将相同的模型应用于以前的描述，以在每个步骤中细化预测，同时保持参数的数量和模型的复杂性不变。
 当与标准像素损失相结合时，我们的新损失项和我们的迭代细化都提高了预测轮廓的质量，在某些情况下，与仅用二元交叉熵训练的相同分类器相比，在某些情况下精度几乎翻倍。我们表明，我们的方法胜过了从显微镜到航空影像等各种数据的最先进的方法。

##### URL
[http://arxiv.org/abs/1712.02190](http://arxiv.org/abs/1712.02190)

##### PDF
[http://arxiv.org/pdf/1712.02190](http://arxiv.org/pdf/1712.02190)

