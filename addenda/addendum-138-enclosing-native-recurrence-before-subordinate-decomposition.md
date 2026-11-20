---
r2d_id: "addendum-138"
title: "Addendum 138 — Enclosing-Native Recurrence Before Subordinate Decomposition"
subtitle: "Primitive Compatibility, Native Identity, and Count-Preserving Recursive Replacement"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 138
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-20"
promotion_basis: "explicit_author_authorization_2026-11-20"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
date: "2026-11-14"
scope: "Unitless complete symmetric recurrence; nonhereditary enclosing admissibility; decomposition-relative primitivity; native identity versus compatible-extension profiles; exact count-preserving recursive reads; unresolved multi-boundary coherence"
---

# R²D Addendum 138 — Enclosing-Native Recurrence Before Subordinate Decomposition

*Primitive Compatibility, Native Identity, and Count-Preserving Recursive Replacement*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Part I (authoritative September 25, 2026 scientific revision), especially native macrostate identity, enclosing-compatible extension, possibility versus occurrence, and recursive replacement; Addenda 120, 122, and 135–137; companion Addendum 131.  
**Purpose:** Determine what makes a complete symmetric recurrence primitive at its own enclosing boundary, and exactly which possible-count consequences may survive a replacement that no longer distinguishes its subordinate presentations. No physical units, causal trajectory, realized recurrence rate, or directional-closure law enter the proofs.

## Abstract

The unitless development of symmetric recurrence in Addenda 135–137 classified complete possible incidence patterns and derived exact enclosing extension counts from stipulated compatibility conditions. Those constructions also raised a more fundamental question: must a complete enclosing recurrence inherit its native identity from a decomposition into subordinate cycles? Part I's boundary-first definitions suggest otherwise, but an exact distinction among component admissibility, native identity, and compatible extension is needed.

We show by finite counterexample that an enclosing owner may admit a complete reciprocal recurrence while refusing independent *complete-enclosing-record* status to each oriented component. A component nevertheless has positive compatible-extension count when it participates in an admitted complete record. Thus nonhereditary enclosing admissibility does not mean the component is impossible at its subordinate boundary. A recurrence can be additive-primitive **relative to the owner's admitted complete domain** despite having an algebraically decomposable subordinate incidence. The familiar theorem equating primitive balanced flows with simple directed cycles requires the stronger assumption that all balanced subincidences are themselves admitted.

Native recurrence identity and complete compatibility-response profiles are also independent. Two distinct native classes can have identical extension profiles, and two presentations of one native class can possess distinct profiles. We prove the exact factorization conditions for recovering one classification from the other and identify their joint classification as the least discriminating representation preserving both. Finally, we establish necessary-and-sufficient conditions for a selected enclosing compatibility property or complete response profile to survive a recursive read, distinguish this from aggregate count preservation by fiber weights, and exhibit a joining error when separately retained margins omit the enclosing compatibility pairing. These are theorems about **admitted possibilities**, not about which complete records physically occur. The actual coherence of compatibility across independently specified chains of three or more boundaries remains a further problem.

## 138.1. Logical order and count discipline

At boundary $J$, let $\mathfrak M_J$ be its domain of compatible formal microstates and let

$$
\pi_J:\mathfrak M_J\longrightarrow\mathcal M_J
\tag{138.1}
$$

be the *owner's native classification*. For an admitted native macrostate $i$,

$$
W_{J,i}=|\pi_J^{-1}(i)|
\tag{138.2}
$$

is native **possible multiplicity**. A larger owner $L$ supplies compatible enclosing extension count $\Theta_{L\mid J,i}$; where positive, the canon's across-boundary possibility is

$$
P_{J,i}=\ln\left(\frac{\Theta_{L\mid J,i}}{W_{J,i}}\right).
\tag{138.3}
$$

A formal complete recurrence pattern may itself be a candidate realization within such a count domain. Its possible-record component counts will be denoted $k_+,k_-$; these are **not** the observed $N_+,N_-$ of a realized recurrence-comparison record. A pattern in an admitted possible set does not establish physical occurrence, occupancy, or actual cycle frequency. A zero raw compatible-extension count is permitted; it has no finite logarithm.

