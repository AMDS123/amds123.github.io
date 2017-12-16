---
layout: post
title: "Image and Video Mining through Online Learning"
date: 2016-12-07 12:26:30
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Recognition
author: Andrew Gilbert, Richard Bowden
mathjax: true
---

* content
{:toc}

##### Abstract
Within the field of image and video recognition, the traditional approach is a dataset split into fixed training and test partitions. However, the labelling of the training set is time-consuming, especially as datasets grow in size and complexity. Furthermore, this approach is not applicable to the home user, who wants to intuitively group their media without tirelessly labelling the content. Our interactive approach is able to iteratively cluster classes of images and video. Our approach is based around the concept of an image signature which, unlike a standard bag of words model, can express co-occurrence statistics as well as symbol frequency. We efficiently compute metric distances between signatures despite their inherent high dimensionality and provide discriminative feature selection, to allow common and distinctive elements to be identified from a small set of user labelled examples. These elements are then accentuated in the image signature to increase similarity between examples and pull correct classes together. By repeating this process in an online learning framework, the accuracy of similarity increases dramatically despite labelling only a few training examples. To demonstrate that the approach is agnostic to media type and features used, we evaluate on three image datasets (15 scene, Caltech101 and FG-NET), a mixed text and image dataset (ImageTag), a dataset used in active learning (Iris) and on three action recognition datasets (UCF11, KTH and Hollywood2). On the UCF11 video dataset, the accuracy is 86.7% despite using only 90 labelled examples from a dataset of over 1200 videos, instead of the standard 1122 training videos. The approach is both scalable and efficient, with a single iteration over the full UCF11 dataset of around 1200 videos taking approximately 1 minute on a standard desktop machine.

##### Abstract (translated by Google)
在图像和视频识别领域，传统的方法是将数据集分成固定的训练和测试分区。然而，训练集的标签是耗时的，特别是随着数据集的大小和复杂性的增加。此外，这种方法不适用于家庭用户，他们希望直观地将他们的媒体分组，而不需要不知疲倦地标注内容。我们的交互式方法能够对图像和视频的类进行迭代聚类。我们的方法是基于图像签名的概念，它不像一个标准的单词模型包，可以表达同现统计以及符号频率。我们有效地计算签名之间的度量距离，尽管它们具有固有的高维度，并提供了区分性特征选择，以允许从一小组用户标记的示例中识别出共同的和独特的元素。这些元素然后在图像签名中加以强调，以增加示例之间的相似性并将正确的类拉到一起。通过在线学习框架重复这个过程，相似度的准确性急剧增加，尽管只标注了一些训练样例。为了证明这种方法对所使用的媒体类型和特征是不可知的，我们对三个图像数据集（15场景，Caltech101和FG-NET），混合文本和图像数据集（ImageTag），主动学习（Iris）和三个动作识别数据集（UCF11，KTH和Hollywood2）。在UCF11视频数据集中，精确度为86.7％，尽管从超过1200个视频的数据集中只使用了90个标记示例，而不是标准的1122个培训视频。该方法既可扩展又高效，在标准台式机上花费大约1分钟的时间，在大约1200个视频的完整UCF11数据集上进行一次迭代。

##### URL
[https://arxiv.org/abs/1609.02770](https://arxiv.org/abs/1609.02770)

##### PDF
[https://arxiv.org/pdf/1609.02770](https://arxiv.org/pdf/1609.02770)

