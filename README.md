# Nonmaximal sums of maximally monotone operators under Rockafellar's constraint qualification

**Code and Lean formalization for [arXiv:2609.10487](https://arxiv.org/abs/2609.10487).**

## Introduction

We construct counterexamples to Rockafellar's sum conjecture in which two maximally monotone operators satisfy the interior-domain condition but their sum is not maximally monotone. We give one counterexample on $c_0$ and another on $\ell^1$ with its usual norm. We establish a general construction theorem that computes the entire monotone polar of a class of graphs, gives a necessary and sufficient condition for their maximal monotonicity, and shows how a positive rank-one perturbation yields a nonmaximal sum under this condition. We verify the theorem's hypotheses and its maximality criterion on $c_0$, thereby obtaining a counterexample to the conjecture. Furthermore, we construct a bounded linear surjection from $\ell^1$ onto $c_0$ and use it to obtain the counterexample on $\ell^1$. 

This package contains Lean proofs for the counterexample on $c_0$ and the general pullback lemma in the paper. 

## Lean proofs

The Lean directory contains the formalization of the counterexample on $c_0$ and a general theorem for transferring maximal monotonicity through a bounded linear surjection.

See lean/README.md for the formalization scope, main files, dependencies and build instructions.

## Author review and discussion record

The general construction theorem and the counterexamples had already been obtained by 6 September 2026. During 6–8 September 2026 (UTC+8), the author manually reviewed these results and their proofs, with Codex assisting in checks and discussions. The manuscript was subsequently submitted to arXiv on 9 September 2026 (UTC).

The [author–Codex review conversations](https://chatgpt.com/s/cx_6ab0cf9a5bd08191ad4fd249da90929d) are shared to make this review process available for readers to inspect and study alongside the paper and Lean formalization. Readers are welcome to examine the arguments, raise questions, and report any errors or points requiring clarification.


## AI assistance

The author supplied earlier constructions, obstruction results, and a framework for positive rank-one perturbations, and guided their further development through iterative discussions with GPT-5.6 Sol. These discussions led to the general construction theorem and the detailed counterexample proofs. The model also assisted with Lean formalization of the counterexample on $c_0$ and the general pullback lemma, manuscript preparation, and adversarial checking. 
