---
r2d_id: addendum-072
title: Addendum 72 — Closure Phase Occurs Before Complex Amplitude
subtitle: Recursive Replacement, Boundary-Native Recurrence, Cyclic Representation, and the Burden of Constructing the Quantum State Vector
source_type: addendum
authority: addendum
text_status: candidate_reconstruction_pending_author_review
indexable: true
addendum: 72
unit: addendum
integrated_in_publication_canon: false
canon_revision: '2026-09-25'
publication_baseline_snapshot: '2026-09-14'
source_format: candidate_markdown_reconstruction
source_pdf: R2D 9-14-2026.pdf
source_pdf_sha256: ab2892f9dc60ac99feec22fc3df72feac72f0500f5953f6014dbecb36286c415
pdf_page_start: 2382
pdf_page_end: 2415
math_representation: LaTeX for normalized equations; source PDF layout text retained for remaining equations
equation_status: candidate_visual_reconstruction_pending_author_review
equation_audit_scope: archived_pdf_visual_comparison; author_review_pending
primitive_authority: false
review_status: author_reviewed
semantic_sync: 2026-09-25-structural-universality-preserved-domain-mappings-remain-testable
machine_revision: 2026-10-09-equation-reconstruction-v1
qa_status: standalone_render_pass_full_book_pending
promotion_date: null
equation_source_conflict_rule: publication_pdf_controls
---

# Addendum 72 — Closure Phase Occurs Before Complex Amplitude

*Recursive Replacement, Boundary-Native Recurrence, Cyclic Representation, and the Burden of Constructing the Quantum State Vector*

## Abstract

<!-- source_pdf_page: 2382 -->

Quantum mechanics is conventionally formulated through complex amplitudes.

A physical state is represented by a vector

$$|\psi\rangle$$

whose components are complex numbers.

Those components evolve through complex phase, interfere linearly, and produce observed outcome
weights through their squared magnitudes.

R2D cannot begin there.

The complex quantum state vector is already a mature physical projection containing several logically
distinct structures:

- recurrence;
- phase;
- amplitude;
- linear superposition;
- orthogonality;
- normalization;
- basis transformation;
- and measurement weight.

These structures must be separated.

The first quantum-side relation is more primitive.

At a quantum boundary Bn , the subordinate path at Bn−1 has already been recursively replaced.

The boundary Bn does not contain that subordinate trajectory as a hidden path waiting to be resolved.

Instead, Bn possesses its own native recurrence relation.

<!-- source_pdf_page: 2383 -->

Thus the R2D ordering is

> subordinate closure → recursive replacement → boundary-native recurrence → phase.

Only after a physical spatial and temporal mapping is supplied does that phase acquire a wave
representation.

Therefore:

> phase occurs before wave.

The integrated R2D development already identified recurrence as primary to wave and particle description,
with particle count reading completed occurrences and wave/phase reading their recurrence relation. It
also explicitly stated that the complex phase is a representation of recurrence rather than recurrence itself.

This addendum strengthens that result.

Suppose a boundary-native closure contains Kn distinguishable ordered recurrence positions:

$$ j=0,1,\ldots,K_n-1. $$

Closure requires

$$ j+K_n\sim j. $$

Composition is therefore addition modulo Kn :

$$ j\oplus r=(j+r)\bmod K_n. $$

The recurrence positions form the cyclic group

$$ C_{K_n}\cong\mathbb Z/K_n\mathbb Z. $$

This structure exists before quantum amplitude, before wave mechanics, and before a physical continuum
coordinate is assigned.

Its one-dimensional complex unitary representations are

$$ \chi_m(j)=\exp\!\left(i\frac{2\pi mj}{K_n}\right), $$

with m defined modulo Kn .

These satisfy

$$ \chi_m(j\oplus r)=\chi_m(j)\chi_m(r), $$

<!-- source_pdf_page: 2384 -->

and automatically preserve closure:

$$\chi_m(j+K_n)=\chi_m(j)$$

For m = 1,

$$ z_j=e^{i2\pi j/K_n}$$

is a faithful one-complex-dimensional representation of the ordered cyclic closure.

Thus complex phase need not be introduced as primitive mathematical substance.

It follows naturally as a representation of closure composition.

The ordering becomes

> boundary-native closure → CKn → eiϕ .

If the physical recurrence is subsequently represented by a continuously parameterized phase coordinate,

$$ \phi\in\mathbb R/2\pi\mathbb Z, $$

then

$$ z(\phi)=e^{i\phi}$$

and

