---
layout: post
title: "Automated Prediction of Temporal Relations"
date: 2016-07-22 05:38:37
categories: arXiv_CL
tags: arXiv_CL Prediction Relation
author: Amol S Patwardhan, Jacob Badeaux, Siavash, Gerald M Knapp
mathjax: true
---

* content
{:toc}

##### Abstract
Background: There has been growing research interest in automated answering of questions or generation of summary of free form text such as news article. In order to implement this task, the computer should be able to identify the sequence of events, duration of events, time at which event occurred and the relationship type between event pairs, time pairs or event-time pairs. Specific Problem: It is important to accurately identify the relationship type between combinations of event and time before the temporal ordering of events can be defined. The machine learning approach taken in Mani et. al (2006) provides an accuracy of only 62.5 on the baseline data from TimeBank. The researchers used maximum entropy classifier in their methodology. TimeML uses the TLINK annotation to tag a relationship type between events and time. The time complexity is quadratic when it comes to tagging documents with TLINK using human annotation. This research proposes using decision tree and parsing to improve the relationship type tagging. This research attempts to solve the gaps in human annotation by automating the task of relationship type tagging in an attempt to improve the accuracy of event and time relationship in annotated documents. Scope information: The documents from the domain of news will be used. The tagging will be performed within the same document and not across documents. The relationship types will be identified only for a pair of event and time and not a chain of events. The research focuses on documents tagged using the TimeML specification which contains tags such as EVENT, TLINK, and TIMEX. Each tag has attributes such as identifier, relation, POS, time etc.

##### Abstract (translated by Google)
背景：自动回答问题或生成新闻文章等自由文本摘要的研究兴趣日益增长。为了实现这个任务，计算机应该能够识别事件序列，事件持续时间，事件发生的时间以及事件对，时间对或事件 - 时间对之间的关​​系类型。具体问题：在定义事件的时间顺序之前，准确地确定事件和时间组合之间的关系类型非常重要。 Mani等人的机器学习方法。 al（2006）对TimeBank的基线数据仅提供了62.5的准确度。研究人员在他们的方法中使用了最大熵分类器。 TimeML使用TLINK注释来标记事件和时间之间的关系类型。使用人类注释来标记TLINK文档时，时间复杂度是二次的。本研究提出使用决策树和解析来改善关系类型标注。本研究尝试通过自动化关系类型标注任务来解决人类注释中的空白，试图提高注释文档中事件和时间关系的准确性。范围信息：将使用来自新闻领域的文件。标记将在同一个文档中执行，而不是在文档中执行。关系类型将仅被识别为一对事件和时间，而不是一系列事件。该研究集中于使用包含诸如EVENT，TLINK和TIMEX等标签的TimeML规范标记的文档。每个标签都具有标识符，关系，POS，时间等属性。

##### URL
[https://arxiv.org/abs/1607.06560](https://arxiv.org/abs/1607.06560)

##### PDF
[https://arxiv.org/pdf/1607.06560](https://arxiv.org/pdf/1607.06560)

