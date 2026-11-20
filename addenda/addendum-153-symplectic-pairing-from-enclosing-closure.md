---
r2d_id: "addendum-153"
title: "Addendum 153 — Symplectic Pairing from Enclosing Closure"
subtitle: "Oriented Intersection Counts, Recursive Preservation, and the Classical Continuum Projection"
source_type: "addendum"
authority: "addendum"
primitive_authority: false
addendum: 153
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
scope: "Finite oriented complete-closure data beyond first-order incidence; an exact genus-two intersection pairing; modular finite symplectic modules; preservation under admissible cellular refinement and recurrence automorphisms; counterexample to incidence-only determination; calibrated symplectic and conditional Hamiltonian projections"
---

# R²D Addendum 153 — Symplectic Pairing from Enclosing Closure

*Oriented Intersection Counts, Recursive Preservation, and the Classical Continuum Projection*

**Status:** Author-approved for canon publication — November 20, 2026  
**Canonical basis:** R²D Parts I–IV (September 25, 2026); especially Addenda 116, 120, 122, 125, 131, 139, and 152.  
**Scope:** Finite mathematical reconstruction and exact consistency demonstration; not a claim that the R²D axioms uniquely select all symplectic phase spaces.

## Abstract

Addendum 116 formalized enclosing conservation by signed interface incidence, and Addendum 152 separated finite state, process, and complete-comparison counts. A subsequent classical continuum construction showed that reversible count-preserving processes may admit Liouville measure and Hamiltonian physical readings. A missing step remained: ordinary conservation and counting do not specify the **nondegenerate alternating pairing** that distinguishes symplectic geometry from mere volume preservation.

We show that a *specified complete, oriented two-dimensional closure relation* supplies this pairing without taking position, momentum, a physical field, or a symplectic form as primitive. One finite enclosing owner admits four oriented recurrence classes and the complete cyclic attachment

$$
\mathcal C_J=a_1b_1a_1^{-1}b_1^{-1}a_2b_2a_2^{-1}b_2^{-1}.
$$

Its finite cellular realization is a closed oriented genus-two surface. The compatible algebraic intersection count on its four first-homology generators yields an alternating integral matrix $\mathbb J$ of determinant one. Reduction modulo every integer $N\ge2$ gives a nondegenerate finite alternating pairing. Orientation-preserving cellular refinements preserve the integral intersection relationship, while selected complete recurrence transformations preserve it precisely when their induced linear maps satisfy $M^{\mathsf T}\mathbb JM=\mathbb J$. After a separately specified real and physical calibration, the same pairing admits the familiar classical two-degree-of-freedom symplectic representation.

An explicit counterexample is essential: a genus-two surface and a wedge of a sphere with four circles have the *same* cellular chain-group ranks and zero boundary matrices but different cup-product pairings. Hence first-order incidence, conservation, and the chain relation $\partial_1\partial_2=0$ **do not determine** symplectic structure. The extra datum is the complete oriented attachment/intersection compatibility of closures. The result establishes an exact finite **existence and reconstruction conditional on that datum**, and isolates what a stronger R²D selection theorem would have to determine.

---

## 153.1. Reconstruction question and logical ordering

Part I defines distinguishable native states and their enclosing compatibility before physical geometry or microscopic trajectories. Addendum 116 supplies an oriented interface-incidence matrix $D$, regional count changes, and conservation:

$$
\Delta\mathbf x=-D\Delta\mathbf z,
\qquad \mathbf 1^{\mathsf T}D=0.
\tag{153.1}
$$

For a completed return of the selected regional classification, $\Delta\mathbf x=0$, so the interfacial output is a cycle:

$$
\boxed{D\Delta\mathbf z=0.}
\tag{153.2}
$$

The closed outputs form $Z_1=\ker D$. In Addendum 152, states, one-step processes, and complete processes are separate count domains, and an enclosing owner—not arbitrary composition of adjacent observations—specifies which whole comparisons are admissible.