$$ z(\phi+2\pi)=z(\phi)$$

The continuously parameterized physical representation is therefore the circle group

$$ U(1)$$

The continuous phase representation comes after the closure relation.

It does not define the primitive count domain.

The complex unit i then acquires a simple mathematical role.

Because

$$ z(\phi)=e^{i\phi},\qquad\frac{dz}{d\phi}=iz. $$

<!-- source_pdf_page: 2385 -->

After a physical clock calibration gives

$$ \frac{d\phi}{dt}=\omega, $$

the recurrence representation satisfies

$$\frac{dz}{dt}=i\omega z$$

up to the chosen orientation convention.

Thus the appearance of i in quantum evolution need not begin as an unexplained algebraic postulate.

It is already the generator of oriented cyclic phase in the complex representation of closure.

But this does not yet derive the Schrödinger equation.

Nor does it derive a quantum amplitude.

Nor does it derive a Hilbert space.

The distinction is essential.

Closure gives

$$ e^{i\phi}$$

A complex amplitude requires

$$ Ae^{i\phi}$$

A quantum state vector requires

$$|\psi\rangle=\sum_i A_i e^{i\phi_i}|i\rangle$$

And the Born rule requires a further relation between realized physical count and

$$|\langle i|\psi\rangle|^2$$

These are different mathematical steps.

The present integrated R2D text currently writes

$$\psi=Ae^{i\phi}$$

<!-- source_pdf_page: 2386 -->

and correctly states that the amplitude A has not yet been identified term by term with primitive
multiplicity or occupancy.

It then proposes the stronger mapping

$$\psi_i=\sqrt{c_i}\,e^{i\phi_i}$$

which implies

$$|\psi_i|^2=c_i$$

and yields a normalized occupancy weight.

This addendum sharpens the logical status of that step.

The phase factor

$$ e^{i\phi_i}$$

follows naturally from recurrent closure.

The magnitude

$$ c_i$$

does not yet.

The mapping

$$\psi_i=\sqrt{c_i}\,e^{i\phi_i}$$

must therefore remain a candidate bridge until R2D establishes why quantum amplitude magnitude is the
square root of the relevant realized count rather than the count itself, multiplicity, occurrence count, or
another boundary quantity.

The burden of constructing the quantum state vector is therefore now sharply defined.

R2D must explain:

1. what the quantum alternatives i are;
2. why each alternative carries a complex closure phase;
3. what primitive count variable determines amplitude magnitude;
4. why alternative coordinates combine linearly;
5. why the invariant physical norm is quadratic;
6. why changes among complete classifications are unitary;
7. why normalized realized count is read as squared amplitude in every admissible measurement basis;

<!-- source_pdf_page: 2387 -->

8. and how joint boundaries generate the tensor-product structure required by composite quantum systems.

One further result follows immediately from the cyclic representation.

The characters of $C_{K_n}$ are orthogonal:

$$\frac1{K_n}\sum_{j=0}^{K_n-1}\chi_m^*(j)\chi_{m'}(j)=\delta_{mm'}$$

Thus ordered closure gives not only complex phase but a natural set of orthogonal phase classes.

Any function defined on the recurrent closure can therefore be expanded as

$$ g(j)=\sum_m\widetilde g_m\chi_m(j)$$

with

$$\widetilde g_m=\frac1{K_n}\sum_jg(j)\chi_m^*(j)$$

The coefficients

$$\widetilde g_m$$

are complex.

This provides a possible mathematical bridge from recursive counting to complex vector representation.

But a Fourier coefficient on a closure domain is not automatically a quantum probability amplitude.

That identification remains to be derived.

The central statement is therefore:

at a quantum boundary, subordinate trajectory identity has already been recursively replaced. What remains is boundary-native recurrence. Ordered closure gives that recurrence a cyclic composition law, whose natural faithful unitary representation is complex phase. Phase therefore follows from closure before any wave, amplitude, or quantum state vector is assigned. A wave appears only after recurrence phase is mapped into physical space and clock time. The amplitude magnitude, linear state space, quadratic norm, and Born rule remain separate mathematical burdens.

And hence:

> closure phase occurs before complex amplitude.

<!-- source_pdf_page: 2388 -->

## 1. The Quantum Boundary Must Be Defined Before the Quantum State

Let

$$ B_n$$

be a quantum-side R2D boundary.

Its states and transitions are defined only relative to that boundary.

The first question is therefore not:

> What is the wavefunction?

It is:

> What recurrence relation remains native to this boundary after recursive replacement?

