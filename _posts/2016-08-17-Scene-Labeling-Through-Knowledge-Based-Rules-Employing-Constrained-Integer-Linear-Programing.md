---
layout: post
title: "Scene Labeling Through Knowledge-Based Rules Employing Constrained Integer Linear Programing"
date: 2016-08-17 21:14:51
categories: arXiv_CV
tags: arXiv_CV Knowledge Inference Classification
author: Nasim Souly, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Scene labeling task is to segment the image into meaningful regions and categorize them into classes of objects which comprised the image. Commonly used methods typically find the local features for each segment and label them using classifiers. Afterward, labeling is smoothed in order to make sure that neighboring regions receive similar labels. However, they ignore expressive and non-local dependencies among regions due to expensive training and inference. In this paper, we propose to use high-level knowledge regarding rules in the inference to incorporate dependencies among regions in the image to improve scores of classification. Towards this aim, we extract these rules from data and transform them into constraints for Integer Programming to optimize the structured problem of assigning labels to super-pixels (consequently pixels) of an image. In addition, we propose to use soft-constraints in some scenarios, allowing violating the constraint by imposing a penalty, to make the model more flexible. We assessed our approach on three datasets and obtained promising results.

##### Abstract (translated by Google)
场景标记任务是将图像分割成有意义的区域，并将它们分类为构成图像的对象类别。通常使用的方法通常为每个片段找到局部特征，并使用分类器对它们进行标记。之后，对标签进行平滑处理，以确保邻近地区收到类似的标签。但是，由于昂贵的培训和推理，他们忽略了地区之间的表达性和非地方性依赖性。在本文中，我们建议在推理中使用关于规则的高层次的知识来结合图像中的区域之间的依赖关系来提高分类的分数。为了达到这个目的，我们从数据中提取这些规则，并将它们转换成整数规划的约束条件，以优化将标签分配给图像的超像素（因此像素）的结构化问题。另外，我们建议在一些场景中使用软约束，允许通过施加惩罚来违反约束条件，使得模型更加灵活。我们在三个数据集上评估了我们的方法并获得了可喜的结果

##### URL
[https://arxiv.org/abs/1608.05104](https://arxiv.org/abs/1608.05104)

##### PDF
[https://arxiv.org/pdf/1608.05104](https://arxiv.org/pdf/1608.05104)

