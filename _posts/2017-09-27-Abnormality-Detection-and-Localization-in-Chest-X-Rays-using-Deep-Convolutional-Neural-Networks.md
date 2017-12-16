---
layout: post
title: "Abnormality Detection and Localization in Chest X-Rays using Deep Convolutional Neural Networks"
date: 2017-09-27 09:49:09
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Detection
author: Mohammad Tariqul Islam, Md Abdul Aowal, Ahmed Tahseen Minhaz, Khalid Ashraf
mathjax: true
---

* content
{:toc}

##### Abstract
Chest X-Rays (CXRs) are widely used for diagnosing abnormalities in the heart and lung area. Automatically detecting these abnormalities with high accuracy could greatly enhance real world diagnosis processes. Lack of standard publicly available dataset and benchmark studies, however, makes it difficult to compare various detection methods. In order to overcome these difficulties, we have used a publicly available Indiana CXR, JSRT and Shenzhen dataset and studied the performance of known deep convolutional network (DCN) architectures on different abnormalities. We find that the same DCN architecture doesn't perform well across all abnormalities. Shallow features or earlier layers consistently provide higher detection accuracy compared to deep features. We have also found ensemble models to improve classification significantly compared to single model. Combining these insight, we report the highest accuracy on chest X-Ray abnormality detection on these datasets. We find that for cardiomegaly detection, the deep learning method improves the accuracy by a staggering 17 percentage point compared to rule based methods. We applied the techniques to the problem of tuberculosis detection on a different dataset and achieved the highest accuracy. Our localization experiments using these trained classifiers show that for spatially spread out abnormalities like cardiomegaly and pulmonary edema, the network can localize the abnormalities successfully most of the time. One remarkable result of the cardiomegaly localization is that the heart and its surrounding region is most responsible for cardiomegaly detection, in contrast to the rule based models where the ratio of heart and lung area is used as the measure. We believe that through deep learning based classification and localization, we will discover many more interesting features in medical image diagnosis that are not considered traditionally.

##### Abstract (translated by Google)
胸部X射线（CXR）广泛用于诊断心脏和肺部的异常。以高精度自动检测这些异常可以大大提高现实世界的诊断过程。然而，缺乏标准的公开可用的数据集和基准研究使得难以比较各种检测方法。为了克服这些困难，我们使用了公开的印第安纳CXR，JSRT和深圳数据集，研究了已知的深度卷积网络（DCN）架构在不同异常情况下的性能。我们发现相同的DCN架构在所有异常情况下表现不佳。与深度特征相比，浅色特征或较早层可以始终如一地提供更高的检测精度。与单一模型相比，我们还发现了集合模型可以显着改善分类。结合这些见解，我们报告了这些数据集上胸部X光异常检测的最高准确性。我们发现，对于心脏巨大的检测，深度学习方法比基于规则的方法提高了17个百分点的精确度。我们将这些技术应用于不同数据集中的结核病检测问题，并取得了最高的准确度。我们使用这些训练分类器的本地化实验表明，对于心脏扩大和肺水肿等空间分布异常，网络可以在大多数时间成功定位异常。心脏局部定位的一个显着结果是心脏及其周围区域是心脏扩大检测的最主要负责人，而以心肺比值为准则的基于规则的模型则不同。我们相信，通过基于深度学习的分类和本地化，我们将发现更多有趣的医学图像诊断中不被认为是传统的特征。

##### URL
[https://arxiv.org/abs/1705.09850](https://arxiv.org/abs/1705.09850)

##### PDF
[https://arxiv.org/pdf/1705.09850](https://arxiv.org/pdf/1705.09850)

