---
layout: post
title: "A Resourceful Reframing of Behavior Trees"
date: 2018-03-24 12:28:04
categories: arXiv_AI
tags: arXiv_AI
author: Chris Martens, Eric Butler, Joseph C. Osborn
mathjax: true
---

* content
{:toc}

##### Abstract
Designers of autonomous agents, whether in physical or virtual environments, need to express nondeterminisim, failure, and parallelism in behaviors, as well as accounting for synchronous coordination between agents. Behavior Trees are a semi-formalism deployed widely for this purpose in the games industry, but with challenges to scalability, reasoning, and reuse of common sub-behaviors. We present an alternative formulation of behavior trees through a language design perspective, giving a formal operational semantics, type system, and corresponding implementation. We express specifications for atomic behaviors as linear logic formulas describing how they transform the environment, and our type system uses linear sequent calculus to derive a compositional type assignment to behavior tree expressions. These types expose the conditions required for behaviors to succeed and allow abstraction over parameters to behaviors, enabling the development of behavior "building blocks" amenable to compositional reasoning and reuse.

##### Abstract (translated by Google)
自治代理的设计者无论是在物理环境还是在虚拟环境中，都需要表现行为中的非确定性，失败和并行性，并且要考虑代理之间的同步协调。行为树是游戏行业广泛使用的一种半形式化，但对可扩展性，推理和重用常见子行为都有挑战。我们通过语言设计的角度提出了一种行为树的替代形式，给出了一个正式的操作语义，类型系统和相应的实现。我们将原子行为的规范描述为描述它们如何转换环境的线性逻辑公式，并且我们的类型系统使用线性连续演算来为行为树表达式派生组合类型分配。这些类型公开了行为成功所需的条件，并允许将参数抽象为行为，从而使行为“构建块”的开发适合于组合推理和重用。

##### URL
[https://arxiv.org/abs/1803.09099](https://arxiv.org/abs/1803.09099)

##### PDF
[https://arxiv.org/pdf/1803.09099](https://arxiv.org/pdf/1803.09099)

