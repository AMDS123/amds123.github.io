---
layout: post
title: "Multi-level Activation for Segmentation of Hierarchically-nested Classes"
date: 2018-08-21 09:59:59
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Classification Relation
author: Marie Piraud, Anjany Sekuboyina, Bjoern H. Menze
mathjax: true
---

* content
{:toc}

##### Abstract
For many biological image segmentation tasks, including topological knowledge, such as the nesting of classes, can greatly improve results. However, most `out-of-the-box' CNN models are still blind to such prior information. In this paper, we propose a novel approach to encode this information, through a multi-level activation layer and three compatible losses. We benchmark all of them on nuclei segmentation in bright-field microscopy cell images from the 2018 Data Science Bowl challenge, offering an exemplary segmentation task with cells and nested subcellular structures. Our scheme greatly speeds up learning, and outperforms standard multi-class classification with soft-max activation and a previously proposed method stemming from it, improving the Dice score significantly (p-values&lt;0.007). Our approach is conceptually simple, easy to implement and can be integrated in any CNN architecture. It can be generalized to a higher number of classes, with or without further relations of containment.

##### Abstract (translated by Google)
对于许多生物图像分割任务，包括拓扑知识，如类的嵌套，可以大大提高结果。然而，大多数“开箱即用”的CNN模型仍然对此类先前信息视而不见。在本文中，我们提出了一种通过多级激活层和三个兼容损耗对这些信息进行编码的新方法。我们将所有这些基于来自2018年数据科学碗挑战的明视场显微镜细胞图像中的核分割进行基准测试，提供具有细胞和嵌套亚细胞结构的示例性分割任务。我们的方案极大地加速了学习，并且优于使用soft-max激活的标准多级分类以及由此产生的先前提出的方法，显着地改善了Dice分数（p值<0.007）。我们的方法在概念上简单，易于实现，并且可以集成到任何CNN架构中。它可以推广到更多的类，有或没有进一步的遏制关系。

##### URL
[http://arxiv.org/abs/1804.01910](http://arxiv.org/abs/1804.01910)

##### PDF
[http://arxiv.org/pdf/1804.01910](http://arxiv.org/pdf/1804.01910)

