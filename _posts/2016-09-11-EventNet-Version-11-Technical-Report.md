---
layout: post
title: "EventNet Version 1.1 Technical Report"
date: 2016-09-11 19:10:33
categories: arXiv_CV
tags: arXiv_CV Ontology CNN Classification
author: Dongang Wang, Zheng Shou, Hongyi Liu, Shih-Fu Chang
mathjax: true
---

* content
{:toc}

##### Abstract
EventNet is a large-scale video corpus and event ontology consisting of 500 events associated with event-specific concepts. In order to improve the quality of the current EventNet, we conduct the following steps and introduce EventNet version 1.1: (1) manually verify the correctness of event labels for all videos; (2) remove the YouTube user bias by limiting the maximum number of videos in each event from the same YouTube user as 3; (3) remove the videos which are currently not accessible online; (4) remove the video belonging to multiple event categories. After the above procedure, some events may contain only a small number of videos, and therefore we crawl more videos for those events to ensure every event will contain more than 50 videos. Finally, EventNet version 1.1 contains 67,641 videos, 500 events, and 5,028 event-specific concepts. In addition, we train a Convolutional Neural Network (CNN) model for event classification via fine-tuning AlexNet using EventNet version 1.1. Then we use the trained CNN model to extract FC7 layer feature and train binary classifiers using linear SVM for each event-specific concept. We believe this new version of EventNet will significantly facilitate research in computer vision and multimedia, and will put it online for public downloading in the future.

##### Abstract (translated by Google)
EventNet是一个大型的视频语料库和事件本体，由500个与事件相关概念相关的事件组成。为了提高当前EventNet的质量，我们进行以下步骤并引入EventNet 1.1版本：（1）手动验证所有视频的事件标签的正确性; （2）通过将来自同一个YouTube用户的每个事件中的视频的最大数目限制为3来移除YouTube用户的偏见; （3）删除当前无法在线访问的视频; （4）删除属于多个事件类别的视频。经过上述过程，有些事件可能只包含少量的视频，因此我们会抓取更多的视频，以确保每个事件将包含超过50个视频。最后，EventNet 1.1版包含67,641个视频，500个事件和5,028个特定于事件的概念。此外，我们还通过使用EventNet 1.1版微调AlexNet来训练用于事件分类的卷积神经网络（CNN）模型。然后，我们使用训练的CNN模型来提取FC7层特征，并且针对每个事件特定的概念使用线性SVM训练二元分类器。我们相信这个新版本的EventNet将大大促进计算机视觉和多媒体方面的研究，并将在网上公开下载。

##### URL
[https://arxiv.org/abs/1605.07289](https://arxiv.org/abs/1605.07289)

##### PDF
[https://arxiv.org/pdf/1605.07289](https://arxiv.org/pdf/1605.07289)

