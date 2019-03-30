---
title: "Refinement of Structural Heuristics for Model Checking of Concurrent Programs through Data Mining"
collection: publications
permalink: /publication/2016-StructuralHeuristics
excerpt: 'Detecting concurrency bugs in multi-threaded programs through model-checking is complicated by the combinatorial explosion in the number of ways that different threads can be interleaved to produce different combinations of behaviors. In this work, patterns of read–write sequences are mined from a single execution of the target program to produce a quantitative, categorical model of thread behaviors. Experiments with a proof-of-concept implementation, built using Java Pathfinder and WEKA, demonstrate a novel structural heuristic that locates bugs faster and more reliably than a conventional counterpart.'
date: 2016-6-18
venue: 'Computer Languages, Systems and Structures: Special Issue on Search-based Techniques and their Hybridizations in Software Engineering'
paperurl: 'http://rmmilewi.github.io/files/structuralheuristics16.pdf'
citation: 'Reed Milewicz and Peter Pirkelbauer. Refinement of structural heuristics for model checking of concurrent programs through data mining. In Computer Languages, Systems and Structures: Special Issue on Search-based Techniques and their Hybridizations in Software Engineering, 2016.'
---

Detecting concurrency bugs in multi-threaded programs through model-checking is complicated by the combinatorial explosion in the number of ways that different threads can be interleaved to produce different combinations of behaviors. At the same time, concurrency bugs tend to be limited in their scope and scale due to the way in which concurrent programs are designed, and making visible the rules that govern the relationships between threads can help us to better identify which interleavings are worth investigating. In this work, patterns of read–write sequences are mined from a single execution of the target program to produce a quantitative, categorical model of thread behaviors. This model is exploited by a novel structural heuristic. Experiments with a proof-of-concept implementation, built using Java Pathfinder and WEKA, demonstrate that this heuristic locates bugs faster and more reliably than a conventional counterpart.

[Download paper here](http://rmmilewi.github.io/files/structuralheuristics16.pdf)

Recommended citation: Reed Milewicz and Peter Pirkelbauer. Refinement of structural heuristics for model checking of concurrent programs through data mining. In Computer Languages, Systems and Structures: Special Issue on Search-based Techniques and their Hybridizations in Software Engineering, 2016.