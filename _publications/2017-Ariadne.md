---
title: "Ariadne: Hybridizing Directed Model Checking and Static Analysis."
collection: publications
permalink: /publication/2017-Ariadne
excerpt: 'We introduce an open-source tool, Ariadne, which translates reports of suspected race conditions of a static analyzer (Petablox) to instrumentation using a source-to-source compiler (ROSE) that can be exploited by a model checker (Java Pathfinder). We detail the algorithm used, present experimental results, and outline directions for future research.'
date: 2017-03-12
venue: '10th IEEE International Conference on Software Testing, Verification and Validation'
paperurl: 'http://rmmilewi.github.io/files/icst17.pdf'
citation: 'Reed Milewicz and Peter Pirkelbauer: Ariadne: Hybridizing Directed Model Checking and Static Analysis. In 10th IEEE International Conference on Software Testing, Verification and Validation, (ICST'17), pp 442-447, 2017.'
---
While directed model checking has proven to be a powerful tool in the fight against concurrency bugs, scalability remains a concern due to the combinatorial explosion in size of the state space. Overcoming that combinatorial explosion requires the selection and/or parameterization of meta*-heuristics, but we are left with a persistent problem of having to provide or compute specialized knowledge of the program under consideration, and this limits the practical value of the technique. To circumvent that, this paper investigates directed model checking as a platform for the synthesis of results from other analyses. We introduce an open-source tool, Ariadne, which translates reports of suspected race conditions of a static analyzer (Petablox) to instrumentation using a source-to-source compiler (ROSE) that can be exploited by a model checker (Java Pathfinder). We detail the algorithm used, present experimental results, and outline directions for future research.

[Download paper here](http://rmmilewi.github.io/files/icst17.pdf)

Recommended citation: Reed Milewicz and Peter Pirkelbauer: Ariadne: Hybridizing Directed Model Checking and Static Analysis. In 10th IEEE International Conference on Software Testing, Verification and Validation, (ICST '17), pp 442-447, 2017.