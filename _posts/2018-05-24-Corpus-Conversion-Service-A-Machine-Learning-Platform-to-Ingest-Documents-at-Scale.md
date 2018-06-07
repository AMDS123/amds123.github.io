---
layout: post
title: "Corpus Conversion Service: A Machine Learning Platform to Ingest Documents at Scale"
date: 2018-05-24 09:44:07
categories: arXiv_CV
tags: arXiv_CV Knowledge Classification
author: Peter W J Staar, Michele Dolfi, Christoph Auer, Costas Bekas
mathjax: true
---

* content
{:toc}

##### Abstract
Over the past few decades, the amount of scientific articles and technical literature has increased exponentially in size. Consequently, there is a great need for systems that can ingest these documents at scale and make the contained knowledge discoverable. Unfortunately, both the format of these documents (e.g. the PDF format or bitmap images) as well as the presentation of the data (e.g. complex tables) make the extraction of qualitative and quantitive data extremely challenging. In this paper, we present a modular, cloud-based platform to ingest documents at scale. This platform, called the Corpus Conversion Service (CCS), implements a pipeline which allows users to parse and annotate documents (i.e. collect ground-truth), train machine-learning classification algorithms and ultimately convert any type of PDF or bitmap-documents to a structured content representation format. We will show that each of the modules is scalable due to an asynchronous microservice architecture and can therefore handle massive amounts of documents. Furthermore, we will show that our capability to gather ground-truth is accelerated by machine-learning algorithms by at least one order of magnitude. This allows us to both gather large amounts of ground-truth in very little time and obtain very good precision/recall metrics in the range of 99\% with regard to content conversion to structured output. The CCS platform is currently deployed on IBM internal infrastructure and serving more than 250 active users for knowledge-engineering project engagements.

##### Abstract (translated by Google)
在过去的几十年中，科学文章和技术文献的数量呈指数级增长。因此，非常需要能够大规模地获取这些文档并使所包含的知识可被发现的系统。不幸的是，这些文档的格式（例如PDF格式或位图图像）以及数据的表示（例如复杂表格）使得定性和定量数据的提取非常具有挑战性。在本文中，我们提出了一个模块化的，基于云的平台来大规模提取文档。这个名为Corpus Conversion Service（CCS）的平台实现了一个管道，允许用户解析和注释文档（即收集地面真相），训练机器学习分类算法，并最终将任何类型的PDF或位图文档转换为结构化内容表示格式。我们将展示每个模块由于采用异步微服务架构而可扩展，因此可以处理大量文档。此外，我们将展示我们通过机器学习算法加速至少一个数量级来收集地面实况的能力。这使我们能够在很短的时间内收集大量的事实真相，并在内容转换为结构化输出方面获得99％范围内的非常好的精度/回忆度量。 CCS平台目前部署在IBM内部基础架构上，为250多名活跃用户提供知识工程项目服务。

##### URL
[http://arxiv.org/abs/1806.02284](http://arxiv.org/abs/1806.02284)

##### PDF
[http://arxiv.org/pdf/1806.02284](http://arxiv.org/pdf/1806.02284)

