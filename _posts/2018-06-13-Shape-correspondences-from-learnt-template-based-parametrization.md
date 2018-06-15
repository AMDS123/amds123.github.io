---
layout: post
title: "Shape correspondences from learnt template-based parametrization"
date: 2018-06-13 19:07:37
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning
author: Thibault Groueix, Matthew Fisher, Vladimir G. Kim, Bryan C. Russell, Mathieu Aubry
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new deep learning approach for matching deformable shapes by using a model which jointly encodes 3D shapes and correspondences. This is achieved by factoring the surface representation into (i) a template, that parameterizes the surface, and (ii) a learnt feature vector that parameterizes the function which transforms the template into the input surface. We show that our network can directly predict the feature vector and thus correspondences for a new input shape, but also that correspondence quality can be significantly improved by an additional regression step. This additional step improves the shape feature vector by minimizing the Chamfer distance between the input and parameterized shape. We show that this produces both a better shape representation and better correspondences. We demonstrate that our simple approach improves state of the art results on the difficult FAUST inter challenge, with an average correspondence error of 2.88cm. We also show results on the real scans from the SCAPE dataset and the synthetically perturbed shapes from the TOSCA dataset, including non-human shapes.

##### Abstract (translated by Google)
我们提出了一种新的深度学习方法，通过使用联合编码3D形状和对应关系的模型匹配可变形形状。这是通过将表面表示分解为（i）模板，表面参数化和（ii）参数化将模板转换为输入表面的函数的学习特征向量来实现的。我们表明，我们的网络可以直接预测特征向量，从而直接预测新输入形状的对应关系，但通过额外的回归步骤可以显着提高通信质量。这个附加步骤通过最小化输入参数化形状之间的倒角距离来改善形状特征向量。我们表明，这产生了一个更好的形状表示和更好的对应关系。我们证明，我们的简单方法改善了困难FAUST相互挑战的最先进结果，平均对应误差为2.88厘米。我们还展示了来自SCAPE数据集的实际扫描结果以及来自TOSCA数据集的合成扰动形状（包括非人体形状）的结果。

##### URL
[http://arxiv.org/abs/1806.05228](http://arxiv.org/abs/1806.05228)

##### PDF
[http://arxiv.org/pdf/1806.05228](http://arxiv.org/pdf/1806.05228)

