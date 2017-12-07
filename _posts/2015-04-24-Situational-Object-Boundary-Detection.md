---
layout: post
title: "Situational Object Boundary Detection"
date: 2015-04-24 09:15:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Jasper Uijlings, Vittorio Ferrari
mathjax: true
---

* content
{:toc}

##### Abstract
Intuitively, the appearance of true object boundaries varies from image to image. Hence the usual monolithic approach of training a single boundary predictor and applying it to all images regardless of their content is bound to be suboptimal. In this paper we therefore propose situational object boundary detection: We first define a variety of situations and train a specialized object boundary detector for each of them using [Dollar and Zitnick 2013]. Then given a test image, we classify it into these situations using its context, which we model by global image appearance. We apply the corresponding situational object boundary detectors, and fuse them based on the classification probabilities. In experiments on ImageNet, Microsoft COCO, and Pascal VOC 2012 segmentation we show that our situational object boundary detection gives significant improvements over a monolithic approach. Additionally, our method substantially outperforms [Hariharan et al. 2011] on semantic contour detection on their SBD dataset.

##### Abstract (translated by Google)
直观上，真实物体边界的外观随图像而异。因此，通常单一的方法来训练一个单一的边界预测，并将其应用于所有图像，而不管其内容是不是最理想的。在本文中，我们因此提出了情景对象边界检测：我们首先定义各种情况，并使用[Dollar和Zitnick 2013]为每个情境训练专门的对象边界检测器。然后给出一个测试图像，我们使用它的上下文将它分类到这些情况下，我们通过全局图像外观进行建模。我们应用相应的情景物体边界检测器，并根据分类概率进行融合。在ImageNet，Microsoft COCO和Pascal VOC 2012分割的实验中，我们展示了我们的情景对象边界检测在整体方法上给出了显着的改进。另外，我们的方法大大优于[Hariharan et al。 2011]对他们的SBD数据集进行语义轮廓检测。

##### URL
[https://arxiv.org/abs/1504.06434](https://arxiv.org/abs/1504.06434)

##### PDF
[https://arxiv.org/pdf/1504.06434](https://arxiv.org/pdf/1504.06434)

