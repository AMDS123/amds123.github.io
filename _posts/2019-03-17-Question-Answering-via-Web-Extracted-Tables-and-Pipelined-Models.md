---
layout: post
title: "Question Answering via Web Extracted Tables and Pipelined Models"
date: 2019-03-17 15:46:05
categories: arXiv_CL
tags: arXiv_CL QA Classification
author: Bhavya Karki, Fan Hu, Nithin Haridas Suhail Barot, Zihua Liu, Lucile Callebert, Matthias Grabmair, Anthony Tomasic
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we describe a dataset and baseline result for a question answering that utilizes web tables. It contains commonly asked questions on the web and their corresponding answers found in tables on websites. Our dataset is novel in that every question is paired with a table of a different signature. In particular, the dataset contains two classes of tables: entity-instance tables and the key-value tables. Each QA instance comprises a table of either kind, a natural language question, and a corresponding structured SQL query. We build our model by dividing question answering into several tasks, including table retrieval and question element classification, and conduct experiments to measure the performance of each task. We extract various features specific to each task and compose a full pipeline which constructs the SQL query from its parts. Our work provides qualitative results and error analysis for each task, and identifies in detail the reasoning required to generate SQL expressions from natural language questions. This analysis of reasoning informs future models based on neural machine learning.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.07113](http://arxiv.org/abs/1903.07113)

##### PDF
[http://arxiv.org/pdf/1903.07113](http://arxiv.org/pdf/1903.07113)