Part I defines native identity by the boundary's classification, not by a persistent object reconstructed from smaller boundaries. The present theorems concern the *complete admitted relation of one owner* before asking how subordinate decompositions instantiate it.

## 138.2. Components, complete records, and compatible extensions

Let a subordinate presentation use three distinguishable response classes $Q=\{A,B,C\}$ and two oriented cyclic comparison patterns

$$
\gamma_+:A\to B\to C\to A,
\qquad
\gamma_-:A\to C\to B\to A.
\tag{138.4}
$$

These arrows specify possible ordered comparisons at the subordinate presentation, not physical trajectories. Let the enclosing owner $J$ admit precisely the complete paired class

$$
\mathcal C_J^{\rm pair}=\{h=\gamma_+\gamma_-\}
\tag{138.5}
$$

in a comparison whose completion is defined by the **whole reciprocal pair**. Its possible complete-record signature is $(k_+,k_-)=(1,1)$, hence $k_{\rm even}=2$ and $k_{\rm odd}=0$. This is a *possible structural symmetry*, not an equality of realized turbine counts.

In the declared one-record domain, the possible complete-record counts are

$$
W_J^{\rm complete}(\gamma_+)=0,
\quad W_J^{\rm complete}(\gamma_-)=0,
\quad W_J^{\rm complete}(h)=1.
\tag{138.6}
$$

The first two equalities mean **not independently complete at $J$**. They do not say that the shorter patterns are impossible subordinate responses.

Let a partial-record extension count be

$$
\Theta_J(s)=|\{h'\in\mathcal C_J^{\rm pair}:s\text{ is a specified compatible part of }h'\}|.
\tag{138.7}
$$

When a particular position of $\gamma_+$ or $\gamma_-$ within $h$ is specified, $\Theta_J(\gamma_+)=\Theta_J(\gamma_-)=1$. The same component is therefore **extendable** although not itself a complete $J$-native recurrence.

**Theorem 1 (component extension does not imply component completion).** For a declared finite enclosing complete-record domain, every specified part of an admitted complete record has at least one compatible extension. This does not imply that the part belongs to the set of independently admitted complete records.

**Proof.** The admitted containing record itself is an extension. The explicit construction (138.5)–(138.7) supplies a part with positive extension but zero independent complete-record count. $\square$

The result preserves Part I's distinction between a local possibility, its compatible enclosing extension, and the enclosing occurrence classification.

## 138.3. Nonhereditary symmetry and boundary-relative primitivity

To isolate the incidence logic, consider formal nonnegative component multiplicities $m=(k_+,k_-)\in\mathbb N_0^2$. One owner may declare the finite admitted complete-incidence set

$$
\mathcal Z_J=\{(0,0),(1,1),(2,2)\}.
\tag{138.8}
$$

The zero vector is a formal null configuration for decomposition comparisons; the nonzero members are complete symmetric possibilities. The set is closed under reversal $(k_+,k_-)\mapsto(k_-,k_+)$, but not every algebraic decomposition has admitted parts.

In particular,

$$
(1,1)=(1,0)+(0,1),
\tag{138.9}
$$

while neither one-sided component belongs to $\mathcal Z_J$.

**Theorem 2 (no universal decomposition compatibility).** Enclosing admissibility and orientation symmetry do not imply hereditary admissibility under additive decomposition.

**Proof.** The admitted vector $(1,1)$ and the excluded component vectors in (138.9) give a counterexample. $\square$

Define an admitted nonzero $m$ to be **$J$-indecomposable** when no expression $m=m_1+m_2$ exists with both $m_i$ nonzero and admitted in the selected $J$-complete incidence domain. Then $(1,1)$ is $J$-indecomposable, although its subordinate graph incidence consists of two distinguishable oriented cycles; $(2,2)$ is decomposable as $(1,1)+(1,1)$.

