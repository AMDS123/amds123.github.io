---
layout: post
title: "Detection, Recognition and Tracking of Moving Objects from Real-time Video via Visual Vocabulary Model and Species Inspired PSO"
date: 2017-06-02 11:09:10
categories: arXiv_CV
tags: arXiv_CV Tracking Classification Detection Recognition
author: Kumar S. Ray, Anit Chakraborty, Sayandip Dutta
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we address the basic problem of recognizing moving objects in video images using Visual Vocabulary model and Bag of Words and track our object of interest in the subsequent video frames using species inspired PSO. Initially, the shadow free images are obtained by background modelling followed by foreground modeling to extract the blobs of our object of interest. Subsequently, we train a cubic SVM with human body datasets in accordance with our domain of interest for recognition and tracking. During training, using the principle of Bag of Words we extract necessary features of certain domains and objects for classification. Subsequently, matching these feature sets with those of the extracted object blobs that are obtained by subtracting the shadow free background from the foreground, we detect successfully our object of interest from the test domain. The performance of the classification by cubic SVM is satisfactorily represented by confusion matrix and ROC curve reflecting the accuracy of each module. After classification, our object of interest is tracked in the test domain using species inspired PSO. By combining the adaptive learning tools with the efficient classification of description, we achieve optimum accuracy in recognition of the moving objects. We evaluate our algorithm benchmark datasets: iLIDS, VIVID, Walking2, Woman. Comparative analysis of our algorithm against the existing state-of-the-art trackers shows very satisfactory and competitive results.

##### Abstract (translated by Google)
在本文中，我们使用Visual Vocabulary模型和Bag of Words来解决在视频图像中识别运动物体的基本问题，并在后续的使用物种启发的PSO的视频帧中追踪我们感兴趣的对象。最初，通过背景建模获得无阴影图像，然后进行前景建模，以提取感兴趣对象的斑点。随后，我们根据我们感兴趣的领域对人体数据集进行三维SVM训练，以进行识别和跟踪。在训练过程中，使用Bag of Words的原则，我们提取了某些领域和对象的必要特征进行分类。随后，将这些特征集合与通过从前景中减去无阴影背景而获得的提取的对象斑点的特征集合匹配，从测试域成功检测到我们感兴趣的对象。三维支持向量机的分类性能可以通过混淆矩阵和反映每个模块精度的ROC曲线来满意地表示。在分类之后，我们感兴趣的对象在使用物种启发的PSO的测试领域被跟踪。通过将自适应学习工具与高效描述分类相结合，我们实现了对运动物体识别的最佳精度。我们评估我们的算法基准数据集：iLIDS，VIVID，Walking2，Woman。我们的算法与现有的最先进的跟踪器的比较分析显示出非常满意的和有竞争力的结果。

##### URL
[https://arxiv.org/abs/1707.05224](https://arxiv.org/abs/1707.05224)

##### PDF
[https://arxiv.org/pdf/1707.05224](https://arxiv.org/pdf/1707.05224)

