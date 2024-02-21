---
layout: single
author_profile: true
sidebar:
  nav: "main"
title:  "[PGM] 2.2 Graphs"
categories:
    - Basics of Graphical Model
tags:
    - [Graphical Model]

toc: true
toc_sticky: true

date: 2024-02-20
use_math: true
---

#### 2.2.1 Nodes & Edges

- Graph $\mathcal{K}$ = ($\mathcal{X}$, $\mathcal{E}$) 에서, $\mathcal{X}$는 node set, $\mathcal{E}$는 edge set.
- $X_i \rightarrow X_j \in \mathcal{E}$에서, $X_i$는 parent, $X_j$는 child.
- degree: 한 node에서 나가는 edge의 수  /  indegree: 한 node로 들어오는 edge의 수

<br/>

#### 2.2.2 Subgraphs

- Induced Subgraph: subgraph들 중 edge를 모두 살린 graph.
- Complete Subgraph: 모든 두 node들이 어떠한 edge에 의해 연결된 graph.

<br/>

#### 2.2.3 Paths & Trails

- Path: 하나라도 node와 node 사이에 edge가 있고 한 손 그리기가 되면, $X_1, ..., X_k$가 path를 이룬다고 한다.
- Trail: path와 유사한 개념이지만 한 손 그리기로 모든 node에 다다를 수 없으면 trail.
- 
