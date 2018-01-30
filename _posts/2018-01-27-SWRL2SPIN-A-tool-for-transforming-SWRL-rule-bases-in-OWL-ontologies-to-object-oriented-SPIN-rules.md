---
layout: post
title: "SWRL2SPIN: A tool for transforming SWRL rule bases in OWL ontologies to object-oriented SPIN rules"
date: 2018-01-27 09:36:22
categories: arXiv_AI
tags: arXiv_AI Ontology
author: Nick Bassiliades
mathjax: true
---

* content
{:toc}

##### Abstract
SWRL is a semantic web rule language that combines OWL ontologies with Horn Logic rules of the RuleML family of rule languages, extending the set of OWL axioms to include Horn-like rules. Being supported by the Prot\'eg\'e ontology editor as well as by popular rule engines and ontology reasoners, such as Jess, Drools and Pellet, SWRL has become a very popular choice for developing rule-based applications on top of ontologies. However, SWRL being around for more than 10 years now, it is most probable that it will never become a W3C standard; therefore, its scope is difficult to reach out to the industrial world. On the other hand, SPIN has become a de-facto industry standard to represent SPARQL rules and constraints on Semantic Web models, building on the widespread acceptance of the SPARQL query language for querying and processing Linked Open Data. In this paper, we argue that the life of existing SWRL rule-based ontology applications can be prolonged by being transformed into SPIN. To this end, we have developed a prototype tool using SWI-Prolog that takes as in-put an OWL ontology with a SWRL rule base and transforms SWRL rules into SPIN rules in the same ontology, taking into consideration the object-oriented scent of SPIN, i.e. linking rules to the appropriate ontology classes as derived by analyzing the rule conditions.

##### Abstract (translated by Google)
SWRL是一种语义网络规则语言，它将OWL本体与规则语言RuleML家族的Horn Logic规则相结合，将OWL公理集合扩展为包含类似Horn的规则。 SWRL在Prot本身的本体编辑器以及流行的规则引擎和本体reasoners（如Jess，Drools和Pellet）的支持下，已经成为在本体之上开发基于规则的应用程序的非常流行的选择。然而，SWRL已经有十多年的历史了，它很可能永远不会成为W3C的标准;因此，其范围很难接触到工业界。另一方面，在SPARQL查询语言被广泛接受用于查询和处理链接开放数据的基础上，SPIN已经成为事实上的行业标准来表示SPARQL对语义Web模型的规则和约束。在本文中，我们认为现有的基于SWRL规则的本体应用程序的生命周期可以通过转化为SPIN来延长。为此，我们开发了一个使用SWI-Prolog的原型工具，它将OWL本体与SWRL规则库相结合，并将SWRL规则转换为同一本体中的SPIN规则，同时考虑了SPIN的面向对象气味即通过分析规则条件将规则链接到适当的本体类。

##### URL
[http://arxiv.org/abs/1801.09061](http://arxiv.org/abs/1801.09061)

##### PDF
[http://arxiv.org/pdf/1801.09061](http://arxiv.org/pdf/1801.09061)

