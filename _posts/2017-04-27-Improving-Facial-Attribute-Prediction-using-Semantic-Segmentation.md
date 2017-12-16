---
layout: post
title: "Improving Facial Attribute Prediction using Semantic Segmentation"
date: 2017-04-27 20:41:50
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Face Semantic_Segmentation Prediction Recognition
author: Mahdi M. Kalayeh, Boqing Gong, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
Attributes are semantically meaningful characteristics whose applicability widely crosses category boundaries. They are particularly important in describing and recognizing concepts where no explicit training example is given, \textit{e.g., zero-shot learning}. Additionally, since attributes are human describable, they can be used for efficient human-computer interaction. In this paper, we propose to employ semantic segmentation to improve facial attribute prediction. The core idea lies in the fact that many facial attributes describe local properties. In other words, the probability of an attribute to appear in a face image is far from being uniform in the spatial domain. We build our facial attribute prediction model jointly with a deep semantic segmentation network. This harnesses the localization cues learned by the semantic segmentation to guide the attention of the attribute prediction to the regions where different attributes naturally show up. As a result of this approach, in addition to recognition, we are able to localize the attributes, despite merely having access to image level labels (weak supervision) during training. We evaluate our proposed method on CelebA and LFWA datasets and achieve superior results to the prior arts. Furthermore, we show that in the reverse problem, semantic face parsing improves when facial attributes are available. That reaffirms the need to jointly model these two interconnected tasks.

##### Abstract (translated by Google)
属性是语义上有意义的特性，其适用性广泛地跨越类别边界。它们在描述和识别没有给出显式训练例子的概念（例如，零点学习）时是特别重要的。此外，由于属性是人类可以描述的，所以它们可以用于高效的人机交互。在本文中，我们建议使用语义分割来改善面部属性预测。其核心思想在于，许多面部属性描述的是本地属性。换句话说，属性出现在人脸图像中的概率在空间域上远非统一。我们与一个深层的语义分割网络联合建立我们的面部属性预测模型。利用语义分割学习的定位线索，将属性预测的注意力引导到不同属性自然显现的区域。作为这种方法的结果，除了识别之外，尽管仅仅在训练期间能够访问图像级别标签（弱监督），我们也能够对属性进行本地化。我们评估我们在CelebA和LFWA数据集上提出的方法，并获得优于现有技术的结果。此外，我们表明，在相反的问题，面部属性可用时，语义面部解析得到改善。这再次确认需要共同模拟这两个相互关联的任务。

##### URL
[https://arxiv.org/abs/1704.08740](https://arxiv.org/abs/1704.08740)

##### PDF
[https://arxiv.org/pdf/1704.08740](https://arxiv.org/pdf/1704.08740)