This definition is relative to the chosen owner's admitted domain. In contrast, if an owner admits **every** nonnegative balanced edge-incidence configuration of a finite directed comparison graph, its indecomposable nonzero elements are the simple directed cycles: every balanced configuration contains a simple cycle, subtraction leaves a nonnegative balanced remainder, and indecomposability forces that remainder to vanish. That familiar cycle theorem therefore uses **decomposition closure** of the admitted incidence domain.

**Corollary.** A complete recurrence may be primitive at $J$ without being a single simple cycle in a subordinate presentation. The primitive classification belongs to $J$ and cannot be inferred solely from subordinate incidence arithmetic.

## 138.4. First return, primitive incidence, and complete matching are different

A return to one chosen reference does not forbid repeated intermediate native response classes. For example,

$$
A\to B\to C\to B\to A
\tag{138.10}
$$

first returns to $A$ at its end, yet repeats $B$. Under the full balanced-incidence domain it decomposes into $A\to B\to A$ and $B\to C\to B$. Under a different enclosing owner the two components may not be independently complete, so the larger record may instead be $J$-primitive.

Likewise, Addendum 137's complete address–stage matching is stronger than a first return of the complete enclosing configuration. With three addresses and three response labels, fix an initial bijective configuration $p_0=(0,1,2)$; allow any two further *distinct* bijective configurations $p_1,p_2$ not equal to $p_0$, followed by a return to $p_0$. There are

$$
(3!-1)(3!-2)=5\cdot4=20
\tag{138.11}
$$

possible first-return configuration sequences, but only two also assign each response class exactly once to every address over the three comparison stages. The remaining eighteen repeat at least one subordinate address–response pairing.

Hence neither enclosing first return nor symmetric support derives complete matching. These are separately defined possible-record classifications.

## 138.5. Subordinate decomposition need not identify the complete relation

Let a specified owner admit the complete balanced aggregate containing all six oriented comparisons between $A,B,C$, each with formal incidence one. It can be presented as

$$
D_1=(A\to B\to C\to A)+(A\to C\to B\to A)
\tag{138.12}
$$

or as

$$
D_2=(A\to B\to A)+(A\to C\to A)+(B\to C\to B).
\tag{138.13}
$$

The aggregate edge-incidence count is equal. The decompositions differ in their complete constituent recurrence structure: two three-stage cycles versus three two-stage cycles.

The enclosing owner may identify the presentations in one native class or distinguish them. Equal aggregate incidence does not force either identification. Conversely, a native enclosing recurrence identity need not reconstruct a unique subordinate decomposition.

The correct logical order is

$$
\boxed{\text{enclosing native classification}\;\longrightarrow\;\text{its compatible subordinate presentations},}
\tag{138.14}
$$

where the arrow expresses *definition and compatibility*, not a chronological process or a rule for realized physical transitions.

## 138.6. Native identity and compatibility-response profile

Let $D_J$ be a finite set of admitted complete recurrence **presentations** under one specified owner. Let

$$
q_J:D_J\longrightarrow\mathcal M_J
\tag{138.15}
$$

be the owner's native recurrence classification. Its meaning is determined by $J$'s readable distinctions.

Choose a **specified** finite set $\mathcal K_J$ of enclosing contexts and a set $\mathcal Y_J$ of corresponding native response types. For each $(k,y)$ let $n_J(d;k,y)$ count the complete compatible extensions of presentation $d$ with that context and response. The complete profile *relative to this family* is

$$
\rho_J(d)=\big(n_J(d;k,y)\big)_{(k,y)\in\mathcal K_J\times\mathcal Y_J}.
\tag{138.16}
$$

An extension profile may contain more information than its sum. It is not automatically the native identity, and the word *complete* means complete for the **declared context family**, not all conceivable future observing boundaries.

**Countermodel A (equal profiles, distinct native identity).** Let $d_1=\gamma_+\gamma_-$ and $d_2=\gamma_-\gamma_+$ be distinguished by the owner according to their response ordering **relative to an owner-defined marked comparison stage**. Without that marked native reference, the two descriptions may be cyclic rotations of one pattern and cannot automatically be counted as distinct: $q_J(d_1)=R_1\ne R_2=q_J(d_2)$. Suppose both have exactly one compatible extension in each of two contexts $u,v$. Then

