---
r2d_id: "addendum-142"
title: "Addendum 142 — Relative Motion Before Velocity"
subtitle: "Binary Comparison, Enclosing Rank, and the Background-Owned Physical Read"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 142
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-20"
promotion_basis: "explicit_author_authorization_2026-11-20"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
date: "2026-11-16"
scope: "Relational directional distinguishability; many-peer motion rank; complete compatible motion classifications; background-owned velocity calibration; mapping onto conventional motion"
---

# R²D Addendum 142 — Relative Motion Before Velocity

*Binary Comparison, Enclosing Rank, and the Background-Owned Physical Read*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Part I, especially boundary-native distinguishability and multiplicity; Part IV, §§3.2–3.8; Addenda 131, 139–141.

## Abstract

Velocity is conventionally measured as motion relative to a reference. R²D specifies the prior organizing relation: the enclosing boundary determines which relative motions are distinguishable, the compatibility of their complete realizations, and the background-defined physical reference and scale. A two-peer boundary distinguishes reciprocal directional alternatives. A many-peer boundary classifies the ordering of those alternatives. Complete enclosing spatial–recurrence compatibility supplies their dimensionless magnitude relations, and the background supplies the physical ruler and clock that make those relations readable as velocity. Neither the reference nor the magnitude originates within the moving molecule.

This addendum establishes reciprocal binary comparison, a finite rank-multiplicity theorem, the count-quantile mapping from relative rank to dimensionless motion, and the physical velocity projection. Maxwell–Boltzmann is identified as a conventional physics correspondence, not treated as a separate derivation. The central result is that **velocity belongs to an enclosing-defined relationship, not to an object independently of that relationship.**

## 142.1. Velocity begins with a relation

At every R²D boundary, a formal microstate is one compatible joint peer realization; readable macrostates and their native multiplicity are defined by the boundary. Let

$$
W_J(i)=|\pi_J^{-1}(i)|,\qquad S_J(i)=\ln W_J(i).
\tag{142.1}
$$

This entropic landscape is scale-free. Addendum 141 establishes that the enclosing background owns the spatial scale $L_\Phi$, the reference interval $\tau_\Phi$, and the complete spatial–recurrence relations. Neither the spatial nor the temporal scale originates in the turbine or the molecule.

A molecule is not assigned an independent primitive velocity before its comparison boundary is defined. Its measured velocity is a downstream physical read of that enclosing organization.

## 142.2. Two peers: reciprocal binary distinguishability

Consider one enclosing comparison containing molecule $a$ and observer $b$, over a common background-defined comparison interval. Let $\ell_a$ and $\ell_b$ be their dimensionless spatial reads in that joint comparison. Define

$$
d_{ab}=\ell_a-\ell_b,
\qquad
s_{ab}=\operatorname{sgn}(d_{ab})\in\{-1,+1\}
\tag{142.2}
$$

for a nonzero resolved distinction. Then

$$
\boxed{s_{ba}=-s_{ab}.}
\tag{142.3}
$$

**Theorem 142.1 — Reciprocal peer comparison.** Reversing the order of a nonzero two-peer comparison reverses its directional classification.

**Proof.** $d_{ba}=\ell_b-\ell_a=-d_{ab}$; taking signs proves the result. $\square$

The two opposite signs describe reciprocal **relative readings**. They do not assert that the two objects have opposite velocities in every external reference frame. An unresolved equality belongs to a separate tie class.

Two-peer distinguishability supplies the relative direction, but no intrinsic magnitude, ensemble center, or scale. Conventional two-body relative velocity can be measured when a ruler and clock are supplied by a larger physical reference; the selected pair does not itself establish their origin.

## 142.3. Many peers: relative rank

Let $N$ distinguishable peers be jointly compared along one direction over a common reference interval, and assume the complete admitted comparisons yield one consistent strict ordering. Define

$$
k_a=\sum_{b\ne a}\mathbf1(d_{ab}>0),
\qquad
\boxed{r_a=\frac{k_a}{N-1}.}
\tag{142.4}
$$

The integer $k_a$ counts the peers below $a$ in that directional ordering. An extreme positive rank denotes the highest relative component; a median rank supplies an ordinal reference. These are enclosing classifications, not properties originating within the isolated molecule.

### Theorem 142.2 — Equal complete-ordering multiplicity

Suppose the enclosing owner admits all $N!$ strict labeled orderings as distinct complete ordering realizations. For any selected labeled peer $a$, the number of complete orderings that place it at a given rank $k$ is

$$
\boxed{\Theta_J(k)=(N-1)!,\qquad k=0,\ldots,N-1.}
\tag{142.5}
$$

**Proof.** Fix $a$ in the $(k+1)$-st ordered position. The remaining $N-1$ labels have $(N-1)!$ permutations, independent of $k$. $\square$

Consequently the normalized possible-count rank distribution in this explicit full-ordering domain is $1/N$ at each rank. **Ranking alone does not produce Maxwell–Boltzmann.** It establishes order but not the physical intervals between ranks. Those distinctions are supplied by complete enclosing spatial–recurrence compatibility.

## 142.4. Complete compatibility supplies the motion-class distribution

Let $\mathcal H_J$ contain the enclosing owner's complete compatible records. Following Addendum 141, a tagged peer $a$ in a complete record $h$ has a dimensionless joint spatial–recurrence read

$$
u_{J,a}(h)=\frac{\ell_{J,a}(h)}{n_J(h)},\qquad n_J(h)>0.\tag{142.6}$$

For a multi-peer system, possible motion classes must count **tagged peer incidences**, not merely complete configurations. Define

$$
\mathcal I_J=\{(h,a):h\in\mathcal H_J,\ a\text{ is a readable peer in }h\},
$$

