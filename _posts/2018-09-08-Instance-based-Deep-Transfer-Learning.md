---
layout: post
title: "Instance-based Deep Transfer Learning"
date: 2018-09-08 08:34:14
categories: arXiv_CV
tags: arXiv_CV Image_Classification Transfer_Learning Classification Deep_Learning
author: Tianyang Wang, Jun Huan, Michelle Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep transfer learning has acquired significant research interest. It makes use of pre-trained models that are learned from a source domain, and utilizes these models for the tasks in a target domain. Model-based deep transfer learning is arguably the most frequently used method. However, very little work has been devoted to enhancing deep transfer learning by focusing on the influence of data. In this work, we propose an instance-based approach to improve deep transfer learning in target domain. Specifically, we choose a pre-trained model which is learned from a source domain, and utilize this model to estimate the influence of each training sample in a target domain. Then we optimize training data of the target domain by removing the training samples that will lower the performance of the pre-trained model. We then fine-tune the pre-trained model with the optimized training data in the target domain, or build a new model which can be initialized partially based on the pre-trained model, and fine-tune it with the optimized training data in the target domain. Using this approach, transfer learning can help deep learning models to learn more useful features. Extensive experiments demonstrate the effectiveness of our approach on further boosting deep learning models for typical high-level computer vision tasks, such as image classification.

##### Abstract (translated by Google)
深度转移学习获得了重要的研究兴趣。它利用从源域学习的预训练模型，并将这些模型用于目标域中的任务。基于模型的深度转移学习可以说是最常用的方法。然而，通过关注数据的影响，很少有人致力于加强深度转移学习。在这项工作中，我们提出了一种基于实例的方法来改进目标领域的深度转移学习。具体而言，我们选择从源域学习的预训练模型，并利用该模型来估计每个训练样本在目标域中的影响。然后，我们通过移除将降低预训练模型的性能的训练样本来优化目标域的训练数据。然后，我们使用目标域中的优化训练数据微调预训练模型，或者构建可以基于预训练模型部分初始化的新模型，并使用优化后的训练数据对其进行微调。目标域。使用这种方法，转移学习可以帮助深度学习模型学习更多有用的功能。大量实验证明了我们的方法在进一步推动典型高级计算机视觉任务（如图像分类）的深度学习模型方面的有效性。

##### URL
[http://arxiv.org/abs/1809.02776](http://arxiv.org/abs/1809.02776)

##### PDF
[http://arxiv.org/pdf/1809.02776](http://arxiv.org/pdf/1809.02776)

