---
layout: post
title: "Co-training for Demographic Classification Using Deep Learning from Label Proportions"
date: 2017-09-13 02:06:19
categories: arXiv_CV
tags: arXiv_CV Regularization Text_Classification Classification Deep_Learning
author: Ehsan Mohammady Ardehaly, Aron Culotta
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning algorithms have recently produced state-of-the-art accuracy in many classification tasks, but this success is typically dependent on access to many annotated training examples. For domains without such data, an attractive alternative is to train models with light, or distant supervision. In this paper, we introduce a deep neural network for the Learning from Label Proportion (LLP) setting, in which the training data consist of bags of unlabeled instances with associated label distributions for each bag. We introduce a new regularization layer, Batch Averager, that can be appended to the last layer of any deep neural network to convert it from supervised learning to LLP. This layer can be implemented readily with existing deep learning packages. To further support domains in which the data consist of two conditionally independent feature views (e.g. image and text), we propose a co-training algorithm that iteratively generates pseudo bags and refits the deep LLP model to improve classification accuracy. We demonstrate our models on demographic attribute classification (gender and race/ethnicity), which has many applications in social media analysis, public health, and marketing. We conduct experiments to predict demographics of Twitter users based on their tweets and profile image, without requiring any user-level annotations for training. We find that the deep LLP approach outperforms baselines for both text and image features separately. Additionally, we find that co-training algorithm improves image and text classification by 4% and 8% absolute F1, respectively. Finally, an ensemble of text and image classifiers further improves the absolute F1 measure by 4% on average.

##### Abstract (translated by Google)
深度学习算法最近在许多分类任务中产生了最新的精确度，但是这种成功通常取决于对许多注释训练样例的访问。对于没有这些数据的领域，一个有吸引力的选择是用轻型或遥远的监督来训练模型。在本文中，我们引入了一个深度学习标签比例（LLP）设置的神经网络，其中训练数据由袋子的未标记实例和每个袋子的相关标签分布组成。我们引入了一个新的正则化层Batch Averager，它可以附加到任何深度神经网络的最后一层，将其从监督学习转换为LLP。现有的深度学习包可以很容易地实现这一层。为了进一步支持数据由两个有条件独立的特征视图（例如图像和文本）组成的域，我们提出了一种协同训练算法，迭代地生成伪袋并修改深LLP模型以提高分类准确性。我们在人口属性分类（性别和种族/民族）方面展示了我们的模型，在社交媒体分析，公共健康和营销方面有很多应用。我们根据Twitter用户的推特和个人资料图像进行实验，预测Twitter用户的人口统计数据，而不需要任何用户级别的培训注释。我们发现深度LLP方法分别优于文本和图像特征的基线。此外，我们发现协同训练算法分别提高了4％和8％的绝对F1的图像和文本分类。最后，文本和图像分类器的集合进一步提高了平均4％的绝对F1值。

##### URL
[https://arxiv.org/abs/1709.04108](https://arxiv.org/abs/1709.04108)

##### PDF
[https://arxiv.org/pdf/1709.04108](https://arxiv.org/pdf/1709.04108)