$$
\Theta_J^{\mathrm{mot}}(u)
=|\{(h,a)\in\mathcal I_J:u_{J,a}(h)=u\}|.
\tag{142.7}
$$

Let the normalized cumulative enclosing possible count be

$$
F_J(u)=
\frac{\sum_{w\le u}\Theta_J^{\mathrm{mot}}(w)}
{\sum_w\Theta_J^{\mathrm{mot}}(w)}.
\tag{142.8}
$$

Then the count-quantile relation is

$$
\boxed{g_\Phi(r)=\inf\{u:F_J(u)\ge r\},\qquad 0<r<1.}
\tag{142.9}
$$

**Theorem 142.3 — Count-quantile motion mapping.** Given the complete enclosing-compatible motion-class counts, Equation (142.9) uniquely supplies the nondecreasing percentile-to-dimensionless-motion mapping with the standard generalized-inverse convention.

**Proof.** $F_J$ is nondecreasing and identifies the cumulative share of admitted motion-class incidences. Its generalized inverse identifies the first motion class at which that share reaches $r$. $\square$

The rank $r_a$ obtained in a single finite realized ensemble is not automatically identical to a percentile of possible counts across all complete records. Their correspondence requires the R²D realization relationship in the selected many-peer comparison domain. Possible multiplicity, realized occurrence, and occupancy remain distinct.

The essential result is already available: the two-peer signs define the ordering, while complete enclosing-compatible motion counts define the magnitude relation among ordered classes.

## 142.5. The enclosing background supplies physical velocity

Let the enclosing background supply $L_\Phi$, $\tau_\Phi$, and a physical reference velocity $u_\Phi^{\mathrm{ref}}$. Define

$$U_\Phi=\frac{L_\Phi}{\tau_\Phi}.\tag{142.10}$$

Then the physical motion component read corresponding to compatible percentile rank $r$ is

$$
\boxed{v_{a|\Phi}(r)
=u_\Phi^{\mathrm{ref}}+\frac{L_\Phi}{\tau_\Phi}g_\Phi(r).}
\tag{142.11}
$$

This equation separates the ordinarily conflated contributions:

1. Relative rank is defined by the enclosing peer comparisons.
2. The dimensionless magnitude class is defined by complete enclosing spatial–recurrence compatibility.
3. The reference, ruler, and clock are supplied by the enclosing background.

### Theorem 142.4 — Velocity is not an intrinsic molecular property

In the R²D construction, the full physical velocity read (142.11) cannot be defined from the isolated peer alone.

**Proof.** Its rank depends on the enclosing comparison set. Its dimensionless magnitude depends on the enclosing motion-class distribution. Its reference and physical scale depend on the background. None of these is defined by the isolated peer. Their composition is therefore an enclosing-defined relation, not an isolated-peer native property. $\square$

This does not discard conventional trajectories or mechanical observations. It identifies the enclosing origin of the physical coordinates in which those observations are expressed.

## 142.6. Conventional thermal-velocity correspondence

A symmetric complete enclosing distribution pairs $u$ with $-u$. Under reciprocal realization,

$$
\langle v-u_\Phi^{\mathrm{ref}}\rangle=0,
\qquad
\langle(v-u_\Phi^{\mathrm{ref}})^2\rangle>0
\tag{142.12}
$$

whenever nonzero reciprocal motion classes occur. Thus positive motion fluctuations coexist with zero net direction, as developed for symmetric turbine recurrence in Addendum 131.

In the conventional ideal-gas Maxwell–Boltzmann regime, a Cartesian velocity component is Gaussian about the background mean. Its observed quantile read is accordingly

$$
\frac{v-u_\Phi^{\mathrm{ref}}}{U_\Phi}
=\frac{\sigma_\Phi}{U_\Phi}\Phi_{\mathrm G}^{-1}(r),
\tag{142.13}
$$

where $\Phi_{\mathrm G}$ is the standard Gaussian cumulative distribution and $\sigma_\Phi$ is the measured component width. Equation (142.13) is a conventional-physics correspondence, not a claim that pairwise ordering alone derives the Gaussian law.

R²D assigns the distribution's compatible state organization and the reference for its physical measurement to the enclosure. The background defines the velocity scale. Molecules realize the admitted comparisons. A separate reconstruction of every kinetic model or velocity distribution is not needed to establish this foundational mapping.

## 142.7. Recursive replacement and conclusion

When the enclosing background changes, the relevant reference, ruler, clock, and native motion classification may change. Addenda 139–141 determine when a relational comparison survives the receiving read and when it is replaced. A molecule does not carry an unchanged intrinsic velocity between recursive count boundaries.

The logical sequence is

$$
\boxed{
\begin{gathered}
\text{Binary enclosing relative distinguishability}\\
\Downarrow\\
\text{Many-peer motion rank}\\
\Downarrow\\
\text{Complete enclosing spatial–recurrence compatibility}\\
\Downarrow\\
\text{Background-owned reference, ruler, and clock}\\
\Downarrow\\
\text{Measured velocity}.
\end{gathered}}
\tag{142.14}
$$

**Velocity is an enclosing-defined relationship, not a property originating in the object that moves.** This is the R²D mapping onto the conventional physical concept of velocity. The framework does not require every application of dynamics to be re-derived in order to establish which boundary owns that concept.

## Related Canon and Addenda

- R²D Part I — *A Theory of Dimensionless Recursive Counting*, especially §3.2.
- R²D Part IV — *Projection: The Physics Constructed from What Remains*, especially §§3.2–3.8.
- Addendum 131 — *Symmetric Background Before Turbine Recurrence*.
- Addenda 139–140 — Cross-native observational coherence and persistence.
- Addendum 141 — *Background Scales Before Motion*.
