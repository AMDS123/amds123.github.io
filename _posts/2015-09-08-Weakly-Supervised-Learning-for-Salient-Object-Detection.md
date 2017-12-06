---
layout: post
title: "Weakly Supervised Learning for Salient Object Detection"
date: 2015-09-08 13:34:24
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Detection
author: Huaizu Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in supervised salient object detection has resulted in significant performance on benchmark datasets. Training such models, however, requires expensive pixel-wise annotations of salient objects. Moreover, many existing salient object detection models assume that at least one salient object exists in the input image. Such an assumption often leads to less appealing saliency maps on the background images, which contain no salient object at all. To avoid the requirement of expensive pixel-wise salient region annotations, in this paper, we study weakly supervised learning approaches for salient object detection. Given a set of background images and salient object images, we propose a solution toward jointly addressing the salient object existence and detection tasks. We adopt the latent SVM framework and formulate the two problems together in a single integrated objective function: saliency labels of superpixels are modeled as hidden variables and involved in a classification term conditioned to the salient object existence variable, which in turn depends on both global image and regional saliency features and saliency label assignment. Experimental results on benchmark datasets validate the effectiveness of our proposed approach.

##### Abstract (translated by Google)
监督显着对象检测的最新进展已经在基准数据集上产生了显着的性能。然而，培训这样的模型需要昂贵的像素明智的对象注释。此外，许多现有的显着物体检测模型假定输入图像中存在至少一个显着物体。这样的假设通常会导致背景图像上的吸引力较小的显着图，其根本不包含显着对象。为了避免昂贵的逐像素显着区域注释的需求，本文研究弱监督学习方法对显着物体检测。给定一组背景图像和显着物体图像，提出共同解决显着目标存在和检测任务的解决方案。我们采用潜在的支持向量机框架，并将这两个问题一起制定在一个单一的综合目标函数中：超像素的显着性标签被建模为隐变量，并涉及一个以显着对象存在变量为条件的分类术语，这又依赖于全局图像区域显着特征和显着性标签分配。基准数据集的实验结果验证了我们提出的方法的有效性。

##### URL
[https://arxiv.org/abs/1501.07492](https://arxiv.org/abs/1501.07492)

