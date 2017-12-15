---
layout: post
title: "Unsupervised High-level Feature Learning by Ensemble Projection for Semi-supervised Image Classification and Image Clustering"
date: 2016-02-04 13:58:00
categories: arXiv_CV
tags: arXiv_CV Image_Caption Image_Retrieval Image_Classification Classification Relation
author: Dengxin Dai, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
This paper investigates the problem of image classification with limited or no annotations, but abundant unlabeled data. The setting exists in many tasks such as semi-supervised image classification, image clustering, and image retrieval. Unlike previous methods, which develop or learn sophisticated regularizers for classifiers, our method learns a new image representation by exploiting the distribution patterns of all available data for the task at hand. Particularly, a rich set of visual prototypes are sampled from all available data, and are taken as surrogate classes to train discriminative classifiers; images are projected via the classifiers; the projected values, similarities to the prototypes, are stacked to build the new feature vector. The training set is noisy. Hence, in the spirit of ensemble learning we create a set of such training sets which are all diverse, leading to diverse classifiers. The method is dubbed Ensemble Projection (EP). EP captures not only the characteristics of individual images, but also the relationships among images. It is conceptually simple and computationally efficient, yet effective and flexible. Experiments on eight standard datasets show that: (1) EP outperforms previous methods for semi-supervised image classification; (2) EP produces promising results for self-taught image classification, where unlabeled samples are a random collection of images rather than being from the same distribution as the labeled ones; and (3) EP improves over the original features for image clustering. The code of the method is available on the project page.

##### Abstract (translated by Google)
本文研究了有限注释或不注释的图像分类问题，但是大量的未标注数据。该设置存在于诸如半监督图像分类，图像聚类和图像检索等许多任务中。不像以前的方法，开发或学习复杂的正规化分类器，我们的方法学习一个新的图像表示，通过利用所有可用数据的分布模式的手头任务。特别是，从所有可用的数据中抽取了丰富的视觉原型，并将其作为替代类来训练辨别分类器;图像通过分类器投影;投影值与原型的相似度被叠加起来以建立新的特征向量。训练集是嘈杂的。因此，本着集合学习的精神，我们创建了一套这样的训练集，这些训练集各不相同，导致了不同的分类器。该方法被称为Ensemble Projection（EP）。 EP不仅捕捉个人图像的特征，而且捕捉图像之间的关系。它在概念上简单且计算效率高，但是有效且灵活。在8个标准数据集上的实验表明：（1）EP优于以前的半监督图像分类方法; （2）EP对于自学图像分类产生了有希望的结果，其中未标记的样本是图像的随机集合，而不是与标记的样本相同的分布; （3）EP改善了原有的图像聚类特征。该方法的代码在项目页面上可用。

##### URL
[https://arxiv.org/abs/1602.00955](https://arxiv.org/abs/1602.00955)

##### PDF
[https://arxiv.org/pdf/1602.00955](https://arxiv.org/pdf/1602.00955)

