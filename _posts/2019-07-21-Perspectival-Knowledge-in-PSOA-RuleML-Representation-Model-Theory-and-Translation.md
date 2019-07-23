---
layout: post
title: "Perspectival Knowledge in PSOA RuleML: Representation, Model Theory, and Translation"
date: 2019-07-21 17:58:15
categories: arXiv_AI
tags: arXiv_AI Knowledge Relation
author: Harold Boley, Gen Zou
mathjax: true
---

* content
{:toc}

##### Abstract
In Positional-Slotted Object-Applicative (PSOA) RuleML, a predicate application (atom) can have an Object IDentifier (OID) and descriptors that may be positional arguments (tuples) or attribute-value pairs (slots). PSOA RuleML explicitly specifies for each descriptor whether it is to be interpreted under the perspective of the predicate in whose scope it occurs. This predicate-dependency dimension refines the space between oidless, positional atoms (relationships) and oidful, slotted atoms (framepoints): While relationships use only a predicate-scope-sensitive (predicate-dependent) tuple and framepoints use only predicate-scope-insensitive (predicate-independent) slots, PSOA uses a systematics of orthogonal constructs also permitting atoms with (predicate-)independent tuples and atoms with (predicate-)dependent slots. This supports data and knowledge representation where a slot attribute can have different values depending on the predicate. PSOA thus extends object-oriented multi-membership and multiple inheritance. Based on objectification, PSOA laws are given: Besides unscoping and centralization, the semantic restriction and transformation of describution permits rescoping of one atom's independent descriptors to another atom with the same OID but a different predicate. For inheritance, default descriptors are realized by rules. On top of a metamodel and a Grailog visualization, PSOA's atom systematics for facts, queries, and rules is explained. The presentation and (XML-)serialization syntaxes of PSOA RuleML are introduced. Its model-theoretic semantics is formalized by extending the interpretation functions for dependent descriptors. The open-source PSOATransRun system realizes PSOA RuleML by a translator to runtime predicates, including for dependent tuples (prdtupterm) and slots (prdsloterm). Our tests show efficiency advantages of dependent and tupled modeling.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1712.02869](http://arxiv.org/abs/1712.02869)

##### PDF
[http://arxiv.org/pdf/1712.02869](http://arxiv.org/pdf/1712.02869)

