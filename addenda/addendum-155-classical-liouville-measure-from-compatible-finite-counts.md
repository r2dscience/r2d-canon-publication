---
r2d_id: "addendum-155"
title: "Addendum 155 — Classical Liouville Measure from Compatible Finite Counts"
subtitle: "Uniform Refinement, Borel Extension, Symplectic Volume, and Hamiltonian Invariance"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 155
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
scope: "Exact compatible finite count measures on unimodular intersection modules; distinction between modular inverse limits and real dyadic-cell completion; unique Borel extension of uniform refinement counts; equality with classical Liouville measure on a selected flat symplectic continuum; symplectic and Hamiltonian measure invariance; noncompact and calibrated extensions; counterexamples to count-only and volume-only selection"
---

# R²D Addendum 155 — Classical Liouville Measure from Compatible Finite Counts

*Uniform Refinement, Borel Extension, Symplectic Volume, and Hamiltonian Invariance*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Parts I–IV (September 25, 2026); especially Addenda 105, 116, 120, 122, 125, 131, 139, and 150–154.  
**Result type:** Exact finite and measure-theoretic reconstruction **conditional on a specified real affine completion**, plus classical symplectic/Hamiltonian consistency. Neither a real continuum nor a physical Hamiltonian is derived from finite cardinality alone.

## Abstract

Addendum 152 defined finite event algebras and counting measures for native states and complete processes, showing that independently uniform counts on successive process lengths need not form a consistent probability family. Addenda 153–154 supplied a different ingredient: explicit complete oriented closures with a nondegenerate **unimodular integral intersection pairing** on the surviving recurrence-class lattice. The open classical-measure question is whether one can connect these structures to the Liouville measure of classical mechanics without taking phase-space volume or physical position–momentum coordinates as primitive.

We construct that connection in a precise finite-to-continuum model. Let $L\cong\mathbb Z^{2g}$ be the first-homology lattice of a selected complete oriented closure, with integral intersection form $I$ and canonical block matrix $\mathbb J_g$. At each resolution $N\ge2$, the finite count owner $L/NL$ has $N^{2g}$ labels, its power-set event algebra, and normalized uniform possible-count measure. These finite measures are exactly consistent under modular reduction. **Their algebraic inverse limit is profinite, not a real phase space**, so this fact alone does not yield Liouville measure.

We next specify, independently and explicitly, the real affine completion $L_{\mathbb R}=L\otimes_{\mathbb Z}\mathbb R$ and its compact quotient $T=L_{\mathbb R}/L$. A nested family of dyadic fundamental-domain cells supplies a different finite comparison map: each coarse cell has precisely $2^{2g}$ finer compatible cells. Uniform cell-count measures form a consistent premeasure whose unique regular Borel extension is normalized Lebesgue (equivalently Haar) measure on $T$. The integral intersection form extends to a constant symplectic form $\omega=\sum_i dx_i\wedge dy_i$, and its unimodularity gives total symplectic volume one on the fundamental domain. Consequently the count-derived Borel measure agrees **exactly** with the positive Liouville measure associated with $\omega^g/g!$.

Integral symplectic recurrence transformations preserve every finite modular count measure and the continuum Liouville measure. An admitted smooth Hamiltonian flow preserves $\omega$ and hence the same measure, giving Liouville's theorem. A four-dimensional volume-preserving but nonsymplectic transformation proves that measure preservation alone cannot reconstruct the intersection pairing. The theorem is an exact **existence and conditional identification result** for a flat classical phase-space representation. It does not establish an intrinsic real-number system from counting, uniform realization frequencies, a unique Hamiltonian, an arbitrary physical phase-space manifold, or quantum nonadditive measurement structure.

---

## 155.1. Reconstruction question and canonical count distinctions

The primitive R²D ordering assigns distinguishable native states and compatible subordinate realizations relative to an enclosing owner before their physical interpretation. Part I distinguishes native multiplicity $W$, enclosing compatible extension $\Theta$, possible count, realized state occurrence $\nu$, structural occupancy, and completed whole-closure recurrence. Addenda 125, 131, and 152 explicitly prohibit substituting one of these counts for another merely because their numerical values can be normalized.

In Addendum 152, a finite molecule–reservoir owner admitted $35$ native possible states, $120$ oriented one-step processes, and $420$ adjacency-composable two-step records. Uniformly normalizing each complete-process domain by its own cardinality did **not** produce compatible probabilities across process lengths: the number of extensions depended on the source record. A count measure exists on each finite event algebra, but consistency across owners must be established, not presumed.

