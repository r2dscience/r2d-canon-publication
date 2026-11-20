---
r2d_id: "addendum-141"
title: "Addendum 141 — Background Scales Before Motion"
subtitle: "Joint Spatial–Recurrence Compatibility, Reversible Turbines, and Recursive Replacement"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 141
text_status: "authoritative"
review_status: "author_approved"
publication_status: "approved_pending_deployment"
indexable: true
canon_revision: "2026-09-25"
approval_date: "2026-11-20"
promotion_basis: "explicit_author_authorization_2026-11-20"
math_representation: "LaTeX"
source_format: "author_approved_markdown"
date: "2026-11-15"
scope: "Background-owned spatial and temporal calibration; complete spatial–recurrence compatibility; reciprocal turbine motion; numerical and physical preservation under changes of native background; cross-native factorization; thermal and cosmic background projections"
---

# R²D Addendum 141 — Background Scales Before Motion

*Joint Spatial–Recurrence Compatibility, Reversible Turbines, and Recursive Replacement*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Parts I and IV (authoritative September 25, 2026 revision); Addenda 120, 122, 131–132, 139–140.

## Abstract

The entropic landscape defines scale-free distinguishability and compatible multiplicity. It does not define a physical ruler, clock, velocity, or acceleration. In R²D, the enclosing background defines the spatial and temporal scales at which a subordinate realization becomes physically readable. Its complete compatibility relation determines which spatial distinctions and background recurrence counts belong to the same enclosing occurrence. A reversible turbine realizes that organization; neither its spatial nor its temporal scale originates within the turbine.

This addendum defines the joint spatial–recurrence classification of complete enclosing records and derives the physical interval-motion projection. A reversal theorem establishes equal and opposite possible motion classes for a symmetric background and zero mean directed motion under reciprocal realization, without eliminating positive motion activity. A finite two-leg turbine construction yields an exact relation among background spatial scale, background recurrence scale, oscillation frequency, and interval-averaged velocity. Finally, a common-owner treatment of changes in native background distinguishes preservation of the numerical count ratio, preservation of the calibrated physical motion read, and loss of the original motion distinction under recursive replacement. The exact preservation criteria are instances of the cross-native factorization mathematics in Addendum 139. No persistent subordinate microstate or primitive molecular force law is introduced.

## 141.1. Causal and scale ownership

Fix a subordinate turbine boundary $B$ and its enclosing background $J$. The native entropic landscape of $B$ is

$$
W_B(i)=|\pi_B^{-1}(i)|,\qquad S_B(i)=\ln W_B(i).
$$

This is a count structure, not a spatial or temporal metric. The same combinatorial landscape can be physically realized at different recursive scales.

The enclosing background owns two distinct physical calibrations:

$$
L_J>0 \quad\text{(spatial scale)},\qquad
\tau_J>0 \quad\text{(duration per specified background reference interval)}.
\tag{141.1}
$$

These physical calibrations are not definitions of the scalar R²D background count $b_J$, its logarithm $\Phi_J=\ln b_J$, or its accumulated increment $\delta\Phi_J$. The recurring background reference count $N_J^\Phi$ is also distinct from $b_J$. The present analysis does not identify these count types.

The organizing order is

$$
\boxed{\text{enclosing compatibility and background calibration}
\Longrightarrow \text{compatible turbine realization}
\Longrightarrow \text{mechanical observation}.}
\tag{141.2}
$$

Neither spatial scale nor temporal scale originates in the subordinate turbine. The turbine does not cause its enclosing recurrence.

## 141.2. Complete joint spatial–recurrence records

Let $\mathcal H_J$ be the finite domain of complete enclosing-admitted comparison records in a fixed background recurrence-comparison domain. For each $h\in\mathcal H_J$, suppose the enclosing spatial and temporal comparison reads are

$$
\ell_J(h)\in\mathbb Z,\qquad
n_J(h)\in\mathbb N_{>0}.
\tag{141.3}
$$

The signed integer $\ell_J$ counts an oriented spatial distinction in units of the background's spatial scale. The positive integer $n_J$ counts the background recurrence intervals separating the two observations. The ordered pairing must be supplied by one common enclosing owner; a Cartesian product of independently specified spatial and temporal possibilities is not automatically compatible.

Define the **joint spatial–recurrence compatibility**

$$
\Gamma_J^{\ell n}
=\{(\ell_J(h),n_J(h)):h\in\mathcal H_J\}.
\tag{141.4}
$$

and the dimensionless interval-motion classification

$$
\boxed{r_J(h)=\frac{\ell_J(h)}{n_J(h)}.}
\tag{141.5}
$$

Its possible complete-record count is