$$
\rho_J(d_1)=(1,1)=\rho_J(d_2),
\qquad q_J(d_1)\ne q_J(d_2).
\tag{138.17}
$$

The native distinction is genuine because the owner's read retains ordering; it is not merely a difference in invented label names.

**Countermodel B (same native identity, different profiles).** Another owner identifies both presentations as one native class $q_J(d_1)=q_J(d_2)=R$ but admits $(d_1,u)$ and $(d_2,v)$, excluding the cross-pairings. Then

$$
\rho_J(d_1)=(1,0),\qquad\rho_J(d_2)=(0,1).
\tag{138.18}
$$

The two presentations are distinct compatible microstates of one native recurrence macrostate, while their larger-context extension profiles differ.

These models prove that native recurrence identity and profile equality do not generally determine each other.

## 138.7. Theorem 3 — Exact factorization criteria

Write $\ker f$ for the equivalence relation $d\sim_f d'$ when $f(d)=f(d')$.

**Theorem 3 (two independent sufficiency tests).** For the declared $q_J$ and $\rho_J$:

1. Native identity is determined by the compatibility profile, $q_J=F\circ\rho_J$ for some $F$, **if and only if**
   $$\ker\rho_J\subseteq\ker q_J.$$
2. The compatibility profile is determined by native identity, $\rho_J=G\circ q_J$ for some $G$, **if and only if**
   $$\ker q_J\subseteq\ker\rho_J.$$
3. They contain exactly the same identifying information **if and only if** their kernels coincide.

**Proof.** Each statement is the finite fiber-constancy criterion: a function factors through another exactly when it is constant on that function's fibers. The third follows by applying the criterion in both directions. $\square$

Neither kernel inclusion follows from Part I's general boundary-count definitions. Symmetry of the admitted domain also does not force either: reversal can exchange two distinct native classes and corresponding contexts while preserving the whole compatibility relation.

## 138.8. Theorem 4 — The joint count-sufficient classification

Define

$$
\boxed{\Xi_J(d)=\big(q_J(d),\rho_J(d)\big).}
\tag{138.19}
$$

Its fibers are the intersections of native-identity fibers and compatibility-profile fibers:

$$
\ker\Xi_J=\ker q_J\cap\ker\rho_J.
\tag{138.20}
$$

**Theorem 4 (joint sufficiency).** Relative to the specified native read and context-response family, $\Xi_J$ is the *least discriminating* quotient through which both $q_J$ and $\rho_J$ factor. Any other classification that determines both must refine the $\Xi_J$ partition.

**Proof.** The two component maps are coordinate projections of $\Xi_J$. If another classification determines both, any records it identifies must agree in both components; its fibers are therefore contained in the joint fibers of $\Xi_J$. $\square$

This is a canonical construction **relative to the specified owner**, not a new intrinsic scalar or an R²D requirement that new boundaries inherit every component of $\Xi_J$.

For a native class $i$, its possible formal-microstate multiplicity remains the sum of the distinct compatible presentations it includes, with their correct native identification. The joint classification may refine it, but collapsing the presentations into one label does not automatically convert their original multiplicity into one. An exact count over a prior domain requires the appropriate fiber weights; the new boundary's **own** native count must be defined independently.

## 138.9. Theorem 5 — Which distinctions may disappear under a specified read?

Let $H$ be a finite complete **possible** comparison domain and

$$
r:H\longrightarrow Y
\tag{138.21}
$$

a specified recursive comparison/read that identifies some differences among its records. This map compares defined classes; it does not assert persistence of microstate identity between physical count domains. Let $K\subseteq H$ be a selected compatible-record property.

**Theorem 5 (classification preservation).** Membership in $K$ can be determined exactly from $r(h)$ alone if and only if

$$
\boxed{r(h)=r(h')\implies\big(h\in K\iff h'\in K\big),}
\tag{138.22}
$$

or, equivalently, $K$ is a union of complete $r$-fibers.

**Proof.** A read cannot distinguish different memberships within one fiber. Conversely, if each fiber is entirely inside or outside $K$, membership is a well-defined function of the read label. $\square$

