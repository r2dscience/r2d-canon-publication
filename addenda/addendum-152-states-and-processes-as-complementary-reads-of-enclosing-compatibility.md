---
r2d_id: "addendum-152"
title: "Addendum 152 — States and Processes as Complementary Reads of Enclosing Compatibility"
subtitle: "Finite Event Algebras, Evolution Counts, and Conditional Reconstruction of State Identity"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 152
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-20"
promotion_basis: "explicit_author_authorization_2026-11-20"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
date: "2026-11-19"
scope: "Finite boundary-indexed measurable event algebras; distinct state and process counting measures; exact multi-step process counts; process-first recovery of native state classes under complete composability; non-backtracking counterowner; incompatibility of naive uniform path probabilities across comparison lengths; relation to canonical R2D count types"
---

# R²D Addendum 152 — States and Processes as Complementary Reads of Enclosing Compatibility

*Finite Event Algebras, Evolution Counts, and Conditional Reconstruction of State Identity*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Parts I–IV (September 25, 2026); Addenda 105, 120, 122, 124–125, 131, 135–140, and 150–151.

## Abstract

The primitive R²D formalism defines states relative to a count boundary: compatible joint realizations belong to its native domain, and a readable classification partitions that domain into macrostate fibers. A separate question concerns *processes*: which complete ordered comparisons among those classifications are admitted by an enclosing owner, and what is counted when the objects are complete processes rather than instantaneous native states? These questions arise in mathematical reconstructions that seek foundations for entropy, measures, states, and dynamics without treating a chosen physical trajectory or stochastic kernel as primitive.

We construct finite state and process event algebras from one explicitly specified molecule–reservoir compatibility, previously established in Addendum 150. It contains 35 compatible native states in molecular classes of sizes 20 and 15. Its reciprocal exchange relation contains 60 undirected edges or 120 oriented one-step process incidences, divided 60 and 60 by molecular source class. We calculate the exact number of complete, adjacency-composable $T$-step process records: their source-class multiplicities alternate between the ratios $20:15$ for even $T$ and $1:1$ for odd $T$. State counting and process counting are therefore distinct measures on different enclosing-owned count domains.

We then reverse the construction. Given only the distinguishable one-step incidences and their complete two-step composability relation, a predecessor-profile equivalence recovers exactly the original 35 state classes, including 20 classes of size three and 15 of size four. This is a finite process-first reconstruction of state identity, conditional on full composition at common intermediate native states and nonempty incoming/outgoing incidence. A second owner with exactly the same states and one-step incidences but excluding immediate reversal admits only 300 instead of 420 two-step records; the same predecessor-profile reconstruction no longer recovers the original 35 classes. Consequently, state/process equivalence requires the complete enclosing composition relation and cannot be inferred from state and one-step incidence counts alone.

Finally, although every finite complete-process domain admits a power-set $\sigma$-algebra and additive counting measure, normalizing the counting measure independently for different process lengths does not generally produce a projectively consistent probability process. This establishes a precise separation among possible evolutions, realized occurrences, and stochastic representations. The results are finite mathematical existence and counterexample statements, not derivations of topology, classical Liouville measure, quantum nonadditivity, or Hamiltonian mechanics.

---

## 152.1. The question and the prior canon

Carcassi's mathematical reconstruction question can be stated without presupposing a physical dynamics: **What are the event spaces and measures of states and of complete processes, and under which enclosing compatibility can each description reconstruct the other?**

Part I gives a native state domain $\mathfrak M_B$ of compatible joint subordinate realizations and a readable map $\pi_B:\mathfrak M_B\to\mathcal M_B$. Its native multiplicity is

$$
W_B(i)=|\pi_B^{-1}(i)|.
\tag{152.1}
$$

An enclosing owner $J$ supplies compatible extension counts $\Theta_{J\mid B,i}$ and possibility

$$
P_{B,i}=\ln\!\left(\frac{\Theta_{J\mid B,i}}{W_B(i)}\right).
\tag{152.2}
$$

Possible multiplicity $W$, enclosing extension $\Theta$, realized state occurrence $\nu$, structural occupancy $c$, opposed-leg occurrence, and completed whole-closure recurrence $N_{\mathcal C}$ are distinct count types. Addenda 122 and 139 establish that a complete enclosing comparison need not be reconstructible by joining separately admitted shorter comparisons. Addendum 125 separates realized configuration occurrences from completed closures. Here we construct **possible** event spaces and count measures first; no occurrence or physical timing is inferred from these counts.