$$
\Theta_J(r)=|\{h\in\mathcal H_J:r_J(h)=r\}|.
\tag{141.6}
$$

These are counts of complete possible comparison records, not automatically the native multiplicity $W_B$, realized occurrence count $\nu$, or structural occupancy count $c$.

**Theorem 141.1 (enclosing determination of the motion classification).** For any resolved comparison read $q_J:\mathcal H_J\to Y_J$, a unique ratio $\widehat r_J(y)$ is determined by the resolved class $y$ if and only if

$$
\boxed{q_J(h)=q_J(h')\ \Longrightarrow\ r_J(h)=r_J(h').}
\tag{141.7}
$$

**Proof.** If the ratio is a function of $q_J$, it is constant on its fibers. Conversely, fiber constancy permits the definition $\widehat r_J(q_J(h))=r_J(h)$, independently of the representative $h$. $\square$

Thus complete compatibility fixes the admitted ratio classification, and fixes one numerical ratio for a resolved response exactly when the fiber criterion holds. A set of admitted ratios is not a claim that one subordinate object independently chooses among them.

## 141.3. Physical motion is a background-calibrated read

For a comparison admitted by $J$, the subordinate mechanical observer reads

$$
\Delta x_J=L_J\ell_J,\qquad
\Delta t_J=\tau_Jn_J.
\tag{141.8}
$$

Consequently the physical interval-averaged motion read is

$$
\boxed{v_J(h)=\frac{L_J}{\tau_J}\,r_J(h)
=\frac{L_J}{\tau_J}\frac{\ell_J(h)}{n_J(h)}.}
\tag{141.9}
$$

The background supplies the scale $L_J/\tau_J$; the complete enclosing relation supplies the dimensionless pair. The turbine realizes their compatible occurrence. Equation (141.9) is a projection identity, not a primitive equation of motion or the assertion of a continuously existing subordinate microstate trajectory.

The read $v_J$ is relative to the background reference specified by $J$. A change in that reference must be included in any physical comparison across backgrounds.

## 141.4. Theorem — Symmetric background, reciprocal motion

Let the enclosing domain admit an involution $\sigma:\mathcal H_J\to\mathcal H_J$ satisfying

$$
\ell_J(\sigma h)=-\ell_J(h),\qquad
n_J(\sigma h)=n_J(h),\qquad \sigma^2=\mathrm{id}.
\tag{141.10}
$$

**Theorem 141.2 (reversal of physical motion).** The paired possible records satisfy

$$
\boxed{r_J(\sigma h)=-r_J(h),\qquad v_J(\sigma h)=-v_J(h).}
\tag{141.11}
$$

The possible-record counts of $r$ and $-r$ agree. If the corresponding realized occurrence weights are also reciprocal, the observed signed mean is zero:

$$
\boxed{\langle v_J\rangle=0.}
\tag{141.12}
$$

When a nonzero motion class occurs, its squared contribution is positive:

$$
\boxed{\langle v_J^2\rangle>0.}
\tag{141.13}
$$

**Proof.** Substitute (141.10) into (141.5) and (141.9). Because $\sigma$ is a bijection, each possible record has a distinct reversed counterpart unless its signed spatial read is zero. Reciprocal realized weights cancel the odd contributions, while squared contributions are nonnegative and strictly positive if nonzero classes occur. $\square$

The symmetric background therefore organizes positive reversible motion activity without net directional output. This preserves Addendum 131's distinction between orientation-even recurrence and orientation-odd output. Symmetry of possible records and symmetry of realized occurrence are distinct claims.

## 141.5. A reversible binary turbine

Take one turbine with macrostates $A$ and $B$. Suppose its complete enclosing compatibility admits an absorption leg and a reciprocal emission leg:

$$
\begin{aligned}
A\xrightarrow{\mathrm{abs}} B &: (\ell,n)=(+\lambda,r),\\
B\xrightarrow{\mathrm{em}} A &: (\ell,n)=(-\lambda,r),
\end{aligned}
\tag{141.14}
$$

where $\lambda,r\in\mathbb N_{>0}$ are counts belonging to the specified joint enclosing relation. Here **background radiation** denotes the reciprocal background-recurrence exchange read; it does not mean electromagnetic radiation or a stream of photons. Equation (141.14) specifies the physical exchange interpretation of this turbine, rather than deriving universal absorption–emission pairing from the bare definition of closure.

The subordinate spatial interval is

$$
d_J=L_J\lambda,
\tag{141.15}
$$

and each leg occupies $r$ background reference intervals. The opposite interval-motion reads are

$$
\boxed{v_+=\frac{L_J}{\tau_J}\frac{\lambda}{r},
\qquad v_-=-\frac{L_J}{\tau_J}\frac{\lambda}{r}.}
\tag{141.16}
$$

