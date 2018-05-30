---
layout: post
title: "Greedy Structure Learning of Hierarchical Compositional Models"
date: 2018-05-29 09:33:51
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation Transfer_Learning Optimization Classification Relation
author: Adam Kortylewski, Clemens Blumer, Andreas Morel-Forster, Thomas Vetter
mathjax: true
---

* content
{:toc}

##### Abstract
Learning the representation of an object in terms of individual parts and their spatial as well as hierarchical relation is a fundamental problem of vision. Existing approaches are limited by the need of segmented training data and prior knowledge of the object's geometry. In this paper, we overcome those limitations by integrating an explicit background model into the structure learning process. We formulate the structure learning as a hierarchical clustering process. Thereby, we iterate in an EM-type procedure between clustering image patches and using the clustered data for learning part models. The hierarchical clustering proceeds in a bottom-up manner, learning the parts of lower layers in the hierarchy first and subsequently composing them into higher-order parts. A final top-down process composes the learned hierarchical parts into a holistic object model. The key novelty of our approach is that we learn a background model that competes with the object model (the foreground) in explaining the training data. In this way, we integrate the foreground-background segmentation task into the structure learning process and therefore overcome the need for segmented training data. As a result, we can infer the number of layers in the hierarchy, the number of parts per layer and the foreground-background segmentation in a joint optimization process. We demonstrate the ability to learn semantically meaningful hierarchical compositional models from a small set of natural images of an object without detailed supervision. We show that the learned object models achieve state-of-the-art results when compared with other generative object models at object classification on a standard transfer learning dataset. The code and data used in this work are publicly available.

##### Abstract (translated by Google)
学习一个对象的表现形式，以个体部分及其空间和层次关系来看，是一个基本的视觉问题。现有方法受限于分割训练数据的需要以及对象几何的先验知识。在本文中，我们通过将明确的背景模型集成到结构学习过程中来克服这些限制。我们将结构学习制定为一个层次聚类过程。因此，我们在一个EM类型的过程中迭代图像修补程序的聚类和使用聚类数据学习零件模型。层次聚类以自下而上的方式进行，首先学习层次结构中较低层的部分，然后将它们组合为较高阶部分。最终的自顶向下过程将学习的分层部分组合为整体对象模型。我们的方法的关键新颖之处在于，我们学习了一个与对象模型（前景）竞争解释训练数据的背景模型。这样，我们将前景 - 背景分割任务整合到结构学习过程中，从而克服分割训练数据的需要。因此，我们可以推断层次结构中的层数，每层的部件数量以及联合优化过程中的前景背景分割。我们展示了从没有详细监督的对象的一小组自然图像中学习语义上有意义的层次组合模型的能力。我们表明，学习对象模型在标准传输学习数据集的对象分类上与其他生成对象模型进行比较时可获得最新的结果。本工作中使用的代码和数据是公开可用的。

##### URL
[http://arxiv.org/abs/1701.06171](http://arxiv.org/abs/1701.06171)

##### PDF
[http://arxiv.org/pdf/1701.06171](http://arxiv.org/pdf/1701.06171)

