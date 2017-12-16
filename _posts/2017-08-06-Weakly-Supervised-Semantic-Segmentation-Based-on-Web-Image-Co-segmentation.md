---
layout: post
title: "Weakly Supervised Semantic Segmentation Based on Web Image Co-segmentation"
date: 2017-08-06 04:09:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised CNN Semantic_Segmentation
author: Tong Shen, Guosheng Lin, Lingqiao Liu, Chunhua Shen, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
Training a Fully Convolutional Network (FCN) for semantic segmentation requires a large number of masks with pixel level labelling, which involves a large amount of human labour and time for annotation. In contrast, web images and their image-level labels are much easier and cheaper to obtain. In this work, we propose a novel method for weakly supervised semantic segmentation with only image-level labels. The method utilizes the internet to retrieve a large number of images and uses a large scale co-segmentation framework to generate masks for the retrieved images. We first retrieve images from search engines, e.g. Flickr and Google, using semantic class names as queries, e.g. class names in the dataset PASCAL VOC 2012. We then use high quality masks produced by co-segmentation on the retrieved images as well as the target dataset images with image level labels to train segmentation networks. We obtain an IoU score of 56.9 on test set of PASCAL VOC 2012, which reaches the state-of-the-art performance.

##### Abstract (translated by Google)
训练完全卷积网络（FCN）进行语义分割需要大量的具有像素级标记的蒙版，这需要大量的人力和时间进行注释。相比之下，网页图像及其图像级别的标签要容易得多。在这项工作中，我们提出了一个新的方法弱监督语义分割只有图像级标签。该方法利用互联网检索大量图像，并使用大规模协同分割框架为检索到的图像生成蒙版。我们首先从搜索引擎中检索图像，例如Flickr和Google，使用语义类名作为查询，例如在数据集PASCAL VOC 2012中使用类名。然后，我们使用通过在检索图像上的共分割产生的高质量掩模以及具有图像级标签的目标数据集图像来训练分割网络。我们在PASCAL VOC 2012的测试集上获得了56.9的IoU得分，达到了最先进的性能。

##### URL
[https://arxiv.org/abs/1705.09052](https://arxiv.org/abs/1705.09052)

##### PDF
[https://arxiv.org/pdf/1705.09052](https://arxiv.org/pdf/1705.09052)

