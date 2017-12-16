---
layout: post
title: "SurvivalNet: Predicting patient survival from diffusion weighted magnetic resonance images using cascaded fully convolutional and 3D convolutional neural networks"
date: 2017-02-20 12:05:30
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification
author: Patrick Ferdinand Christ, Florian Ettlinger, Georgios Kaissis, Sebastian Schlecht, Freba Ahmaddy, Felix Grün, Alexander Valentinitsch, Seyed-Ahmad Ahmadi, Rickmer Braren, Bjoern Menze
mathjax: true
---

* content
{:toc}

##### Abstract
Automatic non-invasive assessment of hepatocellular carcinoma (HCC) malignancy has the potential to substantially enhance tumor treatment strategies for HCC patients. In this work we present a novel framework to automatically characterize the malignancy of HCC lesions from DWI images. We predict HCC malignancy in two steps: As a first step we automatically segment HCC tumor lesions using cascaded fully convolutional neural networks (CFCN). A 3D neural network (SurvivalNet) then predicts the HCC lesions' malignancy from the HCC tumor segmentation. We formulate this task as a classification problem with classes being "low risk" and "high risk" represented by longer or shorter survival times than the median survival. We evaluated our method on DWI of 31 HCC patients. Our proposed framework achieves an end-to-end accuracy of 65% with a Dice score for the automatic lesion segmentation of 69% and an accuracy of 68% for tumor malignancy classification based on expert annotations. We compared the SurvivalNet to classical handcrafted features such as Histogram and Haralick and show experimentally that SurvivalNet outperforms the handcrafted features in HCC malignancy classification. End-to-end assessment of tumor malignancy based on our proposed fully automatic framework corresponds to assessment based on expert annotations with high significance (p>0.95).

##### Abstract (translated by Google)
对肝细胞癌（HCC）恶性肿瘤的自动无创评估有可能大大增强HCC患者的肿瘤治疗策略。在这项工作中，我们提出了一个新的框架，自动表征从DWI图像肝癌病变的恶性程度。我们预测HCC恶性肿瘤分两步：第一步，我们使用级联完全卷积神经网络（CFCN）自动分割HCC肿瘤病灶。然后，3D神经网络（SurvivalNet）预测HCC肿瘤分化的HCC病变的恶性程度。我们将这个任务作为一个分类问题来制定，分类问题的类别是“低风险”和“高风险”，以比中位数生存期更长或更短的生存时间表示。我们评估了31例HCC患者DWI的方法。我们提出的框架实现了65％的端对端准确性，自动病灶分割的Dice评分为69％，基于专家注释的肿瘤恶性分类的准确率为68％。我们将SurvivalNet与直方图和Haralick等经典手工功能进行了比较，并通过实验显示SurvivalNet在HCC恶性分类中胜过手工特征。基于我们提出的全自动框架的肿瘤恶性肿瘤端到端评估对应于基于专家注释的高评估评估（p> 0.95）。

##### URL
[https://arxiv.org/abs/1702.05941](https://arxiv.org/abs/1702.05941)

##### PDF
[https://arxiv.org/pdf/1702.05941](https://arxiv.org/pdf/1702.05941)

