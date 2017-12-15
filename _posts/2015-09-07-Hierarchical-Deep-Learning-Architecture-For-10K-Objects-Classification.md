---
layout: post
title: "Hierarchical Deep Learning Architecture For 10K Objects Classification"
date: 2015-09-07 08:49:39
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Recognition
author: Atul Laxman Katole, Krishna Prasad Yellapragada, Amish Kumar Bedi, Sehaj Singh Kalra, Mynepalli Siva Chaitanya
mathjax: true
---

* content
{:toc}

##### Abstract
Evolution of visual object recognition architectures based on Convolutional Neural Networks & Convolutional Deep Belief Networks paradigms has revolutionized artificial Vision Science. These architectures extract & learn the real world hierarchical visual features utilizing supervised & unsupervised learning approaches respectively. Both the approaches yet cannot scale up realistically to provide recognition for a very large number of objects as high as 10K. We propose a two level hierarchical deep learning architecture inspired by divide & conquer principle that decomposes the large scale recognition architecture into root & leaf level model architectures. Each of the root & leaf level models is trained exclusively to provide superior results than possible by any 1-level deep learning architecture prevalent today. The proposed architecture classifies objects in two steps. In the first step the root level model classifies the object in a high level category. In the second step, the leaf level recognition model for the recognized high level category is selected among all the leaf models. This leaf level model is presented with the same input object image which classifies it in a specific category. Also we propose a blend of leaf level models trained with either supervised or unsupervised learning approaches. Unsupervised learning is suitable whenever labelled data is scarce for the specific leaf level models. Currently the training of leaf level models is in progress; where we have trained 25 out of the total 47 leaf level models as of now. We have trained the leaf models with the best case top-5 error rate of 3.2% on the validation data set for the particular leaf models. Also we demonstrate that the validation error of the leaf level models saturates towards the above mentioned accuracy as the number of epochs are increased to more than sixty.

##### Abstract (translated by Google)
基于卷积神经网络和卷积深度信仰网络的视觉对象识别体系结构的演变已经使人工视觉科学发生了革命性的变化。这些架构分别利用有监督和无监督的学习方法来提取和学习真实世界的分层视觉特征。这两种方法都不能实际地放大以提供高达10K的大量物体的识别。我们提出了一个受分而治之原则启发的两级分层深度学习体系结构，将大规模识别体系结构分解为根叶级模型体系结构。根和叶级模型中的每一个都经过专门培训，以提供比目前普遍使用的任何1级深度学习架构可能的更好的结果。所提出的体系结构分两步对对象进行分类。在第一步中，根级模型将对象分类在高级别类别中。在第二步中，从所有叶子模型中选择用于识别的高级别类别的叶级识别模型。这个叶级模型被呈现为具有相同的输入对象图像，该图像将其分类在特定类别中。此外，我们提出了一个混合叶级模型与监督或无监督的学习方法的训练。无监督学习适用于特定叶级模型的标记数据稀缺。目前叶级模型的培训正在进行中;截至目前，我们已经在47个叶级模型中培训了25个模型。我们已经在特定叶模型的验证数据集上训练了具有3.2％最佳情况的最佳情况下的叶子模型3.2％。此外，我们证明叶面水平模型的验证误差随着时代的数量增加到60以上而达到上述准确度。

##### URL
[https://arxiv.org/abs/1509.01951](https://arxiv.org/abs/1509.01951)

##### PDF
[https://arxiv.org/pdf/1509.01951](https://arxiv.org/pdf/1509.01951)

