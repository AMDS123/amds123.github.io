---
layout: post
title: "GeoTextTagger: High-Precision Location Tagging of Textual Documents using a Natural Language Processing Approach"
date: 2016-01-22 07:09:54
categories: arXiv_SD
tags: arXiv_SD Knowledge Classification
author: Shawn Brunsting, Hans De Sterck, Remco Dolman, Teun van Sprundel
mathjax: true
---

* content
{:toc}

##### Abstract
Location tagging, also known as geotagging or geolocation, is the process of assigning geographical coordinates to input data. In this paper we present an algorithm for location tagging of textual documents. Our approach makes use of previous work in natural language processing by using a state-of-the-art part-of-speech tagger and named entity recognizer to find blocks of text which may refer to locations. A knowledge base (OpenStreatMap) is then used to find a list of possible locations for each block. Finally, one location is chosen for each block by assigning distance-based scores to each location and repeatedly selecting the location and block with the best score. We tested our geolocation algorithm with Wikipedia articles about topics with a well-defined geographical location that are geotagged by the articles' authors, where classification approaches have achieved median errors as low as 11 km, with attainable accuracy limited by the class size. Our approach achieved a 10th percentile error of 490 metres and median error of 54 kilometres on the Wikipedia dataset we used. When considering the five location tags with the greatest scores, 50% of articles were assigned at least one tag within 8.5 kilometres of the article's author-assigned true location. We also tested our approach on Twitter messages that are tagged with the location from which the message was sent. Twitter texts are challenging because they are short and unstructured and often do not contain words referring to the location they were sent from, but we obtain potentially useful results. We explain how we use the Spark framework for data analytics to collect and process our test data. In general, classification-based approaches for location tagging may be reaching their upper accuracy limit, but our precision-focused approach has high accuracy for some texts and shows significant potential for improvement overall.

##### Abstract (translated by Google)
位置标记也称为地理标记或地理定位，是将地理坐标分配给输入数据的过程。在本文中，我们提出了一种用于文本文档位置标记的算法。我们的方法利用以前在自然语言处理中的工作，通过使用最先进的词性标注器和命名实体识别器来查找可能指向位置的文本块。然后使用知识库（OpenStreatMap）来查找每个块的可能位置的列表。最后，通过为每个位置分配基于距离的分数并重复选择具有最佳分数的位置和块，为每个块选择一个位置。我们用维基百科关于主题的地理定位算法进行了测试，这些主题具有明确的地理位置，由文章作者进行地理标记，其中分类方法的中值误差低至11公里，可达到的精度受班级规模的限制。我们的方法在我们使用的维基百科数据集上达到了490米的第10百分位误差和54公里的中位误差。当考虑五个位置标签得分最高时，在文章的作者指定的真实位置8.5公里内，50％的文章被分配至少一个标签。我们还在Twitter消息上测试了我们的方法，这些消息标有发送消息的位置。 Twitter的文本是具有挑战性的，因为它们是短的和非结构化的，并且通常不包含指向它们发送位置的单词，但是我们获得潜在有用的结果。我们解释了我们如何使用Spark框架进行数据分析来收集和处理我们的测试数据。一般而言，基于分类的位置标注方法可能正在达到其精度上限，但我们精确的方法对某些文本具有较高的准确性，并显示出整体改进的巨大潜力。

##### URL
[https://arxiv.org/abs/1601.05893](https://arxiv.org/abs/1601.05893)

##### PDF
[https://arxiv.org/pdf/1601.05893](https://arxiv.org/pdf/1601.05893)

