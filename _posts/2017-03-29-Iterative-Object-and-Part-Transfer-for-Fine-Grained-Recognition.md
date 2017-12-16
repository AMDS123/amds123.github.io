---
layout: post
title: "Iterative Object and Part Transfer for Fine-Grained Recognition"
date: 2017-03-29 11:50:34
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Zhiqiang Shen, Yu-Gang Jiang, Dequan Wang, Xiangyang Xue
mathjax: true
---

* content
{:toc}

##### Abstract
The aim of fine-grained recognition is to identify sub-ordinate categories in images like different species of birds. Existing works have confirmed that, in order to capture the subtle differences across the categories, automatic localization of objects and parts is critical. Most approaches for object and part localization relied on the bottom-up pipeline, where thousands of region proposals are generated and then filtered by pre-trained object/part models. This is computationally expensive and not scalable once the number of objects/parts becomes large. In this paper, we propose a nonparametric data-driven method for object and part localization. Given an unlabeled test image, our approach transfers annotations from a few similar images retrieved in the training set. In particular, we propose an iterative transfer strategy that gradually refine the predicted bounding boxes. Based on the located objects and parts, deep convolutional features are extracted for recognition. We evaluate our approach on the widely-used CUB200-2011 dataset and a new and large dataset called Birdsnap. On both datasets, we achieve better results than many state-of-the-art approaches, including a few using oracle (manually annotated) bounding boxes in the test images.

##### Abstract (translated by Google)
细粒度识别的目的是确定不同鸟类种类的图像中的纵坐标类别。现有的作品已经证实，为了捕捉不同类别之间的细微差别，物体和零件的自动定位是至关重要的。对象和零件本地化的大多数方法依赖于自下而上的管道，在那里生成数以千计的区域建议，然后通过预先训练的对象/零件模型进行过滤。一旦物体/部件的数量变大，这在计算上是昂贵的并且不可扩展。在本文中，我们提出了一个非参数数据驱动的对象和零件定位方法。给定一个未标记的测试图像，我们的方法从训练集中检索到的一些相似图像转移注释。具体来说，我们提出了一个迭代转移策略，逐步完善预测包围盒。根据定位的对象和部分，提取深度卷积特征进行识别。我们在广泛使用的CUB200-2011数据集和一个名为Birdsnap的新的大型数据集上评估我们的方法。在这两个数据集上，我们比许多最先进的方法（包括一些在测试图像中使用oracle（手动注释的）边界框）获得更好的结果。

##### URL
[https://arxiv.org/abs/1703.09983](https://arxiv.org/abs/1703.09983)

##### PDF
[https://arxiv.org/pdf/1703.09983](https://arxiv.org/pdf/1703.09983)

