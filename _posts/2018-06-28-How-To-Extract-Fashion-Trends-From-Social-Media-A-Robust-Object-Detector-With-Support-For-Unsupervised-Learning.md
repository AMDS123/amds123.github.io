---
layout: post
title: "How To Extract Fashion Trends From Social Media? A Robust Object Detector With Support For Unsupervised Learning"
date: 2018-06-28 06:23:56
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Vijay Gabale, Anand Prabhu Subramanian
mathjax: true
---

* content
{:toc}

##### Abstract
With the proliferation of social media, fashion inspired from celebrities, reputed designers as well as fashion influencers has shortened the cycle of fashion design and manufacturing. However, with the explosion of fashion related content and large number of user generated fashion photos, it is an arduous task for fashion designers to wade through social media photos and create a digest of trending fashion. This necessitates deep parsing of fashion photos on social media to localize and classify multiple fashion items from a given fashion photo. While object detection competitions such as MSCOCO have thousands of samples for each of the object categories, it is quite difficult to get large labeled datasets for fast fashion items. Moreover, state-of-the-art object detectors do not have any functionality to ingest large amount of unlabeled data available on social media in order to fine tune object detectors with labeled datasets. In this work, we show application of a generic object detector, that can be pretrained in an unsupervised manner, on 24 categories from recently released Open Images V4 dataset. We first train the base architecture of the object detector using unsupervisd learning on 60K unlabeled photos from 24 categories gathered from social media, and then subsequently fine tune it on 8.2K labeled photos from Open Images V4 dataset. On 300 X 300 image inputs, we achieve 72.7% mAP on a test dataset of 2.4K photos while performing 11% to 17% better as compared to the state-of-the-art object detectors. We show that this improvement is due to our choice of architecture that lets us do unsupervised learning and that performs significantly better in identifying small objects.

##### Abstract (translated by Google)
随着社交媒体的激增，来自知名人士，知名设计师以及时尚影响者的时尚风潮缩短了时装设计和制造的周期。然而，随着时尚相关内容的大量涌现和大量用户生成的时尚照片的出现，时装设计师通过社交媒体的照片和创造趋势时尚的摘要是一项艰巨的任务。这就需要对社交媒体上的时尚照片进行深度解析，以对来自给定时尚照片的多个时尚物品进行本地化和分类。虽然诸如MSCOCO之类的对象检测竞赛对于每个对象类别都有数千个样本，但为快速时尚项目获取大型标记数据集相当困难。而且，最先进的物体检测器没有任何功能来摄取社交媒体上可用的大量未标记数据，以便用标记的数据集对目标检测器进行微调。在这项工作中，我们展示了一个通用对象检测器的应用，该检测器可以以无监督的方式预训练，从最近发布的Open Images V4数据集的24个类别中进行。我们首先使用从社交媒体收集的来自24个类别的60K无标签照片上的无监督学习来训练对象检测器的基础架构，然后在来自Open Images V4数据集的8.2K标记照片上进行微调。在300X300图像输入上，我们在2.4K照片的测试数据集上实现了72.7％的mAP，同时与最先进的物体检测器相比，性能提高了11％到17％。我们表明，这种改进是由于我们选择的架构可以让我们进行无监督学习，并且在识别小物体方面表现更好。

##### URL
[http://arxiv.org/abs/1806.10787](http://arxiv.org/abs/1806.10787)

##### PDF
[http://arxiv.org/pdf/1806.10787](http://arxiv.org/pdf/1806.10787)