These results do not yet imply an alternating form. The question here is more specific:

**Can an enclosingly specified complete oriented closure provide a nondegenerate signed pairing between two closed recurrence classes, so that the pairing survives admissible recursive replacement and has classical symplectic geometry as a calibrated read?**

We answer yes by explicit construction. The construction is **not** a claim that Equation (153.2) alone implies the required pairing.

## 153.2. First-order incidence versus complete closure information

Let $C_1$ be a free abelian group generated by directed interface or recurrence classes, with inverses representing opposite orientations. Let $C_0$ count their incident regions, and $\partial_1:C_1\to C_0$ be the signed incidence operator. A closed one-dimensional comparison belongs to $\ker\partial_1$.

Now admit complete oriented two-dimensional closure records, whose boundaries are cyclic words in the one-dimensional generators. Their linear boundary operator $\partial_2:C_2\to C_1$ records the **net signed appearances** of the generators. The elementary identity

$$
\boxed{\partial_1\partial_2=0}
\tag{153.3}
$$

states that a complete two-dimensional attachment has no unbalanced one-dimensional endpoint incidence.

Crucially, the linear chain complex forgets the *cyclic order* in which generators appear in the complete attachment. Oppositely oriented generators cancel in $\partial_2$, yet the ordering of their appearances can still distinguish their mutual oriented intersection.

The data needed for the present reconstruction are therefore:

1. A finite set of distinguishable oriented recurrence generators and their reversals.
2. The **complete cyclic attachment word**, not only its net signed boundary vector.
3. An enclosing choice of orientation for the complete closure.
4. An explicit class of replacement/refinement and recurrence maps preserving the complete relationship.

These constitute a specified admissible finite compatibility owner. They are not additional physical coordinates or a Hamiltonian law.

## 153.3. A minimal useful two-degree-of-freedom enclosing owner

Introduce four oriented recurrence classes $a_1,b_1,a_2,b_2$, each with a formal reverse. Specify one oriented complete closure by the cyclic word

$$
\boxed{\mathcal C_J=[a_1,b_1][a_2,b_2]}
\tag{153.4}
$$

where $[a,b]=aba^{-1}b^{-1}$ denotes a **word** of compatible oriented occurrences, not a numerical Poisson bracket or quantum commutator.

Expanding the complete record,

$$
\mathcal C_J=
 a_1b_1a_1^{-1}b_1^{-1}
 a_2b_2a_2^{-1}b_2^{-1}.
\tag{153.5}
$$

Represent the ordered boundary by one abstract oriented octagonal two-cell. Identify equally named edge pairs with opposing directed boundary labels. The resulting finite oriented cell complex $X_J$ has one vertex, four one-cells, and one two-cell. The standard edge identification produces a connected closed **orientable surface of genus two**, because its Euler characteristic is

$$
\chi(X_J)=1-4+1=-2=2-2(2).
\tag{153.6}
$$

This cell complex is a mathematical realization of the stipulated complete compatibility. It is **not** a claim that the physical enclosing boundary is literally an embedded genus-two surface, or that physical spatial area precedes the count classification.

Each generator appears once with each sign; hence

$$
\boxed{\partial_1=0,\qquad\partial_2=0.}
\tag{153.7}
$$

The first-homology group is therefore

$$
\boxed{H_1(X_J;\mathbb Z)\cong\mathbb Z^4.}
\tag{153.8}
$$

The fact that the boundary matrices vanish makes the next step especially informative: the alternating pairing will be determined by the *complete ordered attachment*, which those matrices have forgotten.

## 153.4. Derive the oriented intersection counts

A closed oriented surface admits a signed intersection number of transverse representatives of its one-dimensional homology classes. For the cell presentation (153.5), the two occurrences of each $a_i$ and $b_i$ alternate around their common four-edge block. After a small transverse perturbation, $a_i$ and $b_i$ have one signed intersection. Generators belonging to distinct blocks can be represented without transverse intersections. Opposite orientation reverses the intersection sign.