## 2. The Subordinate Boundary Has Its Own State Domain

Let

$$ B_{n-1}$$

be an immediate subordinate boundary.

Its native states belong to

$$\mathcal M_{n-1}$$

Its closure occurs within that state domain.

## 3. A Subordinate Closure May Be Written Schematically As

$$ a\to b\to c\to\cdots\to a$$

This path belongs to Bn−1 .

<!-- source_pdf_page: 2389 -->

## 4. Recursive Carry Does Not Preserve That Path as Hidden State Identity

When closure at Bn−1 participates in realization of Bn , the internal sequence

$$ a\to b\to c\to a$$

does not remain a state trajectory at Bn .

The count domain has changed.

## 5. Therefore

subordinate path identity ∉ native state content of Bn.

This is recursive replacement.

It is not coarse-graining.

## 6. The Quantum Boundary Does Not Contain an Unseen Classical Path

R2D therefore does not begin with

> classical trajectory → hidden quantum trajectory.

There is no requirement that the enclosing quantum boundary preserve a continuously existing
subordinate path.

## 7. The Correct Ordering Is

> subordinate closure

> ↓

> recursive replacement

> ↓

> native recurrence at Bn .

<!-- source_pdf_page: 2390 -->

## 8. Recurrence Is Therefore Boundary Native

The recurrence read at Bn belongs to Bn .

It is not the subordinate path with its details hidden.

## 9. This Is the Quantum-Side Readability Condition

At the quantum boundary:

> recurrence remains readable

while

> subordinate path identity has been replaced.

The current integrated R2D architecture already distinguishes the surviving quantum-side recurrence from
the subordinate geometry that is no longer jointly readable.

## 10. Recurrence Comes Before Phase

A recurrent relation must close.

Let one native closure contain

$$ K_n$$

distinguishable ordered positions.

## 11. Label Those Positions

$$ j=0,1,\ldots,K_n-1$$

The labels are recurrence positions.

They are not yet spatial positions.

## 12. Closure Requires

$$ j+K_n\sim j$$

<!-- source_pdf_page: 2391 -->

Thus the recurrence returns to the same boundary-defined relation after Kn ordered updates.

## 13. Composition Is Modular

For two recurrence increments j and r ,

$$ j\oplus r=(j+r)\bmod K_n$$

## 14. The Closure Therefore Has a Cyclic Algebra

$$ C_{K_n}\cong\mathbb Z/K_n\mathbb Z$$

This structure follows directly from ordered recurrence and closure.

## 15. No Complex Number Has Yet Been Introduced

At this stage there is only:

- a boundary;
- an ordered recurrent relation;
- and closure modulo Kn .

## 16. Phase Is a Coordinate on That Closure

Define

$$\phi_j=\frac{2\pi j}{K_n}$$

Then:

$$\phi_{j+K_n}=\phi_j+2\pi$$

## 17. Closure Identifies Phase Modulo 2π

$$\phi\sim\phi+2\pi$$

Thus phase is not an unrestricted linear coordinate.

<!-- source_pdf_page: 2392 -->

It is cyclic.

## 18. Complex Phase Represents the Cyclic Composition Law

Define

$$ z_j=e^{i2\pi j/K_n}$$

## 19. Closure Is Automatic

$$ z_{j+K_n}=e^{i2\pi(j+K_n)/K_n}=e^{i2\pi j/K_n}e^{i2\pi}$$

Since

$$ e^{i2\pi}=1$$

$$ z_{j+K_n}=z_j$$

## 20. Recurrence Composition Becomes Multiplication

$$ z_{j\oplus r}=z_jz_r$$

Thus the complex representation preserves the closure algebra.

## 21. More Generally, the Cyclic Characters Are

$$\chi_m(j)=e^{i2\pi mj/K_n}$$

Here m labels the different one-dimensional complex representations of the same closure domain.

## 22. They Satisfy

$$\chi_m(j\oplus r)=\chi_m(j)\chi_m(r)$$

<!-- source_pdf_page: 2393 -->

## 23. The m = 1 Character Is Faithful

$$ z_j=e^{i2\pi j/K_n}$$

Distinct recurrence positions map to distinct points on the unit circle.

## 24. Therefore Complex Phase Has a Specific R2D Role

> complex phase = representation of ordered cyclic closure.

It is not the primitive recurrence itself.

## 25. This Strengthens the Existing Phase Principle

The integrated R2D manuscript already states that cyclic recurrence is naturally represented by phase and
that

$$ e^{i(\phi+2\pi)}=e^{i\phi}$$

