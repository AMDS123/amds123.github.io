---
layout: post
title: "Approximate Query Matching for Image Retrieval"
date: 2018-03-14 16:57:50
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Segmentation Caption Semantic_Segmentation Relation Recognition
author: Abhijit Suprem, Polo Chau
mathjax: true
---

* content
{:toc}

##### Abstract
Traditional image recognition involves identifying the key object in a portrait-type image with a single object focus (ILSVRC, AlexNet, and VGG). More recent approaches consider dense image recognition - segmenting an image with appropriate bounding boxes and performing image recognition within these bounding boxes (Semantic segmentation). The Visual Genome dataset [5] is an attempt to bridge these various approaches to a cohesive dataset for each subtask - bounding box generation, image recognition, captioning, and a new operation: scene graph generation. Our focus is on using such scene graphs to perform graph search on image databases to holistically retrieve images based on a search criteria. We develop a method to store scene graphs and metadata in graph databases (using Neo4J) and to perform fast approximate retrieval of images based on a graph search query. We process more complex queries than single object search, e.g. "girl eating cake" retrieves images that contain the specified relation as well as variations.

##### Abstract (translated by Google)
传统图像识别涉及通过单个对象焦点（ILSVRC，AlexNet和VGG）识别纵向型图像中的关键对象。更近期的方法考虑密集图像识别 - 用合适的边界框分割图像并在这些边界框内执行图像识别（语义分割）。 Visual Genome数据集[5]试图将这些不同的方法连接到每个子任务边界框生成，图像识别，字幕和一项新操作（场景图生成）的粘性数据集上。我们的重点是使用这样的场景图来对图像数据库执行图搜索以基于搜索标准整体检索图像。我们开发了一种方法，在图形数据库（使用Neo4J）中存储场景图形和元数据，并根据图形搜索查询执行图像的快速近似检索。我们处理比单个对象搜索更复杂的查询，例如“女孩吃蛋糕”检索包含指定关系以及变体的图像。

##### URL
[https://arxiv.org/abs/1803.05401](https://arxiv.org/abs/1803.05401)

##### PDF
[https://arxiv.org/pdf/1803.05401](https://arxiv.org/pdf/1803.05401)