Addenda 153–154 answered a different mathematical question. An explicitly selected complete oriented two-dimensional closure—requiring attachment information beyond first-order incidence—can have a surviving first-homology lattice with integral nondegenerate alternating intersection pairing. Addendum 153 supplied the rank-four, genus-two witness; Addendum 154 supplied a rank-two, genus-one witness, conditional on operational corner-and-channel-side compatibility. The intersection relation is **not** a time-ordered trajectory, a microscopic collision number, or a physical momentum determinant.

The present question is:

> **Can a compatible family of finite event counts on such an enclosingly determined intersection lattice admit a real classical completion whose uniquely induced Borel measure is exactly the Liouville measure? What additional completion, symmetry, and calibration data are necessary?**

We establish an explicit affirmative consistency result while distinguishing the finite theorem from the chosen real-completion condition. We do not require uniqueness of the R²D primitive owner or exclusion of alternative physical representations.

## 155.2. The integral intersection lattice before physical phase space

Let $X_J$ be a selected connected closed oriented cellular surface determined from complete attachment compatibility as in Addendum 153 or, conditionally, Addendum 154. Write

$$
\boxed{L=H_1(X_J;\mathbb Z)\cong\mathbb Z^{2g},\qquad g\ge1.}
\tag{155.1}
$$

The owner supplies an integral intersection pairing

$$
\boxed{I:L\times L\longrightarrow\mathbb Z}
\tag{155.2}
$$

which is bilinear, alternating, and unimodular. In the particular complete closures under consideration, choose an integral symplectic basis $(a_1,b_1,\ldots,a_g,b_g)$, giving

$$
\boxed{I(u,v)=u^{\mathsf T}\mathbb J_gv,\qquad
\mathbb J_g=\operatorname{diag}(J_2,\ldots,J_2),\qquad
J_2=\begin{pmatrix}0&1\\-1&0\end{pmatrix}.}
\tag{155.3}
$$

The form has $\det\mathbb J_g=1$. Its sign changes if the complete orientation convention is reversed; its nondegeneracy does not.

**Interpretive distinction.** $X_J$ is the cellular complex used to classify the completed oriented relations. The real classical phase space constructed below is a different mathematical object, namely a real completion of $H_1(X_J;\mathbb Z)$ and, initially, a quotient of that completion. We do not identify a genus-$g$ cellular surface with a physical phase-space manifold of dimension $2g$.

For each $N\ge2$, reduce only the recurrence labels and pairing:

$$
\boxed{V_N=L/NL\cong(\mathbb Z/N\mathbb Z)^{2g},\qquad
I_N(\bar u,\bar v)=I(u,v)\bmod N.}
\tag{155.4}
$$

Because $\det\mathbb J_g=1$ is invertible modulo every $N$, $I_N$ is nondegenerate even for composite moduli. The finite domain has exactly $N^{2g}$ distinguishable labels. These label **possible count classifications**, not realized occurrences.

## 155.3. Theorem 155.1 — Exact consistency of finite modular count measures

Equip each $V_N$ with the full finite event algebra and counting measure:

$$
\boxed{\Sigma_N=\mathcal P(V_N),\qquad
m_N(E)=|E|,\qquad
U_N(E)=\frac{|E|}{N^{2g}}.}
\tag{155.5}
$$

The normalized measure $U_N$ is selected by treating the $N^{2g}$ distinct labels uniformly. This is a **possible-label normalization**, not a realized stochastic law. It is the unique normalized measure invariant under every translation of the finite abelian group $V_N$; that transitive translation symmetry belongs to the selected finite label owner, not automatically to every R²D system.

For $N\mid M$, reduction defines

$$
\boxed{r_{M\to N}:V_M\longrightarrow V_N.}
\tag{155.6}
$$

**Theorem 155.1 — Equal-fiber projective count consistency.** For every $N\mid M$ and every event $E\subseteq V_N$,

$$
\boxed{U_M\!\left(r_{M\to N}^{-1}(E)\right)=U_N(E).}
\tag{155.7}
$$

Moreover, the finite alternating pairings commute with reduction:

$$
I_N(r_{M\to N}\bar u,r_{M\to N}\bar v)
=r_{M\to N}\bigl(I_M(\bar u,\bar v)\bigr).
\tag{155.8}
$$

**Proof.** Write $M=kN$. Each residue label in $V_N$ has exactly $k^{2g}$ lifts in $V_M$. Thus the numerator of the finer normalized measure is $k^{2g}|E|$, and its denominator is $(kN)^{2g}$; their ratio is $|E|/N^{2g}$. Reduction of the integer bilinear form proves (155.8). $\square$

