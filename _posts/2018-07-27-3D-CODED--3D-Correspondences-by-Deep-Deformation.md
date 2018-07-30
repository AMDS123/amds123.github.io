---
layout: post
title: "3D-CODED : 3D Correspondences by Deep Deformation"
date: 2018-07-27 09:06:24
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning
author: Thibault Groueix, Matthew Fisher, Vladimir G. Kim, Bryan C. Russell, Mathieu Aubry
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new deep learning approach for matching deformable shapes by introducing {\it Shape Deformation Networks} which jointly encode 3D shapes and correspondences. This is achieved by factoring the surface representation into (i) a template, that parameterizes the surface, and (ii) a learnt global feature vector that parameterizes the transformation of the template into the input surface. By predicting this feature for a new shape, we implicitly predict correspondences between this shape and the template. We show that these correspondences can be improved by an additional step which improves the shape feature by minimizing the Chamfer distance between the input and transformed template. We demonstrate that our simple approach improves on state-of-the-art results on the difficult FAUST-inter challenge, with an average correspondence error of 2.88cm. We show, on the TOSCA dataset, that our method is robust to many types of perturbations, and generalizes to non-human shapes. This robustness allows it to perform well on real unclean, meshes from the the SCAPE dataset.

##### Abstract (translated by Google)
我们提出了一种新的深度学习方法，通过引入{\ it Shape Deformation Networks}来匹配可变形状，它共同编码3D形状和对应关系。这是通过将表面表示分解为（i）模板来实现的，该模板使表面参数化，以及（ii）学习的全局特征向量，其参数化模板到输入表面的变换。通过为新形状预测此特征，我们隐式预测此形状与模板之间的对应关系。我们证明了这些对应关系可以通过一个额外的步骤来改进，该步骤通过最小化输入和转换模板之间的倒角距离来改善形状特征。我们证明了我们的简单方法改进了最困难的FAUST-inter挑战的最新结果，平均对应误差为2.88cm。我们在TOSCA数据集上显示，我们的方法对于许多类型的扰动是稳健的，并且推广到非人类形状。这种稳健性使其能够在SCAPE数据集的真实不洁净网格上表现良好。

##### URL
[http://arxiv.org/abs/1806.05228](http://arxiv.org/abs/1806.05228)

##### PDF
[http://arxiv.org/pdf/1806.05228](http://arxiv.org/pdf/1806.05228)

