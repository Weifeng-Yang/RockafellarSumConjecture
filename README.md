# Nonmaximal sums of maximally monotone operators under Rockafellar's constraint qualification

**Code and Lean formalization for [arXiv:2609.10487](https://arxiv.org/abs/2609.10487).**

## Introduction

We construct counterexamples to Rockafellar's sum conjecture in which two maximally monotone operators satisfy the interior-domain condition but their sum is not maximally monotone. We give one counterexample on $c_0$ and another on $\ell^1$ with its usual norm. We establish a general construction theorem that computes the entire monotone polar of a class of graphs, gives a necessary and sufficient condition for their maximal monotonicity, and shows how a positive rank-one perturbation yields a nonmaximal sum under this condition. We verify the theorem's hypotheses and its maximality criterion on $c_0$, thereby obtaining a counterexample to the conjecture. Furthermore, we construct a bounded linear surjection from $\ell^1$ onto $c_0$ and use it to obtain the counterexample on $\ell^1$. 

This package contains Lean proofs for the counterexample on $c_0$ and the general pullback lemma in the paper. 

## Lean proofs

The Lean directory contains the formalization of the counterexample on $c_0$ and a general theorem for transferring maximal monotonicity through a bounded linear surjection.

See lean/README.md for the formalization scope, main files, dependencies and build instructions.

## Author review and discussion record

After GPT-5.6 Sol completed adversarial auditing and hostile review of the complete construction theorem and the two counterexamples, the author manually reviewed these results from 6 to 8 September 2026. From 12 to 24 September 2026, the manuscript was substantially revised and reorganized around the general construction theorem and pullback result, which form the backbone of the paper, integrating the explicit counterexamples and several results that predate the general construction theorem and those counterexamples into a unified framework. The author manually reviewed and verified the reorganized manuscript and the integrated results throughout this period. Further manual review and verification are ongoing. 


## AI assistance

The author supplied earlier constructions, obstruction results, and a framework for positive rank-one perturbations, and guided their further development through iterative discussions with GPT-5.6 Sol. These discussions led to the general construction theorem and the detailed counterexample proofs. The model also assisted with Lean formalization of the counterexample on $c_0$ and the general pullback lemma, manuscript preparation, and adversarial checking. 
