---
layout: post
title: "Deep Learning Based Vehicle Make-Model Classification"
date: 2018-08-23 14:05:31
categories: arXiv_AI
tags: arXiv_AI Object_Detection CNN Classification Deep_Learning Detection
author: Burak Satar, Ahmet Emir Dirik
mathjax: true
---

* content
{:toc}

##### Abstract
This paper studies the problems of vehicle make &amp; model classification. Some of the main challenges are reaching high classification accuracy and reducing the annotation time of the images. To address these problems, we have created a fine-grained database using online vehicle marketplaces of Turkey. A pipeline is proposed to combine an SSD (Single Shot Multibox Detector) model with a CNN (Convolutional Neural Network) model to train on the database. In the pipeline, we first detect the vehicles by following an algorithm which reduces the time for annotation. Then, we feed them into the CNN model. It is reached approximately 4% better classification accuracy result than using a conventional CNN model. Next, we propose to use the detected vehicles as ground truth bounding box (GTBB) of the images and feed them into an SSD model in another pipeline. At this stage, it is reached reasonable classification accuracy result without using perfectly shaped GTBB. Lastly, an application is implemented in a use case by using our proposed pipelines. It detects the unauthorized vehicles by comparing their license plate numbers and make &amp; models. It is assumed that license plates are readable.

##### Abstract (translated by Google)
本文研究了车辆制造和车辆的问题。模型分类。一些主要挑战是达到高分类准确度并减少图像的注释时间。为了解决这些问题，我们使用土耳其的在线汽车市场创建了一个细粒度的数据库。提出了一种管道，用于将SSD（单击多盒检测器）模型与CNN（卷积神经网络）模型相结合，以在数据库上进行训练。在管道中，我们首先通过遵循减少注释时间的算法来检测车辆。然后，我们将它们输入CNN模型。与使用传统的CNN模型相比，其分类精度结果大约高出4％。接下来，我们建议使用检测到的车辆作为图像的地面实况边界框（GTBB），并将它们馈送到另一个管道中的SSD模型中。在这个阶段，没有使用完美形状的GTBB就达到了合理的分类精度结果。最后，通过使用我们提出的管道在应用程序中实现应用程序。它通过比较他们的车牌号码来制造和检测未经授权的车辆。楷模。假设牌照是可读的。

##### URL
[http://arxiv.org/abs/1809.00953](http://arxiv.org/abs/1809.00953)

##### PDF
[http://arxiv.org/pdf/1809.00953](http://arxiv.org/pdf/1809.00953)

