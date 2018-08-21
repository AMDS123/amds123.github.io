---
layout: post
title: "XL-NBT: A Cross-lingual Neural Belief Tracking Framework"
date: 2018-08-19 19:08:10
categories: arXiv_AI
tags: arXiv_AI Knowledge Tracking Transfer_Learning
author: Wenhu Chen, Jianshu Chen, Yu Su, Xin Wang, Dong Yu, Xifeng Yan, William Yang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Task-oriented dialog systems are becoming pervasive, and many companies heavily rely on them to complement human agents for customer service in call centers. With globalization, the need for providing cross-lingual customer support becomes more urgent than ever. However, cross-lingual support poses great challenges---it requires a large amount of additional annotated data from native speakers. In order to bypass the expensive human annotation and achieve the first step towards the ultimate goal of building a universal dialog management system, we set out to build a cross-lingual state tracking framework without requiring any human labor. Specifically, we assume that there exists a source language with dialog belief tracking annotations while having no access to any form of dialogue data for the other target languages. Then, we pre-train a state tracker for the source language as a teacher, which is able to exploit easy-to-access parallel data and distill its own knowledge to the student state tracker in target languages. In this paper, we specifically discuss two different types of common parallel resources (bilingual corpus and bilingual dictionary) and design different strategies to realize our transfer learning framework. Experimentally, we successfully use English state tracker as the teacher to transfer its knowledge to both Italian and German trackers and achieve promising results.

##### Abstract (translated by Google)
面向任务的对话系统正变得越来越普遍，许多公司在很大程度上依赖它们来补充呼叫中心客户服务的人工代理。随着全球化的发展，提供跨语言客户支持的需求变得比以往任何时候都更迫切。但是，跨语言支持带来了巨大的挑战 - 它需要来自母语人士的大量额外注释数据。为了绕过昂贵的人类注释并实现建立通用对话管理系统的最终目标的第一步，我们着手建立一个跨语言的状态跟踪框架，而不需要任何人工。具体而言，我们假设存在具有对话信念跟踪注释的源语言，而不能访问其他目标语言的任何形式的对话数据。然后，我们作为教师预先培训源语言的状态跟踪器，它能够利用易于访问的并行数据，并以目标语言向学生状态跟踪器提取自己的知识。在本文中，我们具体讨论了两种不同类型的通用并行资源（双语语料库和双语词典），并设计了不同的策略来实现我们的转移学习框架。在实验上，我们成功地使用英国状态跟踪器作为教师将其知识传授给意大利和德国的跟踪器，并取得了可喜的成果。

##### URL
[http://arxiv.org/abs/1808.06244](http://arxiv.org/abs/1808.06244)

##### PDF
[http://arxiv.org/pdf/1808.06244](http://arxiv.org/pdf/1808.06244)