The distinction from Addendum 152 is structural: the complete fibers of this finite reduction owner all have the **same cardinality**. The earlier process-prefix owners generally did not.

### An obstruction that must not be skipped

The inverse-limit count space

$$
\varprojlim_N V_N
\tag{155.9}
$$

with the modular reduction maps is a **profinite** topological group (isomorphic to $\widehat{\mathbb Z}^{\,2g}$ when all moduli are included). It is not $\mathbb R^{2g}$ and not $\mathbb R^{2g}/\mathbb Z^{2g}$. Its natural limiting measure is profinite Haar measure, not automatically classical Liouville measure on a real manifold.

Thus **(155.7) is necessary finite compatibility information for this route, but is not a derivation of the real continuum**. The next construction makes the additional mathematical completion explicit.

## 155.4. Specify the real affine completion and its finite cell reads

Select the real extension already used conditionally in Addendum 153:

$$
\boxed{L_{\mathbb R}=L\otimes_{\mathbb Z}\mathbb R
\cong\mathbb R^{2g}.}
\tag{155.10}
$$

This is a declared **receiving mathematical representation**. Finite counting alone does not require or uniquely determine the ordered field $\mathbb R$, its topology, or any physical ruler. For a compact, normalized example form

$$
\boxed{T=L_{\mathbb R}/L\cong\mathbb R^{2g}/\mathbb Z^{2g}.}
\tag{155.11}
$$

Use the integral symplectic basis of (155.3) to choose the half-open fundamental region $F=[0,1)^{2g}$ and dimensionless real coordinates $(x_1,y_1,\ldots,x_g,y_g)$. No physical position or momentum meaning is assigned to them at this step.

For $k\ge0$, put $N_k=2^k$. Divide $F$ into $N_k^{2g}$ half-open dyadic cells

$$
\boxed{Q_{k,\mathbf j}=\prod_{r=1}^{2g}
\left[\frac{j_r}{2^k},\frac{j_r+1}{2^k}\right),
\quad \mathbf j\in\{0,\ldots,2^k-1\}^{2g}.}
\tag{155.12}
$$

Each cell is assigned one distinct finite label. Let $\mathcal Q_k$ denote this finite cell set and $\mathcal A_k$ the algebra of unions of its cells. Set