automatically expresses closure while maintaining unit magnitude.

The present addendum identifies the underlying algebra explicitly as a cyclic closure group.

## 26. Complex Numbers Are Not Primitive Substance

The same representation can be written

$$ e^{i\phi}=\cos\phi+i\sin\phi$$

This encodes a two-dimensional real rotation in one algebraic quantity.

## 27. Thus i Need Not Be Given Ontological Meaning

The imaginary unit belongs to the representation of oriented cyclic composition.

It is not a second hidden physical substance.

<!-- source_pdf_page: 2394 -->

## 28. Continuous Phase Comes Later

If the physical recurrence is represented continuously, define

$$\phi\in\mathbb R/2\pi\mathbb Z$$

Then:

$$ z(\phi)=e^{i\phi}$$

## 29. The Continuous Phase Representation Is U (1)

$$ U(1)=\{e^{i\phi}:\phi\in\mathbb R\}$$

This is the continuously parameterized representation of cyclic closure.

## 30. The Count Domain Still Comes First

The existence of a smooth U (1) representation does not mean primitive R2D recurrence must itself be a
continuum.

The physical representation can be continuous after the underlying closure relation has been defined.

## 31. Oriented Phase Has a Natural Generator

For

$$ z=e^{i\phi}$$

$$\frac{dz}{d\phi}=iz$$

## 32. Physical Clock Calibration Introduces ω

If

$$\frac{d\phi}{dt}=-\omega$$

<!-- source_pdf_page: 2395 -->

then:

$$\frac{dz}{dt}=-i\omega z$$

The opposite closure orientation gives the opposite sign.

## 33. Thus iω Is a Phase Generator

The combination

$$-i\omega$$

generates continuous oriented recurrence in the complex phase representation.

## 34. This Is Not Yet Schrödinger Evolution

The relation

$$\frac{dz}{dt}=-i\omega z$$

describes one complex phase coordinate.

It does not yet establish:

$$ i\hbar\frac{\partial\psi}{\partial t}=\hat H\psi$$

## 35. Energy Calibration Comes Later

Only after the physical mapping

$$ E=\hbar\omega$$

is supplied can temporal phase recurrence acquire an energetic place value.

The integrated R2D manuscript already treats E = ℏω and p = ℏk as empirical physical phase calibrations
rather than primitive count identities.

<!-- source_pdf_page: 2396 -->

## 36. Phase Exists Before Wave

Nothing in

$$ C_{K_n},\quad\phi_j,\quad e^{i\phi_j}$$

requires a spatial coordinate.

## 37. Therefore Phase Is Not Initially a Wave Phase

It is first the cyclic coordinate of boundary-native recurrence.

## 38. A Wave Requires a Later Distributed Physical Mapping

Once physical space and clock time are supplied, one may represent recurrence as

$$\phi(x,t)=\mathbf k\cdot\mathbf x-\omega t+\phi_0$$

## 39. Then the Corresponding Wave Representation Is

$$ e^{i(\mathbf k\cdot\mathbf x-\omega t+\phi_0)}$$

The wave is therefore a distributed physical representation of already-defined recurrence phase.

## 40. The Logical Order Is

> closure → phase → space-time phase field → wave.

## 41. Not

> wave → phase.

Phase is more primitive in the R2D projection hierarchy.

## 42. This Matters for Nonspatial Quantum Degrees of Freedom

A state can carry phase without being represented as a literal spatial wave.

<!-- source_pdf_page: 2397 -->

This will become important for:

- stationary states;
- spin;
- internal state recurrence;
- relative phase between alternatives;
- and gauge structure.

## 43. The Wave Does Not Contain the Recurrence

Nor does recurrence require a material wave medium.

Wave form is one later physical projection of phase.

## 44. Absolute Phase Zero Is Not Defined by Closure

A cycle has no distinguished primitive point that must be labeled

$$\phi=0$$

## 45. Therefore

$$\phi\to\phi+\alpha$$

changes the coordinate origin without changing the cyclic closure itself.

## 46. Relative Phase Is Preserved

For two closure phases,

$$(\phi_i+\alpha)-(\phi_j+\alpha)=\phi_i-\phi_j$$

Thus:

$$\Delta\phi_{ij}$$

is invariant under a common phase shift.

<!-- source_pdf_page: 2398 -->

## 47. This Is the Seed of Global Gauge Freedom

The later quantum transformation

$$\psi\to e^{i\alpha}\psi$$

can preserve physical relational structure because absolute phase zero is not supplied by the primitive
closure.

