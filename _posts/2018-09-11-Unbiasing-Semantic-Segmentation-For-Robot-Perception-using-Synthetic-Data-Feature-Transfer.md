---
layout: post
title: "Unbiasing Semantic Segmentation For Robot Perception using Synthetic Data Feature Transfer"
date: 2018-09-11 04:27:40
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Inference
author: Jonathan C Balloch, Varun Agrawal, Irfan Essa, Sonia Chernova
mathjax: true
---

* content
{:toc}

##### Abstract
Robot perception systems need to perform reliable image segmentation in real-time on noisy, raw perception data. State-of-the-art segmentation approaches use large CNN models and carefully constructed datasets; however, these models focus on accuracy at the cost of real-time inference. Furthermore, the standard semantic segmentation datasets are not large enough for training CNNs without augmentation and are not representative of noisy, uncurated robot perception data. We propose improving the performance of real-time segmentation frameworks on robot perception data by transferring features learned from synthetic segmentation data. We show that pretraining real-time segmentation architectures with synthetic segmentation data instead of ImageNet improves fine-tuning performance by reducing the bias learned in pretraining and closing the \textit{transfer gap} as a result. Our experiments show that our real-time robot perception models pretrained on synthetic data outperform those pretrained on ImageNet for every scale of fine-tuning data examined. Moreover, the degree to which synthetic pretraining outperforms ImageNet pretraining increases as the availability of robot data decreases, making our approach attractive for robotics domains where dataset collection is hard and/or expensive.

##### Abstract (translated by Google)
机器人感知系统需要在嘈杂的原始感知数据上实时执行可靠的图像分割。最先进的分割方法使用大型CNN模型和精心构建的数据集;然而，这些模型以实时推理为代价关注准确性。此外，标准语义分割数据集不足以在没有增强的情况下训练CNN并且不代表嘈杂，不准确的机器人感知数据。我们建议通过传递从合成分割数据中学习的特征来提高机器人感知数据的实时分割框架的性能。我们展示了使用合成分段数据而不是ImageNet的预训练实时分段架构，通过减少预训练和关闭\ textit {传输间隙}中学到的偏差来提高微调性能。我们的实验表明，我们对合成数据进行预训练的实时机器人感知模型的性能优于ImageNet上预先训练的所有微调数据。此外，随着机器人数据的可用性降低，合成预训练优于ImageNet预训练的程度增加，使得我们的方法对于数据集收集困难和/或昂贵的机器人领域具有吸引力。

##### URL
[http://arxiv.org/abs/1809.03676](http://arxiv.org/abs/1809.03676)

##### PDF
[http://arxiv.org/pdf/1809.03676](http://arxiv.org/pdf/1809.03676)

