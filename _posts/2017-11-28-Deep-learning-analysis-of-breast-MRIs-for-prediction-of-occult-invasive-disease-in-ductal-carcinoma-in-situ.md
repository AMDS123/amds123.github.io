---
layout: post
title: "Deep learning analysis of breast MRIs for prediction of occult invasive disease in ductal carcinoma in situ"
date: 2017-11-28 21:52:49
categories: arXiv_CV
tags: arXiv_CV Review CNN Deep_Learning
author: Zhe Zhu, Michael Harowicz, Jun Zhang, Ashirbani Saha, Lars J. Grimm, E.Shelley Hwang, Maciej A. Mazurowski
mathjax: true
---

* content
{:toc}

##### Abstract
Purpose: To determine whether deep learning-based algorithms applied to breast MR images can aid in the prediction of occult invasive disease following the di- agnosis of ductal carcinoma in situ (DCIS) by core needle biopsy. Material and Methods: In this institutional review board-approved study, we analyzed dynamic contrast-enhanced fat-saturated T1-weighted MRI sequences of 131 patients at our institution with a core needle biopsy-confirmed diagnosis of DCIS. The patients had no preoperative therapy before breast MRI and no prior history of breast cancer. We explored two different deep learning approaches to predict whether there was a hidden (occult) invasive component in the analyzed tumors that was ultimately detected at surgical excision. In the first approach, we adopted the transfer learning strategy, in which a network pre-trained on a large dataset of natural images is fine-tuned with our DCIS images. Specifically, we used the GoogleNet model pre-trained on the ImageNet dataset. In the second approach, we used a pre-trained network to extract deep features, and a support vector machine (SVM) that utilizes these features to predict the upstaging of the DCIS. We used 10-fold cross validation and the area under the ROC curve (AUC) to estimate the performance of the predictive models. Results: The best classification performance was obtained using the deep features approach with GoogleNet model pre-trained on ImageNet as the feature extractor and a polynomial kernel SVM used as the classifier (AUC = 0.70, 95% CI: 0.58- 0.79). For the transfer learning based approach, the highest AUC obtained was 0.53 (95% CI: 0.41-0.62). Conclusion: Convolutional neural networks could potentially be used to identify occult invasive disease in patients diagnosed with DCIS at the initial core needle biopsy.

##### Abstract (translated by Google)
目的：确定基于深度学习的算法是否应用于乳腺MR影像，可以帮助预测导管原位癌（DCIS）在钻芯活检后隐匿性侵袭性疾病。材料和方法：在这个机构审查委员会批准的研究中，我们分析了我们机构的131例患者的动态增强脂肪饱和T1加权MRI序列，核心穿刺活检确诊为DCIS。患者在乳房MRI前没有进行术前治疗，也没有乳腺癌史。我们探索了两种不同的深度学习方法，以预测最终在手术切除中检测到的分析肿瘤中是否存在隐藏的（隐匿的）侵入性成分。在第一种方法中，我们采用了转移学习策略，在这个策略中，我们用我们的DCIS图像对在自然图像的大数据集上预先训练的网络进行了微调。具体来说，我们使用在ImageNet数据集上预先训练的GoogleNet模型。在第二种方法中，我们使用预先训练好的网络来提取深度特征，以及使用这些特征来预测DCIS的升级的支持向量机（SVM）。我们使用10倍交叉验证和ROC曲线下面积（AUC）来估计预测模型的性能。结果：在ImageNet上预先训练的GoogleNet模型作为特征提取器和多项式核SVM作为分类器（AUC = 0.70,95％CI：0.58-0.79），使用深度特征方法获得最佳分类性能。对于基于转移学习的方法，获得的最高AUC是0.53（95％CI：0.41-0.62）。结论：卷积神经网络可能用于初步核心穿刺活检诊断为DCIS的隐匿性侵袭性疾病。

##### URL
[https://arxiv.org/abs/1711.10577](https://arxiv.org/abs/1711.10577)

