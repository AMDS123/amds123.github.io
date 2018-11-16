---
layout: post
title: "Implementing a Portable Clinical NLP System with a Common Data Model - a Lisp Perspective"
date: 2018-11-15 04:58:21
categories: arXiv_AI
tags: arXiv_AI Relation_Extraction Relation
author: Yuan Luo, Peter Szolovits
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a Lisp architecture for a portable NLP system, termed LAPNLP, for processing clinical notes. LAPNLP integrates multiple standard, customized and in-house developed NLP tools. Our system facilitates portability across different institutions and data systems by incorporating an enriched Common Data Model (CDM) to standardize necessary data elements. It utilizes UMLS to perform domain adaptation when integrating generic domain NLP tools. It also features stand-off annotations that are specified by positional reference to the original document. We built an interval tree based search engine to efficiently query and retrieve the stand-off annotations by specifying positional requirements. We also developed a utility to convert an inline annotation format to stand-off annotations to enable the reuse of clinical text datasets with inline annotations. We experimented with our system on several NLP facilitated tasks including computational phenotyping for lymphoma patients and semantic relation extraction for clinical notes. These experiments showcased the broader applicability and utility of LAPNLP.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.06179](http://arxiv.org/abs/1811.06179)

##### PDF
[http://arxiv.org/pdf/1811.06179](http://arxiv.org/pdf/1811.06179)

