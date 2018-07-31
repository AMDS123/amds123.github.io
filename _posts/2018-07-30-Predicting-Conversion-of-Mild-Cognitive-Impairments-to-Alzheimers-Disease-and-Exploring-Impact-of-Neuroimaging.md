---
layout: post
title: "Predicting Conversion of Mild Cognitive Impairments to Alzheimer's Disease and Exploring Impact of Neuroimaging"
date: 2018-07-30 08:39:47
categories: arXiv_CV
tags: arXiv_CV Embedding Deep_Learning Prediction
author: Yaroslav Shmulev, Mikhail Belyaev
mathjax: true
---

* content
{:toc}

##### Abstract
Nowadays, a lot of scientific efforts are concentrated on the diagnosis of Alzheimer's Disease (AD) applying deep learning methods to neuroimaging data. Even for 2017, there were published more than a hundred papers dedicated to AD diagnosis, whereas only a few works considered a problem of mild cognitive impairments (MCI) conversion to the AD. However, the conversion prediction is an important problem since approximately 15% of patients with MCI converges to the AD every year. In the current work, we are focusing on the conversion prediction using brain Magnetic Resonance Imaging and clinical data, such as demographics, cognitive assessments, genetic, and biochemical markers. First of all, we applied state-of-the-art deep learning algorithms on the neuroimaging data and compared these results with two machine learning algorithms that we fit using the clinical data. As a result, the models trained on the clinical data outperform the deep learning algorithms applied to the MR images. To explore the impact of neuroimaging further, we trained a deep feed-forward embedding using similarity learning with Histogram loss on all available MRIs and obtained 64-dimensional vector representation of neuroimaging data. The use of learned representation from the deep embedding allowed to increase the quality of prediction based on the neuroimaging. Finally, the current results on this dataset show that the neuroimaging does affect conversion prediction, however, cannot noticeably increase the quality of the prediction. The best results of predicting MCI-to-AD conversion are provided by XGBoost algorithm trained on the clinical and embedding data. The resulting accuracy is 0.76 +- 0.01 and the area under the ROC curve - 0.86 +- 0.01.

##### Abstract (translated by Google)
如今，许多科学研究都集中在诊断阿尔茨海默病（AD），将深度学习方法应用于神经影像学数据。即使在2017年，也发表了超过100篇专门用于AD诊断的论文，而只有少数作品被认为是轻度认知障碍（MCI）转化为AD的问题。然而，转换预测是一个重要问题，因为大约15％的MCI患者每年收敛于AD。在目前的工作中，我们专注于使用脑磁共振成像和临床数据进行转换预测，例如人口统计学，认知评估，遗传和生化标记。首先，我们在神经影像数据上应用了最先进的深度学习算法，并将这些结果与我们使用临床数据拟合的两种机器学习算法进行了比较。结果，在临床数据上训练的模型优于应用于MR图像的深度学习算法。为了进一步探索神经影像学的影响，我们使用相似学习和所有可用MRI的直方图损失训练深度前馈嵌入，并获得神经影像数据的64维矢量表示。使用来自深度嵌入的学习表示允许基于神经成像来提高预测的质量。最后，该数据集的当前结果显示神经影像确实影响转换预测，但是，不能显着提高预测的质量。预测MCI到AD转换的最佳结果由在临床和嵌入数据上训练的XGBoost算法提供。得到的精度为0.76±0.01，ROC曲线下的面积为0.86±0.01。

##### URL
[http://arxiv.org/abs/1807.11228](http://arxiv.org/abs/1807.11228)

##### PDF
[http://arxiv.org/pdf/1807.11228](http://arxiv.org/pdf/1807.11228)

