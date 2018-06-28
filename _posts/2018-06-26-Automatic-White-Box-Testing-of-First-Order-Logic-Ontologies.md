---
layout: post
title: "Automatic White-Box Testing of First-Order Logic Ontologies"
date: 2018-06-26 19:23:02
categories: arXiv_AI
tags: arXiv_AI Ontology Inference Detection
author: Javier &#xc1;lvez, Montserrat Hermo, Paqui Lucio, German Rigau
mathjax: true
---

* content
{:toc}

##### Abstract
Formal ontologies are axiomatizations in a logic-based formalism. The development of formal ontologies, and their important role in the Semantic Web area, is generating considerable research on the use of automated reasoning techniques and tools that help in ontology engineering. One of the main aims is to refine and to improve axiomatizations for enabling automated reasoning tools to efficiently infer reliable information. Defects in the axiomatization can not only cause wrong inferences, but can also hinder the inference of expected information, either by increasing the computational cost of, or even preventing, the inference. In this paper, we introduce a novel, fully automatic white-box testing framework for first-order logic ontologies. Our methodology is based on the detection of inference-based redundancies in the given axiomatization. The application of the proposed testing method is fully automatic since a) the automated generation of tests is guided only by the syntax of axioms and b) the evaluation of tests is performed by automated theorem provers. Our proposal enables the detection of defects and serves to certify the grade of suitability --for reasoning purposes-- of every axiom. We formally define the set of tests that are generated from any axiom and prove that every test is logically related to redundancies in the axiom from which the test has been generated. We have implemented our method and used this implementation to automatically detect several non-trivial defects that were hidden in various first-order logic ontologies. Throughout the paper we provide illustrative examples of these defects, explain how they were found, and how each proof --given by an automated theorem-prover-- provides useful hints on the nature of each defect. Additionally, by correcting all the detected defects, we have obtained an improved version of one of the tested ontologies: Adimen-SUMO.

##### Abstract (translated by Google)
正式的本体论是基于逻辑的形式主义的公理化。正式本体的发展以及它们在语义Web领域的重要作用正在产生大量关于使用自动推理技术和工具来帮助本体工程的研究。其中一个主要目标是改进和改进公理化，使自动推理工具能够有效推断可靠的信息。公理化中的缺陷不仅可能导致错误的推论，而且也可能通过增加推理的计算成本或者甚至阻止推理而阻碍期望信息的推断。在本文中，我们介绍了一种用于一阶逻辑本体的全新自动白盒测试框架。我们的方法基于在给定公理化中检测基于推理的冗余。所提出的测试方法的应用是完全自动的，因为a）测试的自动化生成仅由公理语法指导，并且b）测试的评估由自动化定理证明器执行。我们的建议可以检测缺陷，并用来证明每个公理的适用性等级 - 为了推理的目的。我们正式定义从任何公理生成的一组测试，并证明每个测试都与测试产生的公理中的冗余在逻辑上相关。我们已经实现了我们的方法并使用这个实现来自动检测隐藏在各种一阶逻辑本体中的一些非平凡的缺陷。在整篇论文中，我们提供了这些缺陷的说明性例子，解释它们是如何被发现的，以及如何通过自动化定理 - 证明者提供的每个证明为每个缺陷的性质提供有用的提示。此外，通过纠正所有检测到的缺陷，我们获得了一个经过测试的本体的改进版本：Adimen-SUMO。

##### URL
[http://arxiv.org/abs/1705.10219](http://arxiv.org/abs/1705.10219)

##### PDF
[http://arxiv.org/pdf/1705.10219](http://arxiv.org/pdf/1705.10219)

