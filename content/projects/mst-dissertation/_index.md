---
title: "On Simulated Annealing, Metropolis algorithm and Minimum Spanning Trees"
date: 2024-06-10
tags: ["Optimization", "Simulated Annealing", "MST"]
cover:
  image: "diss.png"
  alt: "MST diagram"
---
My BSc [dissertation in Mathematics.](/files/diss_template.pdf)

The Metropolis Algorithm is one of the earliest and most fundamental Markov Chain Monte Carlo (MCMC) methods. The algorithm can be adapted to search for optimal solutions in a combinatorial optimisation problem, with a fixed parameter (temperature) to control for acceptance probabilities. Simulated annealing is Metropolis with a varied temperature.

In this dissertation, I gave an overview of two papers: one by Wegener(2005), covering how the Metropolis algorithm with arbitrary fixed temperature is unsuccessful on instances of the minimum spanning tree problem, whereas Simulated Annealing with a geometric cooling schedule is successful; the other by Doerr, Rajabi, and Witt (2022), covering that Simulated Annealing with an appropriate cooling schedule computes arbitrarily tight constant-factor approximations to the minimum spanning tree problem in polynomial time, which is a result conjectured by Wegener (2005).

I revisited and provided detailed proofs of the key results from Wegener (2005) and Doerr et al. (2022) on the performance of Simulated Annealing for the Minimum Spanning Tree problem. I strengthened their analyses by deriving explicit probabilistic bounds on the success probability, obtained via novel estimates on the hitting time of a non-i.i.d. stochastic process arising from the algorithm's dynamics.

My work was supervised by [Prof. Graham Brightwell](https://en.wikipedia.org/wiki/Graham_Brightwell).