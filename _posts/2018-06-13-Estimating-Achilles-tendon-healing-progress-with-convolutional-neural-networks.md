---
layout: post
title: "Estimating Achilles tendon healing progress with convolutional neural networks"
date: 2018-06-13 14:43:21
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative
author: Norbert Kapinski, Jakub Zielinski, Bartosz A. Borucki, Tomasz Trzcinski, Beata Ciszkowska-Lyson, Krzysztof S. Nowinski
mathjax: true
---

* content
{:toc}

##### Abstract
Quantitative assessment of a treatment progress in the Achilles tendon healing process - one of the most common musculoskeletal disorder in modern medical practice - is typically a long and complex process: multiple MRI protocols need to be acquired and analysed by radiology experts. In this paper, we propose to significantly reduce the complexity of this assessment using a novel method based on a pre-trained convolutional neural network. We first train our neural network on over 500,000 2D axial cross-sections from over 3000 3D MRI studies to classify MRI images as belonging to a healthy or injured class, depending on the patient's condition. We then take the outputs of modified pre-trained network and apply linear regression on the PCA-reduced space of the features to assess treatment progress. Our method allows to reduce up to 5-fold the amount of data needed to be registered during the MRI scan without any information loss. Furthermore, we are able to predict the healing process phase with equal accuracy to human experts in 3 out of 6 main criteria. Finally, contrary to the current approaches to regeneration assessment that rely on radiologist subjective opinion, our method allows to objectively compare different treatments methods which can lead to improved diagnostics and patient's recovery.

##### Abstract (translated by Google)
定量评估跟腱愈合过程中的治疗进程 - 现代医学实践中最常见的肌肉骨骼疾病之一 - 通常是一个漫长而复杂的过程：多种MRI方案需要由放射专家采集和分析。在本文中，我们建议使用基于预先训练的卷积神经网络的新方法来显着降低此评估的复杂性。我们首先训练我们的神经网络超过500,000二维轴横截面超过3000三维MRI研究分类MRI图像属于一个健康或受伤的类，取决于病人的情况。然后，我们采取修改的预先训练的网络的输出，并对PCA减少的特征空间进行线性回归以评估治疗进展。我们的方法可以将MRI扫描过程中需要注册的数据量降低5倍，而不会丢失任何信息。此外，我们能够在6个主要标准中的3个中以等同的准确度预测愈合过程阶段对人类专家。最后，与目前依靠放射科医师主观意见的再生评估方法相反，我们的方法允许客观比较不同的治疗方法，这些方法可以导致改进的诊断和患者恢复。

##### URL
[http://arxiv.org/abs/1806.05091](http://arxiv.org/abs/1806.05091)

##### PDF
[http://arxiv.org/pdf/1806.05091](http://arxiv.org/pdf/1806.05091)

