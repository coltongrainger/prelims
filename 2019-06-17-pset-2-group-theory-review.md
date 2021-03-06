---
title: "Problem set 2: Group theory review"
author: Colton Grainger
date: 2019-06-17
revised:
---

## Definitions

Know how to define each of the following $4$ concepts in about 5 minutes. (See references in section 3.)

1. 
    - group
    - subgroup
    - order of an element
    - order of a group

2. 
    - group homomorphism
    - group isomorphism
    - kernel
    - image

7. 
	- (universal property of) quotient groups
	- short exact sequence of groups
	- $\mathrm{GL}_n(k)$ where $n \ge 2$ and $k$ is a field
	- $\mathrm{SL}_n(k)$ similarly

3. 
	- group action on a set $X$ 
	- $\mathrm{Aut}_{\mathrm{Set}}(X)$
	- $\mathrm{Stab}_{G}{A}$ where $A \subset X$
	- $\mathrm{Norm}_{G}{A}$ similarly

4. 
	- normalizer of a *subset* $A \subset G$
	- centralizer of $A \subset G$ similarly
    - conjugacy class of an element
	- normal subgroup

5. 
	- orbit of an element
	- index of a subgroup
	- center of a group
	- the group operation on $G/H$ when $H$ is normal

6. 
	- the symmetric group $S_n$
	- permutation representation
	- integer partition
	- cycle type

7. 
	- discriminant $\Delta$ for $S_n$ acting on $k[x_1, \ldots, x_n]$
	- sign of a permutation
	- the alternating group $A_n$
	- simple group 

8.
	- normal series
	- composition series
	- abelian subquotient
	- (universal property of) the commutator subgroup

9. 
	- group of automorphisms $\mathrm{Aut}(G)$ of a group $G$
	- group of outer automorphisms (similarly)
	- semi-direct product
	- split exact sequence

10. 
	- derived series
	- lower central series
	- upper central series
	- nilpotence class

11. 
	- $p$-group
	- Sylow $p$-subgroup
	- $n_{p_i}$ for primes $p_i$ dividing $\abs{G}$
	- elementary abelian group

12.
	- free group functor $\mathsf{Set} \to \mathsf{Grp}$
	- presentation of a group
	- free abelian group functor $\mathsf{Set} \to \mathsf{Ab}$
	- abelianization functor $\mathsf{Grp} \to \mathsf{Ab}$

## Main results

Know how to make quick arguments in support of the following. (Again, see references in section 3.)

1. Counting

	- State and prove Lagrange's theorem.
	- State and prove Cayley's theorem
	- State Cauchy's theorem.
	- State and prove the Orbit-Stabilizer theorem.
	- State and justify the class equation.
	- State Burnside's counting lemma.

1. Sylow theory

	- State the Sylow theorems.
	- List $5$ techniques for group classification from Sylow theory.
	- Prove there is no simple group of order $120$.
	- Prove that if $G$ is a group of order $pq$, with $p$ and $q$ distinct primes, then $G$ is not simple.

1. Abstruse results 

	- State Feit-Thompson's theorem.
	- State Burnside's theorem.
	- State P. Hall's theorem.
    - State Nielsen–Schreier's theorem

1. Abelian groups

	- State the FTFGAG. 
	- Argue that abelian groups are exactly $\ZZ$-modules. 
    - Use the FTFGAG to obtain a projective resolution for a finitely generated abelian group $G$.
	- Classify all abelian groups of order 1500.

1. Free groups

	- State and prove a universal property for free groups.
	- State and prove a universal property for the commutator subgroup.
	- Prove that a free abelian group is a free group if and only if it is cyclic.
	- Prove that the cyclic group of order $6$ is the group defined by the generators $a,b$ and the relations $a^2 = b^2 = a^{-1}b^{-1}ab = e$.
	- Let $F$ be a free group and let $N$ be the subgroup generated by the set $\{x^n : x \in F, n \text{ a fixed integer}\}.$ Prove that $N \triangleleft F$.

1. Nilpotence

	- Give at least $4$ equivalent criteria to recognize a nilpotent group.
	- Prove that a maximal subgroup of a finite nilpotent group has prime index.

1. Frattini's argument 

	- State Frattini's argument.

## Reading

Be familiar with the following.

- Tanaka and Conrad describe semi-direct products as split exact sequences. 

- Rotman proves a few technical results in group theory using module theory.

- For help with memorization, Peter has copied down relevant definitions and theorems from Dummit and Foote; his outline is included for the sake of completeness.


source | pages | summary
--- | --- | ---
Rock, 2018 | 13 pages | outline of Dummit and Foote, ch. 1--6
Tanaka, 2014 | 5 pages | semidirect products are split short exact sequences
Conrad, 2005 | 18 pages | splitting of short exact sequences for groups
Rotman, 1995 | ch. 7, pp. 154--171 | extensions, automorphism groups, and semidirect products 
Rotman, 1995 | ch. 10, pp. 307--320 | abelian groups, proof of the FTFGAG
