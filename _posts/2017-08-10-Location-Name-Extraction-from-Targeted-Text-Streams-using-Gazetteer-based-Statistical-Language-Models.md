---
layout: post
title: "Location Name Extraction from Targeted Text Streams using Gazetteer-based Statistical Language Models"
date: 2017-08-10 07:43:13
categories: arXiv_CL
tags: arXiv_CL Language_Model
author: Hussein S. Al-Olimat, Krishnaprasad Thirunarayan, Valerie Shalin, Amit Sheth
mathjax: true
---

* content
{:toc}

##### Abstract
Extracting location names from informal and unstructured texts requires the identification of referent boundaries and partitioning of compound names in the presence of variation in location referents. Instead of analyzing semantic, syntactic, and/or orthographic features, our Location Name Extraction tool (LNEx) exploits a region-specific statistical language model to evaluate an observed n-gram in Twitter targeted text as a legitimate location name variant. LNEx handles abbreviations, and automatically filters and augments the location names in gazetteers from OpenStreetMap, Geonames, and DBpedia. Consistent with Carroll [4], LNEx addresses two kinds of location name contractions: category ellipsis and location ellipsis, which produces alternate name forms of location names (i.e., Nameheads of location names). The modified gazetteers and dictionaries of abbreviations help detect the boundaries of multi-word location names delimiting them in texts using n-gram statistics. We evaluated the extent to which using an augmented and filtered region-specific gazetteer can successfully extract location names from a targeted text stream. We used 4,500 event-specific tweets from three targeted streams of different flooding disasters to compare LNEx performance against eight state-of-the-art taggers. LNEx improved the average F-Score by 98-145% outperforming these taggers convincingly on the three manually annotated Twitter streams. Furthermore, LNEx is capable of stream processing.

##### Abstract (translated by Google)
从非正式和非结构化文本中提取位置名称需要在存在位置参照物变化的情况下，识别对象边界和复合名称的分割。我们的位置名称提取工具（LNEx）不是分析语义，语法和/或拼写特征，而是利用特定于地区的统计语言模型来评估在Twitter目标文本中观察到的n元格作为合法的位置名称变体。 LNEx处理缩写，并自动过滤和扩充来自OpenStreetMap，Geonames和DBpedia的地名词典中的位置名称。与Carroll [4]一致，LNEx解决了两种位置名称缩写：类别省略号和位置省略号，它们产生位置名称的替代名称形式（即位置名称的名称）。修改后的地名词典和缩略语字典有助于检测使用n-gram统计量在文本中划定它们的多字位置名称的边界。我们评估了使用增强和过滤的特定区域地名索引可以成功从目标文本流中提取位置名称的程度。我们使用了来自三个不同洪涝灾害目标流的4500个特定于事件的推文，以比较LNEx性能与八个最先进的标记器的性能。 LNEx将三个手动注释的Twitter流的平均F-分数提高了98-145％，令人信服地超越了这些标签。此外，LNEx能够进行流处理。

##### URL
[https://arxiv.org/abs/1708.03105](https://arxiv.org/abs/1708.03105)

##### PDF
[https://arxiv.org/pdf/1708.03105](https://arxiv.org/pdf/1708.03105)