More generally, a complete compatibility-response profile $\rho:H\to V$ survives *as a profile of each surviving label* if and only if

$$
\boxed{\ker r\subseteq\ker\rho.}
\tag{138.23}
$$

This is stronger than preservation of an aggregate count over a compatible class. If $K$ is a union of $r$-fibers and

$$
\omega(y)=|r^{-1}(y)|,
\tag{138.24}
$$

then the original possible-count cardinality satisfies

$$
\boxed{|K|=\sum_{y\in r(K)}\omega(y).}
\tag{138.25}
$$

For any context-specific original count one may similarly retain a *context-conditioned fiber multiplicity*. Such bookkeeping preserves the count of **that original comparison domain**, not necessarily the native multiplicity of a newly defined enclosing boundary. If a selected subset cuts through a fiber, its original aggregate count may still be computed by retaining more detailed conditional weights; membership of an individual record is then not readable from $r$ alone.

## 138.10. A finite distinction between aggregate counts and complete pairing

Let $H=\{d_1,d_2\}$ and suppose the owner admits exactly two extension pairs

$$
\mathcal E=\{(d_1,u),(d_2,v)\},
\tag{138.26}
$$

excluding $(d_1,v)$ and $(d_2,u)$. Define $r(d_1)=r(d_2)=R$.

The surviving label $R$ can carry the *aggregate* context counts

$$
\omega_u(R)=1,\qquad \omega_v(R)=1.
\tag{138.27}
$$

But those two numbers alone do not specify which original presentation was paired with which context. If a later calculation treats each forgotten presentation as independently compatible with each context, it introduces the two excluded cross-pairings. This is the spurious-join obstruction of Addendum 122 in a two-record form.

**Corollary.** Exact preservation of selected numerical enclosing possible counts does not entail reconstruction of the complete enclosing compatibility relation. The latter requires the original pairing information or a verified sufficient replacement interface.

## 138.11. What is universal about recursive replacement?

There is **no universal requirement** that every native distinction, every compatibility profile, or every original raw multiplicity survive a boundary change. Such a requirement would negate the purpose of recursive replacement.

There are, however, universal *conditional consistency criteria*:

- A property claimed to remain readable from the new label must be constant on the corresponding read fibers.
- Exact counts attributed to an earlier comparison domain must use its actual compatible multiplicities, not the number of labels after identification.
- A reconstruction of complete joint compatibility must preserve the enclosing owner's admitted pairings; equal marginals or equal aggregate counts alone are insufficient.
- Nothing about those possible-count conditions selects a physically realized record or occurrence count.

The conditions depend on **which specified count consequence the receiving comparison is claimed to retain**. Part I does not provide a universal list of consequences that every later boundary must preserve.

## 138.12. Multi-boundary composition: known mathematics and the open physical task

Suppose one *already specified common comparison owner* supplies maps

$$
H_0\overset{r_{01}}{\longrightarrow}H_1
\overset{r_{12}}{\longrightarrow}H_2.
\tag{138.28}
$$

The composite read $r_{02}=r_{12}\circ r_{01}$ is mathematically well defined. A selected invariant $I$ survives through both stages exactly when it is constant on the **composite** fibers; equivalently, $I=\overline I_2\circ r_{12}\circ r_{01}$ for some $\overline I_2$. This is a straightforward consequence of finite factorization, not a new primitive theorem.

The unresolved R²D problem is more demanding: **independently specified enclosing owners need not supply one shared domain, compatible native identifications, or path-independent pairings**. In that situation, merely composing stage labels can produce spurious complete possibilities. Establishing an admissible common comparison and preservation of its exact multiplicities across three or more native boundaries is a separate task. This addendum neither assumes nor proves it.

## 138.13. Results, limitations, and downstream implications

**Established, relative to the declared finite owners and read maps:**

