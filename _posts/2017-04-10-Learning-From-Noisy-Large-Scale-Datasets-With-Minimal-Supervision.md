---
layout: post
title: "Learning From Noisy Large-Scale Datasets With Minimal Supervision"
date: 2017-04-10 01:25:42
categories: arXiv_CV
tags: arXiv_CV Image_Caption
author: Andreas Veit, Neil Alldrin, Gal Chechik, Ivan Krasin, Abhinav Gupta, Serge Belongie
mathjax: true
---

* content
{:toc}

##### Abstract
We present an approach to effectively use millions of images with noisy annotations in conjunction with a small subset of cleanly-annotated images to learn powerful image representations. One common approach to combine clean and noisy data is to first pre-train a network using the large noisy dataset and then fine-tune with the clean dataset. We show this approach does not fully leverage the information contained in the clean set. Thus, we demonstrate how to use the clean annotations to reduce the noise in the large dataset before fine-tuning the network using both the clean set and the full set with reduced noise. The approach comprises a multi-task network that jointly learns to clean noisy annotations and to accurately classify images. We evaluate our approach on the recently released Open Images dataset, containing ~9 million images, multiple annotations per image and over 6000 unique classes. For the small clean set of annotations we use a quarter of the validation set with ~40k images. Our results demonstrate that the proposed approach clearly outperforms direct fine-tuning across all major categories of classes in the Open Image dataset. Further, our approach is particularly effective for a large number of classes with wide range of noise in annotations (20-80% false positive annotations).

##### Abstract (translated by Google)
我们提出了一种方法来有效地使用数百万具有嘈杂注释的图像以及干净注释图像的小子集来学习强大的图像表示。将干净的数据和有噪声的数据结合起来的一种常见方法是首先使用噪声较大的数据集对网络进行预训练，然后对干净的数据集进行微调。我们显示这种方法不能充分利用干净集合中包含的信息。因此，我们演示了如何使用干净的注释来减少大数据集中的噪声，然后使用干净集和噪声减少的全集对网络进行微调。该方法包括一个多任务网络，共同学习清除噪声注释和准确分类图像。我们在最近发布的Open Images数据集上评估了我们的方法，其中包含约900万图像，每个图像多个注释和6000多个独特类。对于一小组干净的注释，我们使用四分之一具有〜40k图像的验证集。我们的结果表明，提出的方法明显优于Open Image数据集中所有主要类别的直接微调。此外，我们的方法对于注释中噪声范围广泛的大量类别（20-80％误报注释）特别有效。

##### URL
[https://arxiv.org/abs/1701.01619](https://arxiv.org/abs/1701.01619)

##### PDF
[https://arxiv.org/pdf/1701.01619](https://arxiv.org/pdf/1701.01619)