The mathematical constructions below are standard finite-set, graph, and measure theory. Their purpose is to specify the concrete count objects and the exact boundary-dependent conditions of an R²D representation, not to assert novelty for those abstract theorems.

## 152.2. One finite native state owner

Following Addendum 150, let one enclosing owner $J$ distinguish a binary molecular class $q\in\{0,1\}$ and six binary reservoir distinctions $b_i\in\{0,1\}$. Specify the complete compatible state domain

$$
\boxed{\Omega_J=\{(q,b_1,\ldots,b_6)\in\{0,1\}^7:q+\textstyle\sum_{i=1}^{6}b_i=3\}.}
\tag{152.3}
$$

The molecular read $m:\Omega_J\to\{0,1\}$ is $m(q,\mathbf b)=q$. Its fibers are $H_0=m^{-1}(0)$ and $H_1=m^{-1}(1)$. Direct binomial enumeration gives

$$
\boxed{|H_0|=\binom63=20,\qquad |H_1|=\binom62=15,\qquad |\Omega_J|=35.}
\tag{152.4}
$$

These states are complete native possible records **at $J$**. Their identities need not persist as unchanged native states after recursive replacement. The labels do not introduce a primitive molecular particle, physical energy unit, or clock.

## 152.3. State event algebras and boundary-readable events

As a finite set, $\Omega_J$ admits the full event algebra and counting measure

$$
\boxed{\Sigma_J=\mathcal P(\Omega_J),\qquad\mu_J(E)=|E|\quad(E\subseteq\Omega_J).}
\tag{152.5}
$$

The measure is additive on disjoint unions and hence $\sigma$-additive, because the underlying domain is finite. The molecule's boundary reads only the classification $m$. Its readable event algebra is the pullback

$$
\boxed{\Sigma_M=m^{-1}\!\left(\mathcal P(\{0,1\})\right)
=\{\varnothing,H_0,H_1,\Omega_J\}.}
\tag{152.6}
$$

The induced count values are $\mu_J(H_0)=20$ and $\mu_J(H_1)=15$. The full algebra describes mathematical distinctions in the owner's complete native domain; $\Sigma_M$ describes only those events decidable from the selected molecular read. The choice of a finite power-set algebra is mathematically canonical given the specified finite owner. It is not yet an operational derivation of a topology or of arbitrary continuum $\sigma$-algebras.

## 152.4. A distinct domain of one-step process incidences

Now define the enclosingly admitted **one-step exchange relation** $\Gamma_J\subseteq\Omega_J\times\Omega_J$ as follows:

- If $x=(0,\mathbf b)$, an admitted successor $y=(1,\mathbf b')$ is obtained by replacing exactly one reservoir coordinate $b_i=1$ with $b'_i=0$.
- The reverse exchange is also admitted. No other ordered pairs belong to $\Gamma_J$.

These ordered pairs are *possible process incidences*. They are not realized microscopic transitions. Each $x\in H_0$ admits three outgoing incidences; each $x\in H_1$ admits four. The oriented incidence domain

$$
\mathcal A_J:=\Gamma_J
\tag{152.7}
$$

therefore contains

$$
\boxed{|\mathcal A_J|=20(3)+15(4)=120.}
\tag{152.8}
$$

It has 60 incidences in each molecular direction. The one-step process owner $J_{[0,1]}$ admits $\mathcal A_J$ as its possible complete comparison records. Its event algebra and possible-process counting measure are

$$
\boxed{\Sigma_J^{(1)}=\mathcal P(\mathcal A_J),\qquad\mu_J^{(1)}(F)=|F|.}
\tag{152.9}
$$

Source and target maps $s,t:\mathcal A_J\to\Omega_J$ read the endpoints of a complete *comparison record*; they do not claim that one subordinate physical microstate remains identifiable along a measured trajectory. Their source-class fibers have counts

$$
\boxed{\mu_J^{(1)}(s^{-1}(H_0))=60
=\mu_J^{(1)}(s^{-1}(H_1)).}
\tag{152.10}
$$

**Proposition 152.1 — Native state counts differ from possible process counts.** The same enclosing compatibility admits unequal native class counts $20:15$ but equal outgoing one-step process counts $60:60$.

**Proof.** Equations (152.4) and (152.10) count different domains. Each state's compatible continuation degree weights its contribution to the process domain: $20\cdot3=15\cdot4=60$. $\square$

In particular $\mu_J^{(1)}\circ s^{-1}$ is a degree-weighted pushforward of process count, not $\mu_J$. A process count is not a new formula for the native multiplicity $W_J$, and its logarithm is not automatically Part I's canonical possibility $P=\ln(\Theta/W)$.

## 152.5. Complete process domains and multi-step counts

For each comparison length $T\ge0$, explicitly define a **separate complete process owner** $J_{[0,T]}$ that admits every sequence composable through its consecutive exchange incidences:

$$
\boxed{\Omega_J^{(T)}=\{(x_0,\ldots,x_T)\in\Omega_J^{T+1}:(x_{r-1},x_r)\in\Gamma_J\text{ for }1\le r\le T\}.}
\tag{152.11}
$$

For $T=0$, this is the original state domain. For $T=1$, it is canonically identified with $\mathcal A_J$. This **adjacency-complete** choice is a declared property of these process owners: it is not a theorem that every R²D owner permits arbitrary joins of locally admitted exchanges.

Let $A_T$ and $B_T$ be the number of admitted complete $T$-step records beginning in $H_0$ and $H_1$. Every step exchanges the molecular class; the respective outgoing degrees are three and four.

**Theorem 152.2 — Exact finite evolution multiplicities.** For every integer $T\ge0$,

$$
\boxed{\begin{aligned}
A_T&=20\,3^{\lceil T/2\rceil}4^{\lfloor T/2\rfloor},\\
B_T&=15\,4^{\lceil T/2\rceil}3^{\lfloor T/2\rfloor}.
\end{aligned}}
\tag{152.12}
$$

Consequently,

$$
\boxed{\frac{B_T}{A_T}=\begin{cases}3/4,&T\text{ even},\\1,&T\text{ odd}.
\end{cases}}
\tag{152.13}
$$

**Proof.** Starting in $H_0$, the first, third, and subsequent odd-numbered steps each have three admitted continuations, while even-numbered steps each have four. The roles reverse for a start in $H_1$. Multiplying these factors by the initial cardinalities gives (152.12). The ratio simplifies using $15\cdot4=20\cdot3$; for every two additional steps, both classes receive the common factor $12$. $\square$

| Process steps $T$ | Start in $H_0$ | Start in $H_1$ | Total complete records |
|---:|---:|---:|---:|
| 0 | 20 | 15 | 35 |
| 1 | 60 | 60 | 120 |
| 2 | 240 | 180 | 420 |
| 3 | 720 | 720 | 1,440 |
| 4 | 2,880 | 2,160 | 5,040 |

A count of *complete possible evolutions* therefore depends upon the selected process comparison boundary and its length, even while the original 35-state compatibility remains fixed. The process counts are not automatically measured transition frequencies, realized residence, or completed whole-closure recurrence.

## 152.6. Process event algebras and observation resolution

For each complete process owner, set

$$
\boxed{\Sigma_J^{(T)}=\mathcal P(\Omega_J^{(T)}),\qquad\mu_J^{(T)}(E)=|E|.}
\tag{152.14}
$$

The stage-evaluation maps are $e_r:\Omega_J^{(T)}\to\Omega_J$, $e_r(x_0,\ldots,x_T)=x_r$. Every event $e_r^{-1}(E)$ is a measurable subset of possible complete comparison records. The full algebra generated by the evaluations of all individual native state labels is the power set of $\Omega_J^{(T)}$, because the evaluations separate distinct complete sequences.

The selected molecule, however, reads only $m\circ e_r$. Define its process-readable algebra

$$
\boxed{\Sigma_M^{(T)}=\sigma\!\left(\{(m\circ e_r)^{-1}(\{0\}),(m\circ e_r)^{-1}(\{1\}):0\le r\le T\}\right).}
\tag{152.15}
$$

Because each admitted exchange flips $q$, this algebra has exactly **two nonempty atoms**, namely the complete records beginning in $H_0$ and those beginning in $H_1$. Their measures are $A_T,B_T$. Thus the observer may read only two kinds of molecular process while each kind contains hundreds or thousands of distinct complete admitted process records. This is a precise boundary-relative statement, not a declaration that unobserved fine possibilities have been destroyed.

The process-stage index is an ordinal position in a native complete comparison. It does not by itself establish seconds, a Markov clock, or a persistent subordinate trajectory.

## 152.7. Recover state identity from process composability

We now reverse the construction. Forget the 35 state labels and retain only:

1. an abstract set $\mathcal A$ of 120 distinguishable one-step process labels;
2. a complete relation $\mathcal C_2\subseteq\mathcal A\times\mathcal A$ specifying which two process incidences are consecutively compatible.

For the adjacency-complete process owner, $\mathcal C_2$ contains precisely the pairs $(a,b)$ for which the original target of $a$ matches the original source of $b$. Its count is $|\mathcal C_2|=420$, but the reconstruction below uses **the complete relation**, not merely that total.

Define the predecessor set of a process label $a$:

$$
\boxed{\operatorname{Pred}(a)=\{b\in\mathcal A:(b,a)\in\mathcal C_2\}.}
\tag{152.16}
$$

Define equivalence of process labels by identical predecessor profiles:

$$
\boxed{a\sim b\iff\operatorname{Pred}(a)=\operatorname{Pred}(b).}
\tag{152.17}
$$

**Theorem 152.3 — Conditional state reconstruction from processes.** Suppose the complete two-process relation is exactly composition at one common finite native intermediate state, and every state has at least one incoming and one outgoing process incidence. Then the quotient of outgoing process labels by (152.17) recovers the native states up to isomorphism. For the present 35-record owner it contains exactly 20 classes of three labels and 15 classes of four labels.

**Proof.** Every process $a$ beginning at a given native state $x$ has as its predecessor set exactly the set of all process labels ending at $x$. Hence all outgoing processes from $x$ have the same predecessor set. For distinct states $x\ne y$, those incoming sets are disjoint, and by assumption nonempty; they cannot be equal. Therefore predecessor equality identifies precisely the outgoing processes having one common source. Quotient classes are in bijection with the states. Their sizes are the states' outgoing degrees: three at each of 20 states of molecular class $0$, and four at each of 15 states of molecular class $1$. Given a process $a$, every allowed successor begins at its destination, so the reconstructed target is likewise the source class of any successor. Thus both source and target incidence can be recovered. $\square$

The reconstruction does not follow from the number 420 alone. It uses *which* process pairs are admitted by the complete enclosing owner. Nor does it imply that an experimentally observed molecule is a persistent primitive bearer of all these comparisons: it reconstructs native state **classes** from process compatibility.

## 152.8. A counterowner with the same states and one-step incidences

Define another enclosing process owner $J'_{[0,2]}$ using the **same** 35 native states and the **same** 120 one-step process labels. Unlike the adjacency-complete owner, however, it excludes an immediate reversal:

$$
\boxed{\mathcal C_2^{\mathrm{NB}}=\{(a,b)\in\mathcal C_2:b\ne a^{-1}\}.}
\tag{152.18}
$$

Here $a^{-1}$ denotes the unique reversed incidence along the same undirected exchange edge. Every one of the 120 possible first incidences has exactly one immediately reversed continuation. Thus

$$
\boxed{|\mathcal C_2^{\mathrm{NB}}|=420-120=300.}
\tag{152.19}
$$

More specifically, the molecular source counts change from $(240,180)$ to $(180,120)$.

**Theorem 152.4 — State and one-step compatibility do not fix complete processes.** The adjacency-complete owner and the no-backtracking owner have identical native state domain, identical one-step incidence domain, and identical one-step source-class possible counts, but distinct complete two-step process domains of sizes 420 and 300.

**Proof.** Both owners share $\Omega_J$ and $\mathcal A_J$ by construction. The first admits all 420 matching incidence pairs; the second omits the 120 immediate reversals. $\square$

There is a sharper process-first consequence. Under the no-backtracking relation, outgoing processes $a$ and $b$ from the **same** state generally have different predecessor sets, because $\operatorname{Pred}_{\mathrm{NB}}(a)$ excludes the inverse of $a$, whereas $\operatorname{Pred}_{\mathrm{NB}}(b)$ excludes the inverse of $b$. All states here have degree at least three, so these predecessor sets are nonempty and distinct. For processes from different sources, the predecessor sets are disjoint. Therefore the predecessor-profile equivalence (152.17), applied directly to $\mathcal C_2^{\mathrm{NB}}$, has **120 singleton classes**, rather than the original 35 source-state classes. This does not show that no alternative inference can reconstruct the original graph; it shows that this exact process-first reconstruction requires the specified full-composition condition or a richer contextual identification.

The two-step records of either owner return to the original **molecular class** $q$, because the molecule flips at each exchange. Only the 120 immediate reversals in the adjacency-complete owner return to the identical full native state. Molecular return, complete-state return, and realized whole-closure recurrence remain distinct.

This concrete counterexample complements Addenda 122 and 139: the compatibility of a complete comparison belongs to its enclosing owner, not to a freely formed join of pairwise or marginal information.

## 152.9. Counting measure is not yet a single probability process

Every finite $\Omega_J^{(T)}$ has an additive counting measure. It is possible to normalize it at each fixed length:

$$
\boxed{\mathbb U_T(E)=\frac{|E|}{|\Omega_J^{(T)}|}.}
\tag{152.20}
$$

But independently normalizing these measures does **not** necessarily give a projectively consistent family of process probabilities. For the present owner, the marginal share of complete processes beginning in molecular class $0$ is

$$
\boxed{\begin{aligned}
\mathbb U_0(q_0=0)&=20/35=4/7,\\
\mathbb U_1(q_0=0)&=60/120=1/2,\\
\mathbb U_2(q_0=0)&=240/420=4/7.
\end{aligned}}
\tag{152.21}
$$

These disagree for the same starting-event question. Hence the separately uniform normalized counting measures cannot all be marginals of one probability law on indefinitely extendible process records.

**Proposition 152.5 — Uniform path measures require uniform extension multiplicity.** Let every admitted length-$T$ process record have at least one compatible extension to length $T+1$. The normalized uniform measures on the two finite process domains agree under the prefix-forgetting map if and only if every length-$T$ record has the same number of admitted $(T+1)$-step extensions.

**Proof.** The probability assigned by the longer uniform measure to a fixed prefix equals the number of its compatible extensions divided by the total longer-domain count. Equality with the uniform shorter-domain weight for every prefix is equivalent to constant extension count. $\square$

This does not prohibit a physically appropriate probability process. A separate consistent weighting can be selected as a **downstream stochastic representation**. For example, the present undirected graph permits stationary initial weights proportional to vertex degree and a conditional uniform choice among each state's admitted outgoing edges. Such a Markov representation is mathematically consistent, but its probabilities, realized occurrences, and rates are *not* fixed by the bare possible-state or possible-process counts alone.

The main point is precise: **a family of possible complete evolutions and its finite counting measures do not, merely by normalization, become one realized stochastic dynamics.**

## 152.10. General $N$-site, $K$-excitation family

The preceding results extend exactly to Addendum 150's finite family

$$
\Omega_{N,K}=\{(q,b_1,\ldots,b_N):q+\textstyle\sum_i b_i=K\},\qquad1\le K\le N.
\tag{152.22}
$$

The state-class counts and outgoing process degrees are

$$
\boxed{\begin{aligned}
n_0&=\binom NK,&d_0&=K,\\
n_1&=\binom N{K-1},&d_1&=N-K+1,\\
n_0d_0&=n_1d_1.
\end{aligned}}
\tag{152.23}
$$

For the declared adjacency-complete process owners, the complete-process counts are

$$
\boxed{\begin{aligned}
A_T^{N,K}&=\binom NK K^{\lceil T/2\rceil}(N-K+1)^{\lfloor T/2\rfloor},\\
B_T^{N,K}&=\binom N{K-1}(N-K+1)^{\lceil T/2\rceil}K^{\lfloor T/2\rfloor}.
\end{aligned}}
\tag{152.24}
$$

Therefore $B_T^{N,K}/A_T^{N,K}=1$ for odd $T$ and $K/(N-K+1)$ for even $T$. The same process-first predecessor-profile argument reconstructs the native state classes, provided the full-composition relation is admitted and each state has nonempty incoming and outgoing incidences. The formula gives a family of explicit finite witnesses, rather than only an isolated numerical example.

## 152.11. Logical relationship among states, processes, and measurable events

The construction separates five distinct objects:

1. **Native state domain:** $\Omega_J$ of compatible joint peer realizations, with boundary-relative state identification.
2. **State event algebra and count:** $\Sigma_J$ and $\mu_J$, with smaller observable algebras induced by selected read maps.
3. **One-step process incidence:** $\mathcal A_J$ and its source/target relation, a new count domain.
4. **Complete process owner:** $\Omega_J^{(T)}$, its event algebra and counting measure, subject to the enclosingly declared compatibility of the whole comparison.
5. **Realized statistical or dynamical reading:** $\nu$, occupancy $c$, completed recurrence $N_{\mathcal C}$, or an optional probability and time calibration. None is equated with the possible counts merely because a normalized number can be formed.

This answers the state–process reconstruction question in both directions **for specified finite owners**:

$$
\boxed{\begin{gathered}
\text{Native states + complete composability}
\longrightarrow\text{admitted complete processes},\\[3pt]
\text{Process incidences + complete composability}
\longrightarrow\text{reconstructed native state classes}.
\end{gathered}}
\tag{152.25}
$$

The reconstruction does not say that the original states must be primitive independent objects, nor does it establish a general equivalence between arbitrary states and arbitrary processes. A different process owner can preserve all one-step data while changing the longer-comparison relation and the reconstructed predecessor profiles.

## 152.12. Scope and next reconstruction

**Established for the specified finite owners:**

- The power-set $\sigma$-algebras and their boundary-readable pullbacks are explicit and $\sigma$-additive counting measures exist.
- The 35 state records and 120 process incidences have different source-class count ratios: $20:15$ versus $60:60$.
- The adjacency-complete multi-step process counts and odd/even ratio theorem are exact.
- Complete process composability recovers 35 native state classes from unlabeled incidence identities by the predecessor-profile quotient.
- The no-backtracking counterowner retains every state and one-step incidence but admits 300 rather than 420 two-step records; the same process-first quotient no longer reconstructs the original states.
- Naively uniform normalized counting measures on different comparison lengths need not be projectively consistent.

**Not established by this finite result:** a general theory of physical temporal evolution; a canonical stochastic measure across arbitrary process boundaries; a continuum $\sigma$-algebra or topology derived from experimental operations; Liouville measure; a symplectic form or Hamilton's equations; or the non-Boolean/nonadditive structure of general quantum measurement. These are downstream mathematical reconstructions with their own compatibility and limiting conditions. The finite result supplies a precise baseline against which to test them.

The most direct next target is a family of finite **reversible count-preserving process owners** with consistent physical calibration. We can ask when their calibrated refining-limit event measures reproduce classical Liouville measure, and which additional pairwise compatibility is required for a symplectic rather than merely volume-preserving limiting structure.

## Conclusion

The R²D primitive is not an unspecified universal bag of states. A selected boundary defines a concrete compatible native domain and readable classification. A complete process comparison is a different, enclosing-owned count domain, and its measure need not agree with the native state measure. In the same molecule–reservoir compatibility, there are exactly 35 native states, 120 possible directed one-step processes, and 420 possible two-step records under a fully composable owner. A different owner with the same states and one-step processes admits only 300 two-step records.

When complete incidence composability is supplied, state identities can be reconstructed from the compatibility of processes themselves: the 120 processes fall into 35 predecessor-profile classes. When that composability is changed, the reconstruction changes. The essential point is therefore not that states always precede processes or that processes always precede states. **Both can be finite mathematical reads of one enclosing compatibility, and the equivalence between the reads depends on the complete relation that the enclosing boundary actually admits.**

---

## Related Canon and Addenda

- **R²D Part I:** Boundary-native formal microstates, readable macrostates, native multiplicity, $\Theta$, $P$, state occurrence, occupancy, complete closure recurrence, and recursive carry.
- **R²D Addendum 120:** Native identification and replacement; no duplicate counting of presentations.
- **R²D Addendum 122:** Complete enclosing compatibility before categorical or relational composition; the spurious-join objection.
- **R²D Addenda 124–125:** Native configuration counts, realized occurrence, and completed-closure correspondence.
- **R²D Addenda 135–140:** Complete spatial–recurrence relations, observational coherence, finite compatibility fingerprints, and read-fiber survival.
- **R²D Addenda 150–151:** The 35-state/60-edge molecular–reservoir owner and its 125-state physical preparation extension.

**Review status:** Author-approved for canon publication. This is an exact finite states–processes event-space reconstruction and an explicit mathematical starting point for comparison with operational reconstruction programs. Its scope is finite possible count, not yet physical Hamiltonian dynamics or quantum measure reconstruction.