1. A subordinate cycle can be an extendable part of an admitted reciprocal complete recurrence while not being independently complete at the enclosing boundary (Theorem 1).
2. Symmetric enclosing admissibility does not imply admissibility of every algebraic constituent (Theorem 2).
3. Additive primitivity belongs to the owner's admitted complete domain; a simple-cycle primitive theorem requires stronger decomposition closure.
4. First return of an enclosing configuration is weaker than nonrepetition of all subordinate response pairings, and both are weaker than independently specified complete matching.
5. Equal aggregate incidence or equal context-response counts need not define native recurrence identity; equal native identity need not imply equal larger-context extension profiles.
6. The exact factorization criteria for recovering native identity from profile or profile from native identity are independent (Theorem 3).
7. The joint map $\Xi_J=(q_J,\rho_J)$ is the least discriminating classification preserving both specified kinds of information (Theorem 4).
8. Selected compatibility classes or profiles survive a recursive read precisely under the appropriate fiber-constancy conditions; original possible counts may be retained using correct fiber multiplicities (Theorem 5).
9. Correct aggregate counts do not suffice to reconstruct all joint compatibility pairings.

**Not established:** A uniquely selected universal native recurrence quotient, a universal primitive decomposition rule, universal preservation of original possible multiplicity at a new boundary, coherence of independently specified owners across arbitrary recursive paths, any realized frequency or occurrence, or a physical thermal, quantum, or gravitational calibration.

These qualifications are particularly important to the research following Addenda 131–134. At a putative quantum horizon, a recurrence-related response classification may survive even when subordinate beat decomposition is unreadable. At a putative gravitational horizon, a retained distinction may survive while the enclosing recurrence classification does not. The present theorems say how to audit those claims as **unitless compatibility and readability statements**. They do not derive light, $c$, mass, or $mc^2$.

## Conclusion

The complete identity of a symmetric recurrence belongs to its enclosing boundary. It need not be assembled from simple subordinate cycles, and its constituent cycles need not have independently admissible complete status at the same boundary. Two distinct native recurrence classes may share all specified external compatible-extension profiles; conversely, two presentations of one native recurrence may have different larger-context compatibilities.

The minimal complete representation required to preserve both is the *owner-relative joint classification*

$$
\boxed{\Xi_J=(q_J,\rho_J).}
\tag{138.29}
$$

When recursive replacement makes subordinate presentations unreadable, precisely those specified count properties constant on its read fibers remain reconstructable from the surviving label alone. The correct possible counts of a specified earlier domain may still be retained through fiber multiplicities, but they are not automatically the new boundary's native counts. No such operation determines which possibility physically occurs.

The next target is **exact composition of possibility-preserving native comparisons through three or more independently defined enclosing owners**. The challenge is not algebraic composition of functions; it is construction of the common enclosing-compatible relation that makes those compositions admissible without carrying persistent subordinate object identity or manufacturing spurious joint possibilities.

## References

1. R²D Part I — *A Theory of Dimensionless Recursive Counting*. Authoritative scientific revision September 25, 2026: native macrostate classification, compatible multiplicity, possibility, recurrence comparison, and recursive replacement. https://r2dscience.github.io/r2d-canon-publication/canon/part-i.html
2. R²D Part II — *Joint Readability of Recurrence and Distinguishability*. Downstream thermodynamic physical calibration. https://r2dscience.github.io/r2d-canon-publication/canon/part-ii.html
3. R²D Part III — *The Recursive Clock and the Horizons of Readability*. Complementary joint-readability limits. https://r2dscience.github.io/r2d-canon-publication/canon/part-iii.html
4. R²D Part IV — *Projection: The Physics Constructed from What Remains*. Domain-specific physical projections. https://r2dscience.github.io/r2d-canon-publication/canon/part-iv.html
5. R²D Addendum 120 — *Boundary-Owned Identity and the Algebra of Recursive Replacement*; Addendum 122 — across-boundary enclosing compatibility and composition.
6. R²D Addendum 131 — *Symmetric Background Before Turbine Recurrence*.
7. R²D Addendum 135 — *The Admissible Structures of Symmetric Recurrence*.
8. R²D Addendum 136 — *Native Identification Constrains Symmetric Recurrence*.
9. R²D Addendum 137 — *Enclosing Compatibility Determines Cross-Stage Recurrence*.