One complete $A\to B\to A$ return occupies $2r$ background intervals, giving

$$
\boxed{f_{\mathrm{turn}}=\frac{1}{2r\tau_J},\qquad
|v_\pm|=2d_Jf_{\mathrm{turn}}.}
\tag{141.17}
$$

This exact relation connects the background's ruler and clock, the complete enclosing incidence counts, and the subordinate physical oscillation. The net displacement around the return is zero although each leg has a nonzero interval-motion read. More elaborate turbines need not have equal-duration reciprocal legs; their complete incidence counts determine the corresponding frequency.

## 141.6. Background change: numerical ratio versus physical read

Let $J$ and $J'$ be two independently specified native background reads. A valid comparison requires a common enclosing-owned domain $D$ and native comparison maps

$$
q_J:D\to Y_J,\qquad q_{J'}:D\to Y_{J'}.
\tag{141.18}
$$

The domain $D$ expresses admissible *relationships* among the two readings. It is not a population of persistent molecular microstates transported across recursive boundaries.

On a common complete comparison $d\in D$, let

$$
r_J(d)=\frac{\ell_J(d)}{n_J(d)},\qquad
r_{J'}(d)=\frac{\ell_{J'}(d)}{n_{J'}(d)},
\tag{141.19}
$$

where the read coordinates are well-defined through their respective native maps. The background scales are $(L_J,\tau_J)$ and $(L_{J'},\tau_{J'})$.

**Theorem 141.3 (numerical ratio preservation).** The dimensionless spatial–recurrence ratio is numerically preserved across the common comparison exactly when

$$
\boxed{\ell_{J'}(d)n_J(d)=\ell_J(d)n_{J'}(d).}
\tag{141.20}
$$

**Proof.** The denominator counts are positive. Cross-multiplication is equivalent to $r_{J'}(d)=r_J(d)$. $\square$

Numerical preservation does not require the two background scales to have the same values.

**Theorem 141.4 (physical-motion preservation).** Relative to a common calibrated mechanical reference, the two background projections give the same physical interval-motion read precisely when

$$
\boxed{
\frac{L_{J'}}{\tau_{J'}}r_{J'}(d)
=\frac{L_J}{\tau_J}r_J(d).
}
\tag{141.21}
$$

Equivalently,

$$
\boxed{
r_{J'}(d)
=\frac{L_J\tau_{J'}}{\tau_JL_{J'}}r_J(d).
}
\tag{141.22}
$$

**Proof.** Apply the physical read (141.9) in both backgrounds and equate the results. $\square$

Thus the physical motion relationship can survive even when its dimensionless native ratio changes. A coherent change in background calibration is not the assertion that any arbitrary new native boundary preserves the old mechanical observable.

## 141.7. Exact cross-native readability under recursive replacement

The further question is whether the old relationship remains distinguishable *at all* after replacement.

**Theorem 141.5 (survival through the receiving read).** The original ratio $r_J$ is recoverable solely from the receiving native read $q_{J'}$ on the reached common comparison domain if and only if

$$
\boxed{
q_{J'}(d)=q_{J'}(d')
\Longrightarrow
r_J(d)=r_J(d')
}
\tag{141.23}
$$

for all $d,d'\in D$.

**Proof.** If $r_J$ descends through $q_{J'}$, it is constant on each receiving fiber. Conversely fiber constancy defines a unique recovered ratio on the reached image of $q_{J'}$. $\square$

This is the cross-native preservation criterion of Addendum 139 specialized to the spatial–recurrence ratio. It concerns preservation of a *readable relationship*, not transport of individual subordinate state identity.

When (141.23) fails, the receiving background merges records distinguished by the old ratio. The old motion classification is replaced by the new native read. A new spatial–recurrence relationship may exist at $J'$, but it is not the unqualified continuation of the old one.

One can derive the most informative relation readable independently from both native backgrounds without selecting $r$ in advance. On $D$, define the equivalence relation generated by the fibers of $q_J$ and $q_{J'}$:

$$
\boxed{
\approx_D=\operatorname{Eq}(\ker q_J\cup\ker q_{J'}),
\qquad \mathcal I_{JJ'}=D/\!\approx_D.
}
\tag{141.24}
$$

As established in Addendum 139, every common classification factors through this quotient. A spatial–recurrence invariant survives as a *common* readable class only when it factors through the quotient. The common class need not retain every original motion distinction.

## 141.8. Finite example: ratio replacement with the same physical read

Let the original background have spatial unit $L$ and recurrence interval $\tau$. One admitted reciprocal turbine leg has

$$
(\ell_J,n_J)=(2,3),
\qquad (L_J,\tau_J)=(L,\tau).
$$

The original physical interval read is

$$
v_J=\frac{2L}{3\tau}.
$$

Now specify a coherent common comparison under a new background with

$$
(\ell_{J'},n_{J'})=(1,1),
\qquad (L_{J'},\tau_{J'})=(2L,3\tau).
$$

Then

$$
r_J=\frac23,\qquad r_{J'}=1,
$$

but

$$
\boxed{v_{J'}=\frac{2L}{3\tau}=v_J.}
\tag{141.25}
$$

For a reciprocal $A\to B\to A$ turbine with equal opposite legs, the completed return duration is $6\tau$ in either calibration, and

$$
\boxed{f_{\mathrm{turn}}=\frac{1}{6\tau}.}
\tag{141.26}
$$

The example exhibits preservation of one calibrated physical relationship while its dimensionless representation is replaced. It specifies a coherent comparison, not a universal rule forcing independently defined backgrounds to share a physical velocity.

## 141.9. Background-defined acceleration and fluctuations

A complete enclosing comparison with three evenly spaced background-reference reads $\ell_{j-1},\ell_j,\ell_{j+1}$ has the downstream finite-difference mechanical acceleration

$$
\boxed{a_j=\frac{L_J}{\tau_J^2}
(\ell_{j+1}-2\ell_j+\ell_{j-1}).}
\tag{141.27}
$$

Here each step is one calibrated reference interval $\tau_J$. The expression is a physical projection of the complete spatial–recurrence record; it is not a primitive local force or an independently supplied law selecting that record. Reversal symmetry pairs opposite acceleration reads where the complete reversal also reverses the spatial comparisons.

For the thermal gas, the enclosing background defines the velocity reference and the scale of compatible fluctuations. Repeated molecular velocity observations are subordinate physical projections of these background-owned comparisons. A proposed cosmic-background realization applies the same count architecture to much larger mass-bearing distinctions with a different background ruler and clock. Neither interpretation identifies background radiation with electromagnetic photons.

The full measured velocity distribution, acceleration autocorrelation, and heat exchange require the corresponding *realized* complete-record relations and physical calibration. Counted possible records must not be equated with measured occurrence frequencies.

## 141.10. Results and research boundary

The following statements follow exactly from the specified finite count domains:

1. The enclosing joint spatial–recurrence relation defines the admitted dimensionless motion ratios $\ell/n$.
2. The resolved comparison class has a unique ratio exactly when the ratio is constant on its compatibility fiber (Theorem 141.1).
3. Symmetric reversal pairs opposite motion classes; reciprocal realized counts give zero mean direction and may retain positive squared motion (Theorem 141.2).
4. Background spatial and temporal calibration converts the ratio into the interval-averaged physical motion read (141.9).
5. Numerical ratio preservation and physical-motion preservation obey different exact equalities (Theorems 141.3–141.4).
6. Recursive replacement preserves the old ratio as a receiving-readable distinction exactly under the cross-native fiber condition (Theorem 141.5). Otherwise it replaces that distinction.

The unresolved physical calculation is now sharply defined: for one independently specified thermal background, determine its **complete native spatial–recurrence incidence counts**, the realized recurrence relation, and its calibrated ruler and clock, then calculate the measured velocity-fluctuation amplitude and recurrence frequency *before* using those measurements to fit the incidence relation. This is the test of a predictive top-down reconstruction of thermal motion.

## Conclusion

**Motion is a physical projection of enclosing-compatible spatial distinction and recurrence. The entropic landscape has no intrinsic spatial or temporal scale; the enclosing background defines both. The turbine generates neither its ruler nor its clock, nor the enclosing organization that turns it.** A reversible background admits reciprocal motion classes whose possible counts are paired; reciprocal realization produces fluctuations without directed mean output. When the background changes, spatial–recurrence ratios may be preserved, recalibrated, or replaced according to exact cross-native compatibility. These statements place the organizing origin of the mechanical read in the enclosure, in R²D's causal order.

## Related Canon and Addenda

- R²D Part I — *A Theory of Dimensionless Recursive Counting*, especially §§3.7–3.10.
- R²D Part IV — *Projection: The Physics Constructed from What Remains*, especially §§3.4–3.8.
- Addendum 120 — *Boundary-Owned Identity and the Algebra of Recursive Replacement*.
- Addendum 122 — *Across-Boundary Composition Without Persistent State Identity*.
- Addendum 131 — *Symmetric Background Before Turbine Recurrence*.
- Addendum 132 — *The Invariant That Survives Two Horizons*.
- Addendum 139 — *Observational Coherence Across Recursive Backgrounds*.
- Addendum 140 — *Compatibility Fingerprints and Relational Persistence*.