With orientation chosen so that the $a_i$-to-$b_i$ crossing is positive, the complete cyclic attachment determines

$$
\boxed{\begin{aligned}
I_J(a_i,b_i)&=+1,\\
I_J(b_i,a_i)&=-1,\\
I_J(a_i,a_j)&=I_J(b_i,b_j)=0,\\
I_J(a_i,b_j)&=0\quad(i\ne j).
\end{aligned}}
\tag{153.9}
$$

The intersection number is a signed count of oriented crossing **classes in the finite cellular presentation**. It is not a physical microscopic collision count. It depends on the enclosing orientation and attachment relation; it does not require identifying a persistent subordinate particle that travels along either cycle.

For arbitrary integer homology classes

$$
\begin{aligned}
u&=u_1a_1+u_2b_1+u_3a_2+u_4b_2,\\
v&=v_1a_1+v_2b_1+v_3a_2+v_4b_2,
\end{aligned}
$$

bilinearity of algebraic intersection gives

$$
\boxed{I_J(u,v)=u_1v_2-u_2v_1+u_3v_4-u_4v_3.}
\tag{153.10}
$$

Equivalently, with basis $(a_1,b_1,a_2,b_2)$,

$$
\boxed{I_J(u,v)=u^{\mathsf T}\mathbb Jv,\qquad
\mathbb J=
\begin{pmatrix}
0&1&0&0\\
-1&0&0&0\\
0&0&0&1\\
0&0&-1&0
\end{pmatrix}.}
\tag{153.11}
$$

The same bilinear form can be described through the oriented cup-product pairing on $H^1(X_J;\mathbb Z)$, evaluated on the fundamental two-dimensional class. The intersection and cup-product descriptions are related by Poincaré duality. We use the intersection count as the count-native presentation.

## 153.5. Theorem 153.1 — Exact integral nondegenerate alternating pairing

**Theorem.** The specified finite oriented closure (153.5) determines an integral bilinear pairing $I_J$ on $H_1(X_J;\mathbb Z)$ that is alternating, antisymmetric, and nondegenerate. In the chosen oriented basis its matrix is (153.11), with determinant one.

**Proof.** The oriented attachment gives the basis intersection numbers (153.9). Extending the intersection count bilinearly gives (153.10)–(153.11). Direct calculation yields

$$
I_J(u,u)=0,\qquad I_J(u,v)=-I_J(v,u),\qquad
\boxed{\det\mathbb J=1.}
\tag{153.12}
$$

Since $\det\mathbb J$ is a unit in $\mathbb Z$, the induced homomorphism from $H_1$ to its integer dual is an isomorphism. Thus the pairing is nondegenerate and unimodular. $\square$

A change of oriented homology basis changes the matrix by $\mathbb J\mapsto M^{\mathsf T}\mathbb JM$, but does not remove the pairing itself. Reversing the complete surface orientation changes the **sign** of $I_J$, not its nondegeneracy.

The theorem is an **existence and exact reconstruction** result from a specified complete finite closure. It is not a theorem that every boundary-owned cyclic return produces a surface intersection form.

## 153.6. Theorem 153.2 — Finite symplectic modules at every modulus

For an integer $N\ge2$, reduce the integral homology-label module and its pairing modulo $N$:

$$
\boxed{V_N=(\mathbb Z/N\mathbb Z)^4,\qquad
I_N(\bar u,\bar v)=\bar u^{\mathsf T}\mathbb J\bar v\pmod N.}
\tag{153.13}
$$

**Theorem.** $I_N$ is alternating and nondegenerate for every integer $N\ge2$, including composite $N$.

**Proof.** Bilinearity and alternation descend from the integral form. The determinant of the induced matrix is $1$ modulo $N$, which is a unit in $\mathbb Z/N\mathbb Z$. Thus $\mathbb J$ has an inverse over this ring, and $I_N(u,v)=0$ for all $v$ implies $u=0$. $\square$

