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


##### URL
[https://arxiv.org/abs/1803.05401](https://arxiv.org/abs/1803.05401)

##### PDF
[https://arxiv.org/pdf/1803.05401](https://arxiv.org/pdf/1803.05401)

