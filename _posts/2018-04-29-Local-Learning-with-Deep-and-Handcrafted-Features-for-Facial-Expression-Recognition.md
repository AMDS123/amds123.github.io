---
layout: post
title: "Local Learning with Deep and Handcrafted Features for Facial Expression Recognition"
date: 2018-04-29 09:12:13
categories: arXiv_CV
tags: arXiv_CV Sparse Knowledge CNN Recognition
author: Mariana-Iuliana Georgescu, Radu Tudor Ionescu, Marius Popescu
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach that combines automatic features learned by convolutional neural networks (CNN) and handcrafted features computed by the bag-of-visual-words (BOVW) model in order to achieve state-of-the-art results in facial expression recognition. In order to obtain automatic features, we experiment with multiple CNN architectures, pre-trained models and training procedures, e.g. Dense-Sparse-Dense. After fusing the two types of features, we employ a local learning framework to predict the class label for each test image. The local learning framework is based on three steps. First, a k-nearest neighbors model is applied for selecting the nearest training samples for an input test image. Second, a one-versus-all Support Vector Machines (SVM) classifier is trained on the selected training samples. Finally, the SVM classifier is used for predicting the class label only for the test image it was trained for. Although local learning has been used before in combination with handcrafted features, to the best of our knowledge, it has never been employed in combination with deep features. The experiments on the 2013 Facial Expression Recognition (FER) Challenge data set and the FER+ data set demonstrate that our approach achieves state-of-the-art results. With a top accuracy of 75.42% on the FER 2013 data set and 86.71% on the FER+ data set, we surpass all competition by nearly 2% on both data sets.

##### Abstract (translated by Google)
我们提出了一种方法，将卷积神经网络（CNN）学习的自动特征与通过视觉词袋（BOVW）模型计算的手工特征相结合，以获得面部表情识别中的最新结果。为了获得自动特征，我们尝试了多种CNN体系结构，预先训练的模型和训练过程，例如，密疏密。融合这两种特征后，我们采用本地学习框架来预测每个测试图像的类别标签。本地学习框架基于三个步骤。首先，应用k最近邻模型来为输入测试图像选择最近的训练样本。其次，在所选择的训练样本上训练一对一支持向量机（SVM）分类器。最后，SVM分类器仅用于为其训练的测试图像预测类标签。尽管之前已经将局部学习与手工特征结合使用，但据我们所知，它从未与深层特征结合使用。 2013年面部表情识别（FER）挑战数据集和FER +数据集的实验表明我们的方法达到了最新的结果。 2013年FER数据集的最高准确率为75.42％，FER +数据集的最高准确率为86.71％，两组数据均超过所有竞争对手近2％。

##### URL
[https://arxiv.org/abs/1804.10892](https://arxiv.org/abs/1804.10892)

##### PDF
[https://arxiv.org/pdf/1804.10892](https://arxiv.org/pdf/1804.10892)

