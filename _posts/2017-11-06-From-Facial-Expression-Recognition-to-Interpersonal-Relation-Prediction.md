---
layout: post
title: "From Facial Expression Recognition to Interpersonal Relation Prediction"
date: 2017-11-06 06:04:13
categories: arXiv_CV
tags: arXiv_CV Face Prediction Relation Recognition
author: Zhanpeng Zhang, Ping Luo, Chen Change Loy, Xiaoou Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Interpersonal relation defines the association, e.g., warm, friendliness, and dominance, between two or more people. Motivated by psychological studies, we investigate if such fine-grained and high-level relation traits can be characterized and quantified from face images in the wild. We address this challenging problem by first studying a deep network architecture for robust recognition of facial expressions. Unlike existing models that typically learn from facial expression labels alone, we devise an effective multitask network that is capable of learning from rich auxiliary attributes such as gender, age, and head pose, beyond just facial expression data. While conventional supervised training requires datasets with complete labels (e.g., all samples must be labeled with gender, age, and expression), we show that this requirement can be relaxed via a novel attribute propagation method. The approach further allows us to leverage the inherent correspondences between heterogeneous attribute sources despite the disparate distributions of different datasets. With the network we demonstrate state-of-the-art results on existing facial expression recognition benchmarks. To predict inter-personal relation, we use the expression recognition network as branches for a Siamese model. Extensive experiments show that our model is capable of mining mutual context of faces for accurate fine-grained interpersonal prediction.

##### Abstract (translated by Google)
人际关系定义了两个或两个以上人之间的联系，例如温暖，友善和主导。在心理学研究的驱动下，我们研究了这种细粒度和高层次的关系特征是否可以从野外的人脸图像中进行表征和量化。我们首先研究深度网络体系结构，以强健识别面部表情，从而解决这个具有挑战性的问题与通常仅从面部表情标签学习的现有模型不同，我们设计出有效的多任务网络，能够从诸如性别，年龄和头部姿势等丰富的辅助属性中学习，而不仅仅是面部表情数据。虽然传统的监督训练需要具有完整标签的数据集（例如，所有样本必须标有性别，年龄和表达），但是我们表明可以通过新的属性传播方法来放松这个要求。这种方法进一步使我们能够利用异构属性源之间的固有对应关系，尽管不同数据集的分布是不同的。通过网络，我们在现有的面部表情识别基准上展示了最新的结果。为了预测人际关系，我们使用表达式识别网络作为连接模型的分支。大量的实验表明，我们的模型能够挖掘人脸的相互关系，进行准确的细粒度人际预测。

##### URL
[https://arxiv.org/abs/1609.06426](https://arxiv.org/abs/1609.06426)

##### PDF
[https://arxiv.org/pdf/1609.06426](https://arxiv.org/pdf/1609.06426)