The integrated manuscript already identifies this distinction between physical recurrence and arbitrary
absolute phase reference.

## 48. Counting Gives Invariance; Reference Choice Gives Freedom

The recurrence itself closes.

Changing the phase-zero convention does not change that closure.

Thus:

> closure invariance + phase-reference freedom → global phase redundancy.

## 49. Cyclic Closure Also Generates Orthogonality

Consider two cyclic characters

$$\chi_m(j)=e^{i2\pi mj/K_n}$$

and

$$\chi_{m'}(j)$$

Their normalized overlap over one complete closure is

$$\frac1{K_n}\sum_{j=0}^{K_n-1}\chi_m^*(j)\chi_{m'}(j)=\delta_{mm'}$$

<!-- source_pdf_page: 2399 -->

## 50. Substitute the Character Form

$$\frac1{K_n}\sum_{j=0}^{K_n-1}e^{i2\pi(m'-m)j/K_n}$$

## 51. If m = m′

Every term equals one.

Therefore:

$$\frac1{K_n}\sum_j1=1$$

## 52. If $m\ne m'$

The terms form a complete set of equally spaced phases around the unit circle.

Their sum vanishes.

Thus:

$$\frac1{K_n}\sum_{j=0}^{K_n-1}\chi_m^*(j)\chi_{m'}(j)=0$$

## 53. Therefore

$$\frac1{K_n}\sum_{j=0}^{K_n-1}\chi_m^*(j)\chi_{m'}(j)=\delta_{mm'}$$

The closure characters form an orthogonal basis on the cyclic count domain.

## 54. This Is Potentially the First Bridge Toward Quantum State Space

Quantum mechanics requires orthogonal complex state coordinates.

Ordered closure already supplies orthogonal complex phase classes.

<!-- source_pdf_page: 2400 -->

## 55. But This Is Not Yet Hilbert Space

The closure-character space is a finite complex function space over one cyclic domain.

R2D still must establish why the full physically admissible quantum state space inherits the required linear
inner-product structure.

## 56. Any Function on the Closure Can Be Expanded in Characters

Let

$$ g(j)$$

be a quantity defined over the closure positions.

Then:

$$ g(j)=\sum_m\widetilde g_m\chi_m(j)$$

## 57. The Coefficients Are

$$\widetilde g_m=\frac1{K_n}\sum_jg(j)\chi_m^*(j)$$

These coefficients are naturally complex.

## 58. Complex Vector Coordinates Therefore Arise Naturally From Closure Decomposition

The vector

$$(\widetilde g_0,\widetilde g_1,\ldots)$$

is a complex coordinate representation of a function on the cyclic closure.

<!-- source_pdf_page: 2401 -->

## 59. This Is Important but Insufficient

A complex Fourier coefficient is not automatically a quantum probability amplitude.

R2D must not identify the two merely because both are complex.

## 60. Phase Must Therefore Be Separated From Amplitude

Closure directly supplies

$$ e^{i\phi}$$

It does not directly supply

$$ A$$

## 61. The Wavefunction Contains Both

Conventionally,

$$\psi=Ae^{i\phi}$$

The integrated R2D text already recognizes this distinction and states that amplitude weight has not yet
been identified term-by-term with primitive multiplicity or occupancy.

## 62. Therefore

> phase derivation ≠ amplitude derivation.

The former can now be traced to closure.

The latter remains open.

## 63. The Candidate Occupancy Mapping Must Be Reclassified

The current candidate is

$$\psi_i=\sqrt{c_i}\,e^{i\phi_i}$$

This gives

<!-- source_pdf_page: 2402 -->

ψi∗ ψi = ci .

## 64. Algebraically This Is Correct

If one chooses

$$ A_i=\sqrt{c_i}$$

then

$$|\psi_i|^2=c_i$$

## 65. But R2D Has Not Yet Derived the Choice

The theory must still explain why

$$ A_i=\sqrt{c_i}$$

rather than

$$ A_i=c_i$$

or a function of

$$ W_i,\quad\nu_i,\quad A_{i}^{\mathrm{asymmetry}}$$

or another boundary quantity.

## 66. The Frozen Count Distinction Must Be Preserved

$$ W_i\ne\nu_i\ne c_i$$

A quantum amplitude mapping must specify which count it reads and why.

## 67. Multiplicity Cannot Be Substituted Silently

Possible multiplicity is

$$ W_i$$

Dynamic occupancy is

<!-- source_pdf_page: 2403 -->

ci .

Realized occurrence count is

$$\nu_i$$

The amplitude cannot be called “the square root of count” until count ownership is fixed.

## 68. The First Burden Is to Define the Alternatives

A quantum state is written

$$|\psi\rangle=\sum_i\psi_i|i\rangle$$

What are the ∣i⟩?

R2D must assign their boundary ownership.

## 69. They Cannot Be Assumed to Be Primitive Objects

The alternatives may correspond to:

- boundary macrostates;
- recurrence classes;
- orientation classes;
- detector distinctions;
- or another complete boundary classification.

The mapping must be derived for each physical representation.

## 70. The Second Burden Is Amplitude Magnitude

For each alternative i, R2D must derive

$$ A_i=F(\text{R2D count structure})$$

The function F is presently unknown.

<!-- source_pdf_page: 2404 -->

## 71. The Third Burden Is Linear Superposition

Quantum mechanics requires

$$|\psi\rangle=\sum_i\psi_i|i\rangle$$

Closure phase alone gives multiplication under recurrent composition.

It does not by itself derive linear addition among alternatives.

## 72. This Is a Distinct Mathematical Requirement

R2D must explain why compatible alternative recurrence coordinates satisfy a linear composition law.

That is the doorway from cyclic representation to vector space.

## 73. The Fourth Burden Is the Inner Product

Quantum mechanics requires a Hermitian inner product

$$\langle\phi|\psi\rangle$$

The cyclic character orthogonality derived above is suggestive.

It does not yet establish the complete physical inner product.

## 74. The Fifth Burden Is the Quadratic Norm

Quantum states use

$$\|\psi\|^2=\langle\psi|\psi\rangle=\sum_i|\psi_i|^2$$

Why this quadratic form is the preserved physical count measure must be derived.

## 75. The Sixth Burden Is Normalization

Conventionally,

<!-- source_pdf_page: 2405 -->

∑ ∣ψi ∣2 = 1.

$$ i$$

R2D must determine what conserved or normalized count this represents.

## 76. The Seventh Burden Is Basis Independence

Suppose one complete classification uses states

$$|i\rangle$$

Another uses

$$|\alpha\rangle$$

Quantum mechanics demands a consistent transformation between them.

## 77. Count Preservation Suggests Norm Preservation

If complete physical classification changes without changing total realized support, then the state-space
transformation should preserve the relevant norm.

This is the likely route toward unitarity.

## 78. But Unitarity Must Be Earned

One cannot simply assume

$$ U^\dagger U=I$$

R2D must establish why admissible changes of complete quantum classification are linear and norm
preserving.

## 79. The Eighth Burden Is the General Born Rule

Even if one fixed basis satisfies

$$ c_i\propto|\psi_i|^2$$

the full Born rule requires

<!-- source_pdf_page: 2406 -->

p(i∣ψ) = ∣⟨i∣ψ⟩∣2

for every admissible complete measurement basis.

## 80. A Fixed-Basis Occupancy Identity Is Not Enough

This distinction is already recognized elsewhere in the R2D development: a detector occupancy law does not
by itself establish the general projective Born rule.

## 81. The Ninth Burden Is Composite State Structure

For two peer boundaries A and B , conventional quantum theory uses

$$\mathcal H_{AB}=\mathcal H_A\otimes\mathcal H_B$$

R2D must derive why joint boundary realization acquires tensor-product representation.

## 82. This Will Matter for Entanglement

An enclosing joint boundary may possess a state that does not factor:

$$|\Psi_{AB}\rangle\ne|\psi_A\rangle\otimes|\psi_B\rangle$$

But tensor structure must be established before this becomes a derived quantum result.

## 83. Therefore Three Levels Must Remain Distinct

$$\text{closure phase}\ne\text{complex amplitude}\ne\text{quantum state vector}$$

## 84. Closure Phase Is

$$ e^{i\phi}$$

<!-- source_pdf_page: 2407 -->

It represents cyclic recurrence.

## 85. Complex Amplitude Is

$$ Ae^{i\phi}$$

It adds a magnitude weight not yet derived from closure alone.

## 86. A Quantum State Vector Is

$$|\psi\rangle=\sum_i A_i e^{i\phi_i}|i\rangle$$

It adds an alternative basis and a linear vector-space structure.

## 87. The Born Rule Adds Another Layer

$$|\langle i|\psi\rangle|^2$$

That relation is not contained in cyclic phase alone.

## 88. Principle — Subordinate Path Replacement Precedes Quantum Recurrence

At a quantum boundary, subordinate trajectory identity has already been recursively replaced.

The recurrence read at the quantum boundary is native to that boundary.

## 89. Principle — Boundary-Native Recurrence Precedes Phase

A closure must recur before a cyclic coordinate can represent it.

Thus:

> recurrence → phase.

<!-- source_pdf_page: 2408 -->

## 90. Principle — Closure Defines a Cyclic Composition Law

For Kn ordered recurrence positions,

$$ j+K_n\sim j$$

defines

$$ C_{K_n}$$

## 91. Principle — Complex Phase Represents Closure

$$ C_{K_n}\to e^{i2\pi j/K_n}$$

Complex phase is a faithful representation of cyclic closure, not a primitive substance.

## 92. Principle — Continuous Phase Is a Later Physical Representation

$$ C_{K_n}\to U(1)$$

only after recurrence receives a continuously parameterized physical phase read.

## 93. Principle — Phase Precedes Wave

A recurrence can possess phase before any spatial coordinate is assigned.

Thus:

> phase → wave projection.

## 94. Principle — Wave Is a Distributed Phase Read

Once physical space and time are defined,

$$\phi(x,t)=\mathbf k\cdot\mathbf x-\omega t+\phi_0$$

and the wave representation follows.

<!-- source_pdf_page: 2409 -->

## 95. Principle — Absolute Phase Zero Is Not Primitive

Closure does not select a unique origin.

Thus:

$$\phi\to\phi+\alpha$$

can preserve the same physical closure relations.

## 96. Principle — Closure Characters Are Naturally Orthogonal

$$\frac1{K_n}\sum_{j=0}^{K_n-1}\chi_m^*(j)\chi_{m'}(j)=\delta_{mm'}$$

Orthogonal complex phase classes therefore arise before a general Hilbert-space postulate.

## 97. Principle — Orthogonality Does Not Yet Derive Quantum State Space

The cyclic character basis is a mathematical consequence of closure.

The physical identification of general quantum states with a complex inner-product space remains a
separate bridge.

## 98. Principle — Phase Does Not Determine Amplitude Magnitude

Closure provides

$$ e^{i\phi}$$

It does not yet provide

$$ A$$

## 99. Principle —            c Is a Candidate Mapping, Not Yet a Primitive Result

$$\psi_i=\sqrt{c_i}\,e^{i\phi_i}$$

<!-- source_pdf_page: 2410 -->

is compatible with

$$|\psi_i|^2=c_i$$

but the square-root mapping must still be derived from R2D count architecture.

## 100. Principle — The State Vector Requires Additional Structure

A quantum state vector requires:

alternatives + amplitude magnitudes + closure phases + linear composition + inner product.

Closure phase supplies only one part.

## 101. Logical Status

Canonical R2D

States are boundary indexed.

Recursive replacement changes the count domain.

Subordinate state identity does not persist as hidden state identity at the enclosing boundary.

Quantum Readability Architecture

At the quantum-side boundary:

> boundary-native recurrence remains readable

after subordinate path identity has been replaced.

New Closure Result

For a Kn -position recurrent closure:

$$ C_{K_n}\cong\mathbb Z/K_n\mathbb Z$$

New Complex-Phase Representation

$$\chi_m(j)=e^{i2\pi mj/K_n}$$

<!-- source_pdf_page: 2411 -->

New Orthogonality Result

$$\frac1{K_n}\sum_{j=0}^{K_n-1}\chi_m^*(j)\chi_{m'}(j)=\delta_{mm'}$$

Continuous Physical Phase Representation

$$ z(\phi)=e^{i\phi},\qquad z(\phi+2\pi)=z(\phi)$$

Physical Clock Mapping

$$\dot\phi=-\omega$$

Imported Quantum Energetic Calibration

$$ E=\hbar\omega$$

Later Wave Projection

$$\phi(x,t)=\mathbf k\cdot\mathbf x-\omega t+\phi_0$$

Candidate Amplitude Mapping

$$\psi_i=\sqrt{c_i}\,e^{i\phi_i}$$

Not Yet Established

This addendum does not yet derive:

- amplitude magnitude from primitive R2D count structure;
- why Ai = ci ;
- linear superposition of alternatives;
- the full complex vector space of quantum states;
- the Hermitian inner product;
- quadratic norm preservation;
- unitarity;
- the basis-independent Born rule;
- tensor-product composition;
- or Schrödinger dynamics.

Those are now separate, explicit mathematical burdens.

## 102. The Complete Phase Architecture

A subordinate boundary closes:

<!-- source_pdf_page: 2412 -->

Bn−1 : a → b → c → a.

Its path identity is recursively replaced:

$$\downarrow$$

$$ B_n$$

The enclosing boundary possesses native recurrence:

$$\downarrow$$

$$ j+K_n\sim j$$

The recurrence has cyclic algebra:

$$\downarrow$$

$$ C_{K_n}$$

The cyclic algebra admits complex phase representation:

$$\downarrow$$

$$ e^{i2\pi j/K_n}$$

Continuous physical phase can then be assigned:

$$\downarrow$$

$$ e^{i\phi}$$

Physical clock and space mapping can then produce:

$$\downarrow$$

$$ e^{i(\mathbf k\cdot\mathbf x-\omega t)}$$

Only afterward does the wavefunction problem begin:

$$\downarrow$$

$$ Ae^{i\phi}$$

And only after amplitude magnitudes and alternative composition are derived does one obtain:

$$\downarrow$$

$$|\psi\rangle=\sum_i A_i e^{i\phi_i}|i\rangle$$

<!-- source_pdf_page: 2413 -->

Thus:

subordinate closure→replacement→native recurrence→cyclic phase→complex representation→wave→amplitude→state vector.

## 103. Conclusion

Quantum mechanics is written in complex numbers.

That fact is often accepted at the beginning of the theory.

R2D asks what physical relation exists before the complex quantum amplitude.

The answer begins with recursive replacement.

At a quantum boundary, the subordinate trajectory is not hidden beneath the quantum state.

It has already ceased to be a state trajectory at that boundary.

Its closure participates in realization of a new count domain.

The enclosing boundary then possesses its own native recurrence.

That recurrence is what remains physically readable.

A recurrent relation must close.

If one closure contains Kn ordered recurrence positions,

$$ j+K_n\sim j$$

The positions form the cyclic group

$$ C_{K_n}$$

That cyclic composition has the natural complex representation

$$ z_j=e^{i2\pi j/K_n}$$

Complex phase is therefore not inserted arbitrarily.

It is the compact unitary representation of oriented recurrent closure.

When physical phase is continuously parameterized,

<!-- source_pdf_page: 2414 -->

eiϕ

provides the corresponding U (1) representation.

The imaginary unit then appears naturally as the generator of oriented phase evolution:

$$\frac{dz}{d\phi}=iz$$

None of this requires a spatial wave.

Phase comes first.

Only after phase is mapped into physical space and clock time does one obtain

$$ e^{i(\mathbf k\cdot\mathbf x-\omega t+\phi_0)}$$

Thus the wave is not the primitive carrier of phase.

It is a later physical representation of recurrence phase.

Closure also explains why absolute phase zero is not primitive.

A cycle does not possess a unique physically preferred starting label.

Therefore a common shift

$$\phi\to\phi+\alpha$$

can preserve all relative recurrence relations.

This is the count-theoretic seed of global phase freedom.

Ordered cyclic closure supplies another important structure.

Its complex characters are orthogonal:

$$\frac1{K_n}\sum_{j=0}^{K_n-1}\chi_m^*(j)\chi_{m'}(j)=\delta_{mm'}$$

Thus complex orthogonal phase coordinates arise directly from recurrent closure.

This gives R2D a plausible mathematical path toward quantum state space.

But it does not complete that path.

<!-- source_pdf_page: 2415 -->

A complex phase is not yet a complex amplitude.

A complex amplitude is not yet a quantum state vector.

And a quantum state vector is not yet a Born rule.

The phase factor

$$ e^{i\phi}$$

has now acquired a clear R2D origin.

The amplitude magnitude

$$ A$$

has not.

The current candidate

$$ A_i=\sqrt{c_i}$$

is mathematically attractive because it gives

$$|\psi_i|^2=c_i$$

But R2D must still establish why occupancy enters through a square root, why the relevant count is
occupancy rather than multiplicity or occurrence, why alternative amplitudes add linearly, why the
quadratic norm is invariant, and why the same count rule survives every complete change of measurement
basis.

Those are the next problems.

The central statement is therefore:

at the quantum boundary, subordinate trajectory identity has already been recursively replaced. What survives is boundary-native recurrence. Ordered recurrence closes cyclically; cyclic closure possesses a natural complex unitary phase representation; and that phase exists before any spatial wave, amplitude magnitude, or quantum state vector is assigned. Complex phase therefore has a direct R2D origin in closure, while complex amplitude remains a separate structure to be derived.

And hence:

closure phase occurs before complex amplitude.
