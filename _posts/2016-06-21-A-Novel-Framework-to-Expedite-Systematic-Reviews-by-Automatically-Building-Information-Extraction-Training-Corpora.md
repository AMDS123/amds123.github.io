---
layout: post
title: "A Novel Framework to Expedite Systematic Reviews by Automatically Building Information Extraction Training Corpora"
date: 2016-06-21 04:56:33
categories: arXiv_CL
tags: arXiv_CL Review
author: Tanmay Basu, Shraman Kumar, Abhishek Kalyan, Priyanka Jayaswal, Pawan Goyal, Stephen Pettifer, Siddhartha R. Jonnalagadda
mathjax: true
---

* content
{:toc}

##### Abstract
A systematic review identifies and collates various clinical studies and compares data elements and results in order to provide an evidence based answer for a particular clinical question. The process is manual and involves lot of time. A tool to automate this process is lacking. The aim of this work is to develop a framework using natural language processing and machine learning to build information extraction algorithms to identify data elements in a new primary publication, without having to go through the expensive task of manual annotation to build gold standards for each data element type. The system is developed in two stages. Initially, it uses information contained in existing systematic reviews to identify the sentences from the PDF files of the included references that contain specific data elements of interest using a modified Jaccard similarity measure. These sentences have been treated as labeled data.A Support Vector Machine (SVM) classifier is trained on this labeled data to extract data elements of interests from a new article. We conducted experiments on Cochrane Database systematic reviews related to congestive heart failure using inclusion criteria as an example data element. The empirical results show that the proposed system automatically identifies sentences containing the data element of interest with a high recall (93.75%) and reasonable precision (27.05% - which means the reviewers have to read only 3.7 sentences on average). The empirical results suggest that the tool is retrieving valuable information from the reference articles, even when it is time-consuming to identify them manually. Thus we hope that the tool will be useful for automatic data extraction from biomedical research publications. The future scope of this work is to generalize this information framework for all types of systematic reviews.

##### Abstract (translated by Google)
系统评价识别和整理各种临床研究，并比较数据元素和结果，以便为特定的临床问题提供基于证据的答案。这个过程是手动的，涉及很多时间。缺乏使这一过程自动化的工具。这项工作的目的是开发一个框架，使用自然语言处理和机器学习来构建信息提取算法，以识别新的主要出版物中的数据元素，而不必花费昂贵的手工注释任务来为每个数据建立黄金标准元素类型。该系统分两个阶段开发。最初，它使用包含在现有系统评价中的信息，通过使用改进的Jaccard相似性度量，从包含参考文献的PDF文件中识别包含感兴趣的特定数据元素的句子。这些句子被视为标记数据。支持向量机（SVM）分类器是训练有标签的数据从新文章提取兴趣的数据元素。我们使用纳入标准作为实例数据元素，对与充血性心力衰竭相关的Cochrane数据库系统评价进行了实验。实验结果表明，所提出的系统自动识别含有高回忆率（93.75％）和合理精度（27.05％ - 意味着评审者平均只能读3.7个句子）的感兴趣的数据元素的句子。实证结果表明，该工具正在从参考文献中检索有价值的信息，即使手动识别它们非常耗时。因此，我们希望该工具对于从生物医学研究出版物中自动提取数据有用。这项工作的未来范围是推广所有类型的系统评价信息框架。

##### URL
[https://arxiv.org/abs/1606.06424](https://arxiv.org/abs/1606.06424)

##### PDF
[https://arxiv.org/pdf/1606.06424](https://arxiv.org/pdf/1606.06424)

