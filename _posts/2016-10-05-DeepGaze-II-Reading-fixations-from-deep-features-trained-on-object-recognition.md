---
layout: post
title: "DeepGaze II: Reading fixations from deep features trained on object recognition"
date: 2016-10-05 18:47:28
categories: arXiv_CV
tags: arXiv_CV Salient Transfer_Learning Prediction Recognition
author: Matthias Kümmerer, Thomas S. A. Wallis, Matthias Bethge
mathjax: true
---

* content
{:toc}

##### Abstract
Here we present DeepGaze II, a model that predicts where people look in images. The model uses the features from the VGG-19 deep neural network trained to identify objects in images. Contrary to other saliency models that use deep features, here we use the VGG features for saliency prediction with no additional fine-tuning (rather, a few readout layers are trained on top of the VGG features to predict saliency). The model is therefore a strong test of transfer learning. After conservative cross-validation, DeepGaze II explains about 87% of the explainable information gain in the patterns of fixations and achieves top performance in area under the curve metrics on the MIT300 hold-out benchmark. These results corroborate the finding from DeepGaze I (which explained 56% of the explainable information gain), that deep features trained on object recognition provide a versatile feature space for performing related visual tasks. We explore the factors that contribute to this success and present several informative image examples. A web service is available to compute model predictions at this http URL

##### Abstract (translated by Google)
在这里，我们介绍DeepGaze II，一种预测人们在图像中看什么的模型。该模型使用经过训练的VGG-19深度神经网络的特征来识别图像中的物体。与使用深度特征的其他显着性模型相​​反，这里我们使用VGG特征来进行显着性预测，而不需要额外的微调（而是在VGG特征之上训练一些读出层以预测显着性）。因此这个模型是一个转移学习的强大测试。在保守的交叉验证之后，DeepGaze II解释了在固定模式中约87％的可解释的信息增益，并且在MIT300持有基准的曲线度量下达到了最高性能。这些结果证实了DeepGaze I（解释了56％的可解释的信息增益）的发现，深入的物体识别训练提供了执行相关视觉任务的多功能特征空间。我们探索促成这一成功的因素，并提供几个信息丰富的图像示例。 Web服务可用于在此URL处计算模型预测

##### URL
[https://arxiv.org/abs/1610.01563](https://arxiv.org/abs/1610.01563)

##### PDF
[https://arxiv.org/pdf/1610.01563](https://arxiv.org/pdf/1610.01563)

