---
layout: post
title: "Object Recognition from very few Training Examples for Enhancing Bicycle Maps"
date: 2018-05-28 09:41:06
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Prediction Recognition
author: Christoph Reinders, Hanno Ackermann, Michael Ying Yang, Bodo Rosenhahn
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, data-driven methods have shown great success for extracting information about the infrastructure in urban areas. These algorithms are usually trained on large datasets consisting of thousands or millions of labeled training examples. While large datasets have been published regarding cars, for cyclists very few labeled data is available although appearance, point of view, and positioning of even relevant objects differ. Unfortunately, labeling data is costly and requires a huge amount of work. In this paper, we thus address the problem of learning with very few labels. The aim is to recognize particular traffic signs in crowdsourced data to collect information which is of interest to cyclists. We propose a system for object recognition that is trained with only 15 examples per class on average. To achieve this, we combine the advantages of convolutional neural networks and random forests to learn a patch-wise classifier. In the next step, we map the random forest to a neural network and transform the classifier to a fully convolutional network. Thereby, the processing of full images is significantly accelerated and bounding boxes can be predicted. Finally, we integrate data of the Global Positioning System (GPS) to localize the predictions on the map. In comparison to Faster R-CNN and other networks for object recognition or algorithms for transfer learning, we considerably reduce the required amount of labeled data. We demonstrate good performance on the recognition of traffic signs for cyclists as well as their localization in maps.

##### Abstract (translated by Google)
近年来，数据驱动的方法在提取有关城市地区基础设施的信息方面取得了巨大成功。这些算法通常在包含数千或数百万个标记训练样例的大型数据集上进行训练。虽然已经发布了关于汽车的大数据集，但对于骑车人来说，尽管相关对象的外观，观点和位置不同，但很少有标记数据可用。不幸的是，标签数据代价昂贵，需要大量的工作。因此，在本文中，我们解决了很少标签学习的问题。其目的是识别众包数据中的特定交通标志，以收集骑行者感兴趣的信息。我们提出了一个对象识别系统，每个类平均只有15个例子。为了实现这一点，我们结合了卷积神经网络和随机森林的优点来学习一种面向分片的分类器。在下一步中，我们将随机森林映射到神经网络，并将分类器转换为完全卷积网络。由此，全图像的处理显着加速并且可以预测边界框。最后，我们整合了全球定位系统（GPS）的数据，以在地图上定位预测。与更快的R-CNN和其他用于目标识别的网络或用于传输学习的算法相比，我们大大减少了标记数据的所需数量。我们在骑自行车者的交通标志识别和地图定位方面表现出色。

##### URL
[http://arxiv.org/abs/1709.05910](http://arxiv.org/abs/1709.05910)

##### PDF
[http://arxiv.org/pdf/1709.05910](http://arxiv.org/pdf/1709.05910)