$$
\boxed{U_k^{\rm cell}(A)=\frac{\#\{Q\in\mathcal Q_k:Q\subseteq A\}}{2^{2gk}},\qquad A\in\mathcal A_k.}
\tag{155.13}
$$

These are again finite counting measures, now on **cells in the specified real completion**, not on an independently given physical probability density.

When the resolution increases from $k$ to $k+1$, every cell has exactly $2^{2g}$ child cells. The resulting parent map is

$$
\boxed{\pi_{k+1,k}(\mathbf j)_r=\left\lfloor\frac{j_r}{2}\right\rfloor.}
\tag{155.14}
$$

**The modular map and the cell map are not the same map.** Modular reduction uses $\mathbf j\bmod 2^k$ on residue labels. Dyadic cell containment uses $\lfloor\mathbf j/2\rfloor$. Although their underlying finite label sets have the same cardinalities, their two refinement relationships must not be substituted for one another. In particular, the cell map uses the chosen real affine ordering; it is not an additional consequence of (155.7).

**Lemma 155.2 — Uniform dyadic refinement compatibility.** For $A\in\mathcal A_k$,

$$
\boxed{U_{k+1}^{\rm cell}(A)=U_k^{\rm cell}(A).}
\tag{155.15}
$$

**Proof.** If $A$ contains $r$ coarse cells, it contains precisely $2^{2g}r$ finer cells. Divide by the total number $2^{2g(k+1)}$ of finer cells. The result is $r/2^{2gk}$. $\square$

Because every cell and every distinct refinement is counted exactly once, this is a model of admissible recursive replacement with constant compatible extension count. If a physical owner has unequal refinement multiplicities, uniform possible count need not survive the projection; this condition must be tested for that owner.

## 155.5. Theorem 155.3 — Unique Borel extension of compatible counts

Let $\mathcal A=\bigcup_{k\ge0}\mathcal A_k$ (using the natural inclusion of coarser cell events among finer ones). Lemma 155.2 gives a well-defined normalized nonnegative assignment $U^{\rm cell}$ on this algebra. The $\mathcal A_k$ form a nested family, and their union generates the Borel sigma-algebra of the selected torus $T$.

**Theorem 155.3 — Finite-cell count to Borel measure.** The compatible count assignment (155.13) has a **unique Borel probability-measure extension** $\mu_{\rm count}$ on $T$. For every dyadic cell,

$$
\boxed{\mu_{\rm count}(Q_{k,\mathbf j})=2^{-2gk}.}
\tag{155.16}
$$

For every half-open axis-parallel rectangle $R=\prod_{r=1}^{2g}[a_r,b_r)$ represented in the fundamental region,

$$
\boxed{\mu_{\rm count}(R)=\prod_{r=1}^{2g}(b_r-a_r).}
\tag{155.17}
$$

**Proof.** One construction avoids presupposing a phase-space density. At each subdivision step, give each of the $2^{2g}$ equally admitted child-label words the probability $2^{-2g}$. These finite cylinder assignments are consistent and yield the usual product measure on infinite binary label sequences. Map the binary sequence in each coordinate to its point $x_r=\sum_{k\ge1}\epsilon_{r,k}2^{-k}\pmod1$. The exceptional sequences with ambiguous binary endpoints form a null set, because an individual infinite specified tail has probability zero. The pushforward is a Borel probability measure on $T$ assigning exactly $2^{-2gk}$ to every dyadic cell.

Dyadic cells generate the selected Borel sigma-algebra, so any two Borel probabilities with the prescribed cell values agree by the uniqueness theorem for measures on a generating algebra (or the $\pi$–$\lambda$ theorem). This proves existence and uniqueness. Formula (155.17) follows first for rectangles whose endpoints are dyadic rationals, by exact finite cell counting, and then for arbitrary endpoints by nested dyadic approximation and continuity of the finite measure. $\square$

This theorem is a **count-derived measure extension on a specified real Borel space**. It uses the ordinary mathematical probability-measure extension theorem as part of the representation; it does not identify equally possible labels with equally frequent realized occurrences.

In particular, $\mu_{\rm count}$ is the normalized Lebesgue measure in the selected affine chart. It is also the normalized Haar measure of the compact additive group $T$, since the rectangle formula gives translation invariance and normalized Haar probability is unique.

### Exact finite example

For $g=1$, consider $E=[0,1/2)\times[0,3/4)$. At resolution $N=4$, six of sixteen cells lie in $E$; at resolution $N=8$, twenty-four of sixty-four do. Therefore

$$
\boxed{U_2^{\rm cell}(E)=\frac6{16}
=U_3^{\rm cell}(E)=\frac{24}{64}=\frac38
=\mu_{\rm count}(E).}
\tag{155.18}
$$

For every continuous $f:T\to\mathbb R$, the corresponding uniform grid averages converge:

$$
\boxed{\lim_{k\to\infty}\frac{1}{2^{2gk}}
\sum_{\mathbf j} f\!\left(\frac{\mathbf j}{2^k}\right)
=\int_T f\,d\mu_{\rm count}.}
\tag{155.19}
$$

This follows because $f$ is uniformly continuous on compact $T$: the difference between each cell average and a chosen point value is bounded by the modulus of continuity at the cell diameter.

## 155.6. Theorem 155.4 — Identification with the classical Liouville measure

Return to the integral intersection pairing $I$ supplied by the complete finite owner. Extend it real-bilinearly to $L_{\mathbb R}$:

$$
\boxed{\omega_x(v,w)=I_{\mathbb R}(v,w),\qquad x\in L_{\mathbb R}.}
\tag{155.20}
$$

Because this alternating form is constant and translation-invariant, it descends to $T$. In the chosen paired real coordinates its representation is

$$
\boxed{\omega=\sum_{i=1}^{g}dx_i\wedge dy_i.}
\tag{155.21}
$$

This is a symplectic form: it is closed ($d\omega=0$), and its coefficient matrix is $\mathbb J_g$, whose determinant is one. At this stage $x_i,y_i$ are **dimensionless real recurrence-class coordinates**, not measured positions and momenta.

Its top exterior power is

$$
\boxed{\Omega_L=\frac{\omega^{\wedge g}}{g!}
=dx_1\wedge dy_1\wedge\cdots\wedge dx_g\wedge dy_g.}
\tag{155.22}
$$

The associated positive Liouville measure of a Borel event $E$ is $\mu_L(E)=\int_E|\Omega_L|$, where the bars indicate the positive density obtained from the oriented top form.

**Theorem 155.4 — Exact count/Liouville equality on the selected continuum.** For the chosen real affine completion of the unimodular intersection lattice,

$$
\boxed{\mu_{\rm count}(E)=\mu_L(E)
\qquad\text{for every Borel }E\subseteq T.}
\tag{155.23}
$$

**Proof.** On a dyadic cell $Q_{k,\mathbf j}$, the constant top-form density in (155.22) gives

$$
\int_{Q_{k,\mathbf j}}|\Omega_L|
=\bigl(2^{-k}\bigr)^{2g}=2^{-2gk}.
$$

By (155.16), this equals the finite count-derived cell measure. Both are Borel probability measures, since the total Liouville volume of the unit fundamental region is one. They agree on the generating dyadic algebra, so they agree on every Borel set. $\square$

This is an **equality of measures**, not an analogy between uniform counting and classical volume.

### Why the intersection pairing is indispensable

Uniform cell counts on a real torus can produce its normalized Haar measure even if no symplectic form has been specified. **Counting alone does not select $\omega$.** The role of Addenda 153–154 is to supply an independent, nondegenerate alternating pairing; only then can the count-derived Borel measure be *identified as Liouville measure for that specified symplectic structure*.

Unimodularity fixes the normalization match. For a general integral alternating matrix $K$, the symplectic volume of the standard unit lattice fundamental region is $|\operatorname{Pf}(K)|$. In the present models $|\operatorname{Pf}(\mathbb J_g)|=1$, so no further normalization is needed. For a non-unimodular pairing, normalized count/Haar measure would equal the **normalized** symplectic volume rather than the unnormalized Liouville volume.

A simultaneous reversal of the enclosing orientation changes $I$ and $\omega$ by a sign, but leaves the associated positive volume density and nondegeneracy unchanged. Thus the positive count/Liouville measure does not require choosing an absolute physical handedness.

## 155.7. Theorem 155.5 — Finite symplectic transformations preserve the count measure

Let $M:L\to L$ be an integral recurrence-class automorphism satisfying the test already isolated in Addendum 153:

$$
\boxed{M^{\mathsf T}\mathbb J_gM=\mathbb J_g.}
\tag{155.24}
$$

For every $N$, reduction of $M$ gives a bijection $\bar M_N:V_N\to V_N$ preserving $I_N$. It is therefore a permutation of the $N^{2g}$ distinguishable finite labels.

**Theorem 155.5 — Symplectic count invariance.** Every such $M$ satisfies

$$
\boxed{U_N(\bar M_N E)=U_N(E)
\quad\text{for all }E\subseteq V_N,\ N\ge2,}
\tag{155.25}
$$

and its real torus automorphism satisfies

$$
\boxed{M^*\omega=\omega,\qquad
\mu_L(ME)=\mu_L(E)
\quad\text{for Borel }E\subseteq T.}
\tag{155.26}
$$

**Proof.** The finite claim follows because a bijection preserves the cardinality of every event. The integral symplectic identity gives $M^*\omega=\omega$ on the real extension and hence on the torus. Taking the $g$th wedge power preserves the positive Liouville measure, which equals $\mu_{\rm count}$ by Theorem 155.4. $\square$

The modular reductions and $M$ commute. The chosen **dyadic parent maps need not commute with $M$**, because an integer symplectic map need not send every dyadic cube to another cube at the same resolution. This is not an obstruction to preservation of the *continuum measure*: that follows from the symplectic identity, not from a false claim of exact cell-partition equivariance.

### Counterexample — Liouville volume does not determine symplectic structure

For $g=2$, use the $4\times4$ block-diagonal $\mathbb J_2$ of Addendum 153. Consider

$$
\boxed{V=\begin{pmatrix}
1&0&1&0\\
0&1&0&0\\
0&0&1&0\\
0&0&0&1
\end{pmatrix},\qquad
\det V=1,\qquad
V^{\mathsf T}\mathbb J_2V\ne\mathbb J_2.}
\tag{155.27}
$$

This integer automorphism permutes every finite modular count domain and preserves its uniform count measure. Its real extension preserves the top-dimensional volume density because $\det V=1$. Nevertheless, it changes the pairing between recurrence generators in the first and second symplectic blocks, so it is **not symplectic**.

Therefore a measure-preserving count representation is insufficient to select classical symplectic mechanics. The independent intersection structure of Addenda 153–154 is essential, especially for two or more degrees of freedom.

## 155.8. Theorem 155.6 — Conditional Hamiltonian invariance (Liouville's theorem)

A symplectic continuum does not by itself specify evolution. To consider classical Hamiltonian mechanics, select a smooth globally defined function $H:T\to\mathbb R$, or a smooth Hamiltonian on the noncompact real extension. Define the Hamiltonian vector field by the sign convention

$$
\boxed{\iota_{X_H}\omega=dH.}
\tag{155.28}
$$

Since $\omega$ is closed, Cartan's identity gives

$$
\mathcal L_{X_H}\omega
=d(\iota_{X_H}\omega)+\iota_{X_H}(d\omega)
=d^2H=0.
\tag{155.29}
$$

**Theorem 155.6 — Liouville invariance of admitted Hamiltonian evolution.** Wherever the flow $\Phi_t$ of $X_H$ is defined,

$$
\boxed{\Phi_t^*\omega=\omega,
\qquad\Phi_t^*\left(\frac{\omega^{\wedge g}}{g!}\right)
=\frac{\omega^{\wedge g}}{g!},
\qquad\mu_L(\Phi_tE)=\mu_L(E).}
\tag{155.30}
$$

**Proof.** Differentiating the pullback along the flow yields

$$
\frac{d}{dt}\Phi_t^*\omega
=\Phi_t^*(\mathcal L_{X_H}\omega)=0.
$$

Since $\Phi_0$ is the identity, $\Phi_t^*\omega=\omega$. Taking wedge powers proves invariance of the Liouville top form and its positive measure. $\square$

On compact $T$, every smooth autonomous Hamiltonian vector field is complete. On noncompact $L_{\mathbb R}$ the claim is restricted to flow times for which solutions exist; smoothness alone does not ensure global completeness.

**A globally valid torus example.** In one canonical pair, choose

$$
H(x,y)=\frac{1-\cos(2\pi y)}{2\pi}.
$$

It is well defined on $T=\mathbb R^2/\mathbb Z^2$. The associated flow is

$$
\Phi_t(x,y)=(x+t\sin(2\pi y),\ y)\pmod1.
\tag{155.31}
$$

It is nontrivial, smooth, and preserves $dx\wedge dy$ and the count-derived Borel measure.

**Relation to the integral shear of Addendum 153.** The integer shear $(x,y)\mapsto(x+y,y)$ is an integral symplectic torus automorphism and preserves finite modular count. The noncompact Hamiltonian $H=\tfrac12y^2$ generates the shear continuously on $\mathbb R^2$, but $H$ is not a globally single-valued function on the compact torus. Its finite and noncompact representations must not be conflated with a global Hamiltonian isotopy of the torus.

The Hamiltonian or physical clock is an **additional selected representation**. Liouville's theorem proves preservation by such an admitted evolution; it does not derive which $H$ a physical experiment must realize.

## 155.9. Noncompact flat phase space and physical calibration

The compact torus $T$ is a convenient finite-total-measure witness. Standard classical phase spaces are often noncompact. The same cell-count construction extends locally to $L_{\mathbb R}\cong\mathbb R^{2g}$.

Partition $\mathbb R^{2g}$ into half-open cubes of side $2^{-k}$. For a bounded rectangle $R$, count the cells contained in $R$ and assign each cell weight $2^{-2gk}$. The counting limit gives

$$
\boxed{\lim_{k\to\infty}2^{-2gk}
\#\{Q_{k,\mathbf j}\subseteq R\}
=\prod_{r=1}^{2g}(b_r-a_r),
\quad R=\prod_r[a_r,b_r).}
\tag{155.32}
$$

Boundary discrepancies occupy a vanishing fraction of the bounded grid. By standard Borel-measure extension this produces the unique sigma-finite Lebesgue measure on the noncompact real completion, equal to the Liouville measure of the constant $\omega$ from (155.21). It is not a normalized global probability measure: the full noncompact phase space has infinite volume.

A receiving physical background can calibrate the dimensionless real coordinates by chosen scales, for example

$$
\boxed{q_i=\ell_i x_i,
\qquad p_i=\kappa_i y_i,\qquad
\ell_i,\kappa_i>0.}
\tag{155.33}
$$

The usual physically calibrated canonical form and its positive Liouville density are

$$
\boxed{\omega_{\rm phys}=\sum_{i=1}^{g}dq_i\wedge dp_i,
\qquad d\mu_{L,\rm phys}
=\prod_{i=1}^{g}dq_i\,dp_i
=\left(\prod_i\ell_i\kappa_i\right)
\prod_{i=1}^{g}dx_i\,dy_i.}
\tag{155.34}
$$

The product of scales is the physical volume calibration. If the individual products $\ell_i\kappa_i$ differ, $\omega_{\rm phys}$ is not simply a single common multiple of the dimensionless form; its **top-density** has the indicated product factor. The primitive finite count does not determine absolute meters, seconds, momenta, action units, or the numerical calibration of a particular experimental Hamiltonian.

A microcanonical measure restricted to a physical energy surface is a further **conditional** construction involving a specified Hamiltonian and suitable disintegration or energy-shell measure. It is not identical to the full Liouville measure obtained here.

## 155.10. Why uniform counting is a genuine condition, not a general law

The cell result depended on a strong, testable mathematical property: **every coarse cell had exactly the same number of compatible finer cells**. Equal cardinality of individual finite state domains is not enough.

Consider a coarse owner with two labels $a,b$ assigned equal normalized counts $1/2$ each. Let a finer owner admit one extension of $a$ and three extensions of $b$. Uniform counting on its four fine labels gives pushforward weights

$$
\boxed{(U_{\rm coarse}(a),U_{\rm coarse}(b))=(1/2,1/2),
\qquad (r_*U_{\rm fine})(a,b)=(1/4,3/4).}
\tag{155.35}
$$

These disagree. Therefore independently uniform finite count measures do not generally define a consistent continuum measure, let alone Liouville measure. This is the same logical obstruction illustrated by the unequal process extensions in Addendum 152.

Even when equal-fiber refinement holds, it does not select a *unique* real completion or a symplectic form by itself. Other refinements and measurable representations may exist. The exact Liouville identification requires the **joint specification** of (i) the enclosingly selected unimodular intersection pairing, (ii) a compatible uniform finite cell-refinement owner, and (iii) the affine real Borel completion on which the pairing extends as a constant two-form.

Similarly, a uniform measure over possible distinguishable cells does not imply equal residence time, ergodicity, equidistribution of realized occurrences, a Markov kernel, or microscopic random choice. R²D's $W$, $\Theta$, realized $\nu$, structural occupancy, and whole-closure recurrence remain distinct count types.

## 155.11. Relationship to the canon and to standard classical mechanics

This reconstruction keeps the mathematical and causal order explicit:

$$
\boxed{\begin{gathered}
\text{Complete boundary-owned oriented closure}
\Longrightarrow (L,I),\\
\text{finite admitted recurrence labels}
\Longrightarrow (V_N,I_N,\Sigma_N,U_N),\\
\text{selected uniform real-affine refinement}
\Longrightarrow (T,\mathcal B(T),\mu_{\rm count}),\\
\text{real extension of the complete intersection pairing}
\Longrightarrow (T,\omega),\\
\text{exact identification}
\Longrightarrow \mu_{\rm count}=\mu_L,\\
\text{admitted smooth Hamiltonian evolution}
\Longrightarrow (\Phi_t)_*\mu_L=\mu_L.
\end{gathered}}
\tag{155.36}
$$

The first arrow is the conditional attachment reconstruction of Addenda 153–154. The second is finite algebra and cardinality. The third is **not forced by the second**: it explicitly introduces a real affine completion and a regular compatible cell scheme. The fourth identifies the real symplectic structure from the existing integral intersection counts rather than inferring it from volume preservation. The fifth is a measure-identification theorem. The last is the familiar classical Liouville theorem for the admitted Hamiltonian read.

This is not a claim that standard classical mechanics is false or that its familiar mathematical theorems are newly proved in the abstract. The novel role within R²D is an explicitly ordered **finite consistency witness and reconstruction map** from one specified boundary-owned count relation to a standard continuum measure, with the extra representation conditions stated rather than obscured.

The comparison with mathematical reconstruction programs can now be made on concrete objects: $V_N$, $\Sigma_N$, $U_N$, the two distinct refinement maps, $\mathcal B(T)$, $\mu_{\rm count}$, $I$, $\omega$, and the selected flow $\Phi_t$. This supplies an exact answer to the classical-measure question without assuming that the same argument reconstructs the general nonadditive event structures of quantum measurement.

## 155.12. Results, limitations, and the next selection question

**Established for the specified owners:**

1. A complete oriented closure with unimodular $H_1$ pairing has explicit nondegenerate finite symplectic modules $(V_N,I_N)$ at every modulus and uniform finite event measures.
2. Those normalized finite counts are exactly consistent under modular reduction; their inverse limit is profinite and must not be identified with real phase space.
3. After an explicitly selected real affine completion, equal-fiber dyadic cell refinements give a unique regular Borel probability measure, determined solely by the compatible finite cell counts.
4. The measure equals the Liouville measure of the real extension of the pre-existing intersection pairing because both have identical weights on every generating cell and unimodularity fixes the total normalization.
5. Integral symplectic recurrence maps preserve the finite measures and the continuum Liouville measure; a count-/volume-preserving nonsymplectic map shows that the converse fails in four dimensions.
6. Every admitted smooth Hamiltonian flow preserves the symplectic form and its Liouville measure on its interval of existence; a globally defined torus example and noncompact shear example separate the relevant global conditions.
7. A noncompact flat read yields sigma-finite Liouville measure, and physical position–momentum units enter through separately calibrated background scales.

**Not established:** derivation of $\mathbb R$ or its topology from finite counting alone; uniqueness of the real affine completion; that all R²D boundary changes have equal-fiber refinements; realization frequencies or rates from possible counts; an arbitrary curved or cotangent-bundle phase space from the same finite owner; a unique physical Hamiltonian; a quantum non-Boolean/nonadditive measure; or a specific physical apparatus's calibration and experimental selection of all completion conditions.

The next mathematically discriminating question is:

> **Can a specified nested family of *physical* complete enclosing comparisons select its compatible real affine completion and uniform symplectic cell-refinement structure, rather than merely admit the flat representation used here?**

That selection problem is distinct from—and not a prerequisite for—the exact existence and measure-identification theorem proved in this addendum.

## Conclusion

A single complete enclosing intersection structure can support finite count measures whose compatible real-cell refinements reproduce the classical Liouville measure **exactly**. The decisive result is the equality

$$
\boxed{\mu_{\rm count}(E)=\int_E\left|\frac{\omega^{\wedge g}}{g!}\right|,
\qquad E\in\mathcal B(T),\qquad
\omega=\sum_{i=1}^{g}dx_i\wedge dy_i.}
\tag{155.37}
$$

The count side is defined on finite, uniform, refining event cells and extended by measure theory; the symplectic side is determined by the integral intersection relation of the complete oriented closure. Their equality is a theorem for the specified real completion, not an assumption that all uniform counting is inherently symplectic. Hamiltonian measure invariance follows for every smooth admitted Hamiltonian flow.

The chain of reconstruction is **complete enclosing closure $\to$ unimodular intersection lattice $\to$ compatible finite cell counts $\to$ Borel measure $=$ Liouville measure $\to$ conditional Hamiltonian invariance**. This places one classical mathematical structure on an explicit R²D finite-count foundation while preserving the boundary ownership, read-resolution, and realization distinctions of the canon.

---

## Related canon, addenda, and mathematical background

- **R²D Part I:** native boundary-relative multiplicity, compatible extension, possible count, realized occurrence, closure, and recursive replacement.
- **R²D Part II:** thermal state and residence readings, background calibration, and physical energy accounting.
- **Addenda 116, 120, 122, and 125:** directed incidence, native identity, complete enclosing composability, and the distinction between possible and realized closure counts.
- **Addenda 131 and 139:** complete background-relative recurrence and survival of selected relational comparisons.
- **Addenda 150–151:** one common finite enclosing owner, reciprocal exchange, and nested constraint compatibility without double counting.
- **Addendum 152:** finite state/process sigma-algebras and the precise obstruction to independent uniform measures on differently extended process lengths.
- **Addendum 153:** unimodular intersection pairings, finite modular symplectic modules, recursive preservation, non-symplectic volume-preserving counterexample, and conditional real/classical projection.
- **Addendum 154:** the two-junction genus-one finite witness, non-identifiability of attachment from temporal records alone, and exact conditional reconstruction from complete corner-and-side records.
- **Standard measure theory:** dyadic semi-algebras, Borel measure extension, and uniform binary-digit construction; see *A Dyadic Approach to Lebesgue Theory*, Washington University in St. Louis, https://cpb-us-w2.wpmucdn.com/sites.wustl.edu/dist/7/2589/files/2020/05/SP2020-MA4121-LN.pdf.
- **Standard symplectic geometry:** symplectic volume and Hamiltonian Liouville invariance; see the University of Regensburg symplectic geometry notes, https://ammann.app.uni-regensburg.de/lehre/2017w_symplectic/cieliebak_symplectic-geometry-a.pdf.
- **Standard Haar measure:** normalized Lebesgue measure as Haar measure on the real torus; see https://people.dm.unipi.it/abate/matdid/dispense/files/SistDinDisc_cap4.pdf.

**Review status:** Author-approved for canon publication. The distinction between profinite modular reduction and real cell refinement, and the explicit real-completion and uniform-refinement assumptions, are essential to the claim. Removing them would turn a conditional exact reconstruction into an unsupported derivation of the real continuum from finite cardinality alone.
