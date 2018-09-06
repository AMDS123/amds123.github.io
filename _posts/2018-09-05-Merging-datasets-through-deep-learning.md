---
layout: post
title: "Merging datasets through deep learning"
date: 2018-09-05 16:19:26
categories: arXiv_AI
tags: arXiv_AI Face Ontology Deep_Learning
author: Kavitha Srinivas, Abraham Gale, Julian Dolby
mathjax: true
---

* content
{:toc}

##### Abstract
Merging datasets is a key operation for data analytics. A frequent requirement for merging is joining across columns that have different surface forms for the same entity (e.g., the name of a person might be represented as "Douglas Adams" or "Adams, Douglas"). Similarly, ontology alignment can require recognizing distinct surface forms of the same entity, especially when ontologies are independently developed. However, data management systems are currently limited to performing merges based on string equality, or at best using string similarity. We propose an approach to performing merges based on deep learning models. Our approach depends on (a) creating a deep learning model that maps surface forms of an entity into a set of vectors such that alternate forms for the same entity are closest in vector space, (b) indexing these vectors using a nearest neighbors algorithm to find the forms that can be potentially joined together. To build these models, we had to adapt techniques from metric learning due to the characteristics of the data; specifically we describe novel sample selection techniques and loss functions that work for this problem. To evaluate our approach, we used Wikidata as ground truth and built models from datasets with approximately 1.1M people's names (200K identities) and 130K company names (70K identities). We developed models that allow for joins with precision@1 of .75-.81 and recall of .74-.81. We make the models available for aligning people or companies across multiple datasets.

##### Abstract (translated by Google)
合并数据集是数据分析的关键操作。合并的常见要求是加入具有相同实体的不同表面形式的列（例如，人的名称可以表示为“Douglas Adams”或“Adams，Douglas”）。类似地，本体对齐可能需要识别同一实体的不同表面形式，尤其是当本体是独立开发时。但是，数据管理系统目前仅限于基于字符串相等性执行合并，或者最多使用字符串相似性。我们提出了一种基于深度学习模型执行合并的方法。我们的方法取决于（a）创建一个深度学习模型，该模型将实体的表面形式映射到一组向量中，使得同一实体的替代形式在向量空间中最接近，（b）使用最近邻居算法对这些向量进行索引。找到可能可能连接在一起的表单。为了构建这些模型，由于数据的特性，我们不得不采用度量学习的技术;具体而言，我们描述了适用于此问题的新颖样本选择技术和损失函数。为了评估我们的方法，我们使用维基数作为基础事实，并使用大约1.1M人名（200K身份）和130K公司名称（70K身份）的数据集构建模型。我们开发的模型允许以0.75-.81的精度@ 1和0.74-.81的精度进行连接。我们使模型可用于在多个数据集中对齐人员或公司。

##### URL
[http://arxiv.org/abs/1809.01604](http://arxiv.org/abs/1809.01604)

##### PDF
[http://arxiv.org/pdf/1809.01604](http://arxiv.org/pdf/1809.01604)

