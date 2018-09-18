---
layout: post
title: "Accident Forecasting in CCTV Traffic Camera Videos"
date: 2018-09-16 00:01:39
categories: arXiv_CV
tags: arXiv_CV Object_Detection Knowledge RNN Prediction Detection
author: Ankit Shah, Jean Baptiste Lamare, Tuan Nguyen Anh, Alexander Hauptmann
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel dataset for traffic accidents analysis.Our goal is to resolve the lack of public data for research about automatic spatio-temporal annotations for traffic safety in the roads. Our Car Accident Detection and Prediction(CADP) dataset consists of 1,416 video segments collected from YouTube, with 205 video segments having full spatio-temporal annotations. To the best of our knowledge, our dataset is largest in terms of number of traffic accidents, compared to related datasets. Through the analysis of the proposed dataset, we observed a significant degradation of object detection in pedestrian category in our dataset, due to the object sizes and complexity of the scenes. To this end, we propose to integrate contextual information into conventional Faster R-CNN using Context Mining(CM) and Augmented Context Mining(ACM) to complement the accuracy for small pedestrian detection. Our experiments indicate a considerable improvement in object detection accuracy: +8.51 % for CM and +6.20 % for ACM. For person(pedestrian) category, we observed significant improvements:+46.45 % for CM and 45.22 % for ACM, compared to Faster R-CNN. Finally, we demonstrate the performance of accident forecasting in our dataset using Faster R-CNN and an Accident LSTM architecture. We achieved an average of 1.359 seconds in terms of Time-To-Accident measure with an Average Precision of 47.36 %. Our Webpage for the paper is https://goo.gl/cqK2wE

##### Abstract (translated by Google)
本文提出了一种新的交通事故分析数据集。我们的目标是解决公共交通安全自动时空注释研究缺乏的公共数据。我们的车祸检测和预测（CADP）数据集包括从YouTube收集的1,416个视频片段，其中205个视频片段具有完整的时空注释。据我们所知，与相关数据集相比，我们的数据集在交通事故数量方面最大。通过对所提议的数据集的分析，我们观察到由于场景的对象大小和复杂性，在我们的数据集中行人类别中的对象检测的显着降级。为此，我们建议使用上下文挖掘（CM）和增强上下文挖掘（ACM）将上下文信息集成到传统的更快的R-CNN中，以补充小行人检测的准确性。我们的实验表明物体检测准确度有了相当大的提高：CM为+ 8.51％，ACM为+6.20％。对于人（行人）类别，我们观察到显着改善：与快速R-CNN相比，CM为+ 46.45％，ACM为45.22％。最后，我们使用Faster R-CNN和Accident LSTM架构在我们的数据集中演示事故预测的性能。我们在事故时间测量方面平均达到1.359秒，平均精度为47.36％。我们的论文网页是https://goo.gl/cqK2wE

##### URL
[http://arxiv.org/abs/1809.05782](http://arxiv.org/abs/1809.05782)

##### PDF
[http://arxiv.org/pdf/1809.05782](http://arxiv.org/pdf/1809.05782)