When $N=2$, antisymmetric matrices also appear symmetric after reducing signs, but $I_N(u,u)=0$ still holds for every $u$; the alternating property is not lost.

This produces a family of finite compatible alternating count structures with exactly $N^4$ label combinations. A finite **symplectic module** here means a finite module with this nondegenerate alternating bilinear pairing; it is not a smooth symplectic manifold.

## 153.7. Recursive replacement: what is preserved, and under which map

There are **two different operations** that should not be conflated.

**Cellular refinement.** An orientation-preserving subdivision of the complete oriented cell complex replaces cells and their local descriptions without changing the attached oriented surface. Let

$$
s:H_1(X_J;\mathbb Z)\longrightarrow H_1(X'_J;\mathbb Z)
$$

be the induced homology identification. The algebraic intersection number is unchanged:

$$
\boxed{I'_J(su,sv)=I_J(u,v).}
\tag{153.14}
$$

**Proof.** Subdivision gives an orientation-preserving topological identification of the same closed surface. Represent the two homology classes by transverse cycles; their signed intersection number is invariant under the identification, despite changes to their cellular representatives. $\square$

This is a mathematically explicit **model** of an admissible recursive replacement in which native representatives change but one relational count survives. Arbitrary R²D boundary changes need not induce such an isomorphism. The preservation claim applies only when the enclosing replacement supplies it.

**Change of finite modulus.** The passage from $V_N$ to $V_{N'}$ is not the same as cellular subdivision. For $N\mid N'$, reduction

$$
r_{N'\to N}:V_{N'}\to V_N
$$

preserves the pairing **after reduction**:

$$
\boxed{I_N(r u,r v)=r\bigl(I_{N'}(u,v)\bigr).}
\tag{153.15}
$$

There is generally no canonical embedding $V_N\hookrightarrow V_{N'}$ preserving these pairings as literally equal integers. Multiplying representatives by $N'/N$ can multiply the pairing by its square. Accordingly, we claim exact preservation under cellular refinement and compatible residue reduction, not an unjustified identity among all modular presentations.

## 153.8. Theorem 153.3 — Selected recurrence automorphisms preserve the count pairing

An admissible complete recurrence may induce an invertible integer transformation $M$ on the four identified recurrence classes. The pairing is preserved precisely when

$$
\boxed{M^{\mathsf T}\mathbb JM=\mathbb J.}
\tag{153.16}
$$

This is a *test on the enclosingly admitted transformation*, not a consequence of invertibility or count conservation alone.

For example, take the paired shear

$$
S=\begin{pmatrix}
1&1&0&0\\0&1&0&0\\0&0&1&1\\0&0&0&1
\end{pmatrix}.
\tag{153.17}
$$

Direct multiplication gives

$$
\boxed{S^{\mathsf T}\mathbb JS=\mathbb J.}
\tag{153.18}
$$

Thus $S$ induces an alternating-pairing-preserving permutation on $V_N$ for every $N$. If the complete recurrence is realized by an orientation-preserving self-map of the underlying surface, preservation of its intersection numbers supplies (153.16) automatically.

Contrast the integer transformation

$$
V=\begin{pmatrix}
1&0&1&0\\0&1&0&0\\0&0&1&0\\0&0&0&1
\end{pmatrix}.
\tag{153.19}
$$

It has $\det V=1$, is invertible modulo all $N$, and preserves the number of finite labels. Nevertheless,

$$
\boxed{V^{\mathsf T}\mathbb JV\ne\mathbb J.}
\tag{153.20}
$$

Indeed, it changes the pairing between $a_2$ and $b_1$ from zero to one, because $V(a_2)=a_1+a_2$ and $V(b_1)=b_1$.

**Theorem.** Count-preserving invertibility does not imply alternating-pairing preservation; (153.17) is a positive witness and (153.19) an explicit counterexample. $\square$

In two dimensions, preserving an oriented area form is closely related to symplectic preservation. This four-dimensional example distinguishes the requirements, as needed for reconstructing classical mechanics with more than one degree of freedom.

## 153.9. Theorem 153.4 — First-order incidence does not determine symplectic pairing

The missing-data question can be settled exactly, not merely stated as a caution.

Compare the complete oriented surface $X_J$ with the pointed wedge complex

$$
Y=S^2\vee S^1\vee S^1\vee S^1\vee S^1.
\tag{153.21}
$$

Both admit CW presentations with cellular chain groups

$$
C_2\cong\mathbb Z,
\qquad C_1\cong\mathbb Z^4,
\qquad C_0\cong\mathbb Z,
$$

and cellular boundary matrices

$$
\boxed{\partial_1=0,\qquad\partial_2=0.}
\tag{153.22}
$$

Their homology groups are consequently identical in each degree. But their multiplicative cohomology structures are not:

- For the oriented genus-two surface $X_J$, evaluation of the cup product $H^1\times H^1\to H^2\cong\mathbb Z$ is the nondegenerate form $\mathbb J$.
- For $Y$, all cup products of degree-one classes vanish. Its four circle classes do not generate a nontrivial degree-two intersection relation; the sphere contributes a separate $H^2$ class.

**Theorem.** The chain-group ranks, the signed incidence matrices, their composition $\partial_1\partial_2=0$, and even their additive homology groups do not determine the nondegenerate alternating pairing.

**Proof.** The two stated complexes have identical cellular chain complexes (153.22), hence identical additive homology. Their cup-product pairings differ, one nondegenerate and one zero. Thus those lower-order data cannot determine the pairing. $\square$

The full attaching word (153.5), together with complete orientation and its associated intersection structure, distinguishes $X_J$ from $Y$. It is therefore genuine additional **enclosing compatibility information**, not simply a new name for the signed incidence matrix of Addendum 116.

## 153.10. The classical continuum symplectic read

The integral recurrence-class pairing admits a real vector-space extension:

$$
\boxed{V_{\mathbb R}=H_1(X_J;\mathbb Z)\otimes_{\mathbb Z}\mathbb R\cong\mathbb R^4.}
\tag{153.23}
$$

Extend $I_J$ by real bilinearity. The resulting constant, nondegenerate alternating form may be interpreted on the tangent spaces of this *four-dimensional real vector space*. After introducing physical background scales and selecting canonical physical read coordinates $(q_1,p_1,q_2,p_2)$, choose a calibration that represents the pairings with the canonical normalization:

$$
\boxed{\omega=dq_1\wedge dp_1+dq_2\wedge dp_2.}
\tag{153.24}
$$

This is the standard symplectic form for two classical canonical pairs. Because its coefficients are constant,

$$
\boxed{d\omega=0,\qquad \omega\wedge\omega\ne0.}
\tag{153.25}
$$

Its Liouville volume is, with the chosen orientation,

$$
\boxed{d\mu_L=\frac{1}{2}\omega\wedge\omega.}
\tag{153.26}
$$

The physical *units* and absolute numerical calibration of $q_i,p_i$ do not follow from the integer intersection counts. Neither does a unique physical Hamiltonian. The construction provides a finite integer pairing with an admissible continuum symplectic representation, not a derivation of the real continuum from finite cardinality alone.

The real four-dimensional phase space is **not** the same object as the genus-two surface used to organize the finite closure. The surface supplied an intersection relation on its first homology. Its real extension supplied the linear phase-space pairing. Confusing those roles would incorrectly turn a mathematical representation of compatibility into a physical spatial surface.

## 153.11. Hamiltonian projection and its extra condition

One valid continuum physical read of the paired shear is the time-one map of a Hamiltonian flow on the calibrated *noncompact* real phase space:

$$
H(q_1,p_1,q_2,p_2)=\frac12(p_1^2+p_2^2).
\tag{153.27}
$$

With the convention $\iota_{X_H}\omega=dH$, the generator is

$$
\boxed{X_H=p_1\,\partial_{q_1}+p_2\,\partial_{q_2}.}
\tag{153.28}
$$

Thus

$$
F_t(q_1,p_1,q_2,p_2)
=(q_1+tp_1,p_1,q_2+tp_2,p_2),
\tag{153.29}
$$

and $F_1$ has the same matrix as the integer shear $S$ in the corresponding ordered basis. Units and masses can be included by calibrating the physical time and momentum/position scales.

More generally, symplectic preservation of a smooth flow gives a closed one-form $\iota_X\omega$; it is **Hamiltonian** when this one-form is exact, $\iota_X\omega=dH$. On spaces with nontrivial first cohomology, a symplectic flow need not have a globally defined Hamiltonian.

The $N$-modular finite shear and the real Hamiltonian flow are **two compatible representations**, not the same global geometric dynamical system. In particular, $H=\frac12(p_1^2+p_2^2)$ is not a globally single-valued function of periodic momentum on a compact phase-space torus. We do not transfer its Hamiltonian interpretation to such a torus without an additional valid global construction.

## 153.12. Generalization and the role of complete orientation

For $g\ge1$ oriented pairs $(a_i,b_i)$, let the enclosing owner admit the complete oriented surface word

$$
\boxed{\mathcal C_J^{(g)}=\prod_{i=1}^{g}[a_i,b_i].}
\tag{153.30}
$$

Its oriented closed surface presentation has genus $g$ and an integral first-homology pairing given in the corresponding basis by

$$
\boxed{\mathbb J_g=\operatorname{diag}(J_2,\ldots,J_2),\qquad
J_2=\begin{pmatrix}0&1\\-1&0\end{pmatrix}.}
\tag{153.31}
$$

This gives a nondegenerate alternating $2g$-dimensional integer pairing, and therefore finite pairings modulo every $N\ge2$. An admissible continuum real extension supports the corresponding $g$-degree-of-freedom canonical symplectic vector space.

Genus one is sufficient for the smallest nondegenerate alternating pair. **Genus two is the smallest useful witness for separating four-dimensional volume preservation from symplectic preservation**, as in Section 153.8.

The physically relevant selection problem remains: for a specified R²D system, what complete enclosing compatibility justifies a particular oriented two-dimensional closure, identifies its recurrence classes, and selects which completed process transformations preserve them? The formalism must not infer that every count-preserving recurrence is symplectic merely because one such enclosing presentation exists.

## 153.13. Relation to the established R²D count architecture

This reconstruction maintains the following distinctions:

- **Native multiplicity:** $W$ and $\Theta$ count compatible realizations of a specified owner. They are not replaced by intersection number.
- **Directed incidence:** $D\Delta\mathbf z=0$ is a closure/conservation relation; it is not the alternating intersection matrix $\mathbb J$.
- **Complete comparison:** the cyclic attachment $\mathcal C_J$ is an independently specified enclosing relationship. Its ordered information is not recoverable from net signed interface counts alone.
- **Recursive replacement:** the native cellular representatives may change while a chosen orientation-preserving homology identification preserves $I_J$; such an identification is a condition, not automatic across arbitrary boundaries.
- **Physical calibration:** the classical variables, symplectic form, Liouville volume, clock, and Hamiltonian are downstream readings of a selected compatible relation.
- **Recurrence:** possible oriented loops, realized completed closures, and the canon's recurrence-weighted $\Delta A\,N_{\mathcal C}=C_J\lambda_JN_{\chi_J}$ belong to different count comparisons. The topological intersection number does not determine realized recurrence frequency or override that law.

In particular, the genus-two two-cell records a **complete orientational closure classification**, not a positive realized return count. No conclusion about thermodynamic entropy production, viscosity, gravitational mass, or electromagnetic propagation follows from $\det\mathbb J=1$ alone.

## 153.14. Results, scope, and next selection problem

**Exact results for the specified complete owner:**

1. A cyclic oriented attachment $[a_1,b_1][a_2,b_2]$ defines a finite cellular surface with $H_1\cong\mathbb Z^4$ and integral intersection matrix $\mathbb J$.
2. The intersection count is alternating and unimodular, hence nondegenerate; reduction produces nondegenerate finite alternating pairings for every $N\ge2$.
3. Orientation-preserving cellular refinement preserves the integral pairing, and compatible modular reductions preserve it modulo the smaller modulus.
4. Selected recurrence maps preserve the pairing iff $M^{\mathsf T}\mathbb JM=\mathbb J$; a volume-preserving countermap can fail this test.
5. Two complexes with identical signed boundary operators and additive homology can have different intersection/cup-product pairings. Therefore the complete oriented attachment contributes indispensable information beyond first-order incidence.
6. A real extension with separately specified physical coordinate calibration produces the classical two-degree-of-freedom symplectic form and its Liouville measure; one selected shear admits an explicit Hamiltonian physical representation.

**Not established:** that Part I's primitive count axioms select a unique two-dimensional attachment; that all admissible boundary closures have a nondegenerate intersection form; that a physical $q,p$ identification is fixed by counting alone; that every symplectic recurrence admits a globally Hamiltonian clock; or that this model already reconstructs all classical interactions. These would be different, testable selection and calibration results.

The precise next question is:

> **Which boundary-owned compatibility conditions select a closed oriented two-dimensional incidence complex with unimodular intersection pairing, and which recursive replacements preserve that complete intersection relation?**

This is a stronger and better-defined question than asking whether conservation, reversibility, or finite multiplicity alone *implies* Hamiltonian mechanics.

## Conclusion

One complete enclosing oriented closure may determine a nondegenerate alternating count relation before classical position and momentum receive physical meaning:

$$
\boxed{\begin{gathered}
\mathcal C_J=[a_1,b_1][a_2,b_2],\\
I_J(u,v)=u^{\mathsf T}\mathbb Jv,\qquad \det\mathbb J=1,\\
I_N:\,(\mathbb Z/N\mathbb Z)^4\times(\mathbb Z/N\mathbb Z)^4\to\mathbb Z/N\mathbb Z,\\
M^{\mathsf T}\mathbb JM=\mathbb J,\\
\omega=dq_1\wedge dp_1+dq_2\wedge dp_2.
\end{gathered}}
$$

The chain of inference is **complete oriented compatibility $\to$ signed intersection count $\to$ finite alternating pairing $\to$ conditional continuum symplectic read**. Ordinary oriented incidence and conservation are insufficient: they discard the attachment order from which mutual intersection is recovered.

Thus R²D has a rigorous **symplectic consistency construction** based on one finite boundary-owned relation, and an exact statement of the extra enclosing information required to turn that construction into a more general mathematical reconstruction.

---

## Related Canon and Addenda

- **R²D Part I:** boundary-relative native state definitions, compatible multiplicity, oriented closure, retained constraint, and complete recurrence.
- **Addendum 116 — Conservation Before Transport:** signed interface incidence, closed total inventory, and directional throughput; first-order conservation architecture.
- **Addenda 120 and 122:** native identity and whole-enclosing compatibility before presentation and relational composition.
- **Addenda 125 and 131:** possible and realized closure counts, and complete background-relative recurrence.
- **Addendum 139:** relational readability across recursive backgrounds and complete comparison records.
- **Addendum 152 — States and Processes as Complementary Reads of Enclosing Compatibility:** finite measurable event domains, complete-process compatibility, and process-first reconstruction of native state classifications.

**Review status:** Author-approved for canon publication; all physical continuum and Hamiltonian reads are conditional on the explicitly stated real, orientation, and calibration data.
