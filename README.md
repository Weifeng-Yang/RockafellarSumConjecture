# Nonmaximal sums of maximally monotone operators under Rockafellar's constraint qualification

**Code and Lean formalization for [arXiv:2609.10487](https://arxiv.org/abs/2609.10487).**

## Introduction

We construct counterexamples to Rockafellar's sum conjecture in which two maximally monotone operators satisfy the interior-domain condition but their sum is not maximally monotone, thereby providing the complete disproof of the conjecture. We establish a general construction theorem that computes the entire monotone polar of a class of graphs and characterizes their maximal monotonicity by the nonexistence of solutions to explicit equations in the continuous dual. We also prove a pullback theorem that transfers counterexamples through bounded linear surjections. These theorems provide a systematic mechanism for generating entire families of counterexamples and lead to further structural consequences for the resulting operators. 
Specifically, we obtain four classes of counterexample families: weighted constructions with different curves, first operators with prescribed affine value dimensions, second operators obtained by positive rescaling and norm-continuous monotone perturbation with full domain, and counterexamples on further Banach spaces. The last class yields counterexamples on every Banach space containing a closed subspace isomorphic to $c_0$ or $\ell^1$, or admitting such a quotient. We also give explicit constructions on $c_0$ and standard $\ell^1$ that realize the construction and pullback mechanisms, respectively. 
We further determine the domain geometry and exact radial bounds of the constructed operators, characterize reflexivity by a fixed rank-one test in two classical classes of Banach spaces, identify maximal monotone extensions under surjective pullback, and compute exact Fitzpatrick identities. The appendices further extend these constructions to additional parameter and product families, nonlinear scalar and strictly monotone second operators, normal-cone and subdifferential partners, and examples with prescribed radial bounds, and more counterexample families. 

This package contains Lean proofs for the counterexample on $c_0$ and the general pullback lemma in the paper. 

## Lean proofs

The Lean directory contains the formalization of the counterexample on $c_0$ and a general theorem for transferring maximal monotonicity through a bounded linear surjection.

See lean/README.md for the formalization scope, main files, dependencies and build instructions.

## Author review and discussion record

After GPT-5.6 Sol completed adversarial auditing and hostile review of the complete construction theorem and the two counterexamples, the author manually reviewed these results from 6 to 8 September 2026. From 12 to 24 September 2026, the manuscript was substantially revised and reorganized around the general construction theorem and pullback result, which form the backbone of the paper, integrating the explicit counterexamples and several results that predate the general construction theorem and those counterexamples into a unified framework. The author manually reviewed and verified the reorganized manuscript and the integrated results throughout this period. Further manual review and verification are ongoing. 


## AI assistance

The author supplied earlier constructions, obstruction results, and a framework for positive rank-one perturbations, and guided their further development through iterative discussions with GPT-5.6 Sol. These discussions led to the general construction theorem and the detailed counterexample proofs. The model also assisted with Lean formalization of the counterexample on $c_0$ and the general pullback lemma, manuscript preparation, and adversarial checking. 
