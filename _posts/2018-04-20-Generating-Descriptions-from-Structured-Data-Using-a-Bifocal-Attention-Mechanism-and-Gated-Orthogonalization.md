---
layout: post
title: "Generating Descriptions from Structured Data Using a Bifocal Attention Mechanism and Gated Orthogonalization"
date: 2018-04-20 18:30:18
categories: arXiv_AI
tags: arXiv_AI Attention
author: Preksha Nema, Shreyas Shetty, Parag Jain, Anirban Laha, Karthik Sankaranarayanan, Mitesh M. Khapra
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we focus on the task of generating natural language descriptions from a structured table of facts containing fields (such as nationality, occupation, etc) and values (such as Indian, actor, director, etc). One simple choice is to treat the table as a sequence of fields and values and then use a standard seq2seq model for this task. However, such a model is too generic and does not exploit task-specific characteristics. For example, while generating descriptions from a table, a human would attend to information at two levels: (i) the fields (macro level) and (ii) the values within the field (micro level). Further, a human would continue attending to a field for a few timesteps till all the information from that field has been rendered and then never return back to this field (because there is nothing left to say about it). To capture this behavior we use (i) a fused bifocal attention mechanism which exploits and combines this micro and macro level information and (ii) a gated orthogonalization mechanism which tries to ensure that a field is remembered for a few time steps and then forgotten. We experiment with a recently released dataset which contains fact tables about people and their corresponding one line biographical descriptions in English. In addition, we also introduce two similar datasets for French and German. Our experiments show that the proposed model gives 21% relative improvement over a recently proposed state of the art method and 10% relative improvement over basic seq2seq models. The code and the datasets developed as a part of this work are publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.07789](http://arxiv.org/abs/1804.07789)

##### PDF
[http://arxiv.org/pdf/1804.07789](http://arxiv.org/pdf/1804.07789)

